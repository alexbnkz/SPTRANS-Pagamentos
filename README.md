# SPTRANS Folha De Pagamentos
Extração de dados com Requests para listar pagamentos da SPTRANS - São Paulo Transporte

## Modo de usar

Execute o arquivo run.py:

```bash
python run.py
```

## Resultado

**Schema**

- empresa: string
- mes: string
- ano: string
- nome: string
- cargo: string
- lotacao: string
- admissao: string
- nascimento: string
- vencimentos: string
- encargos: string
- beneficios: string
- outras_remuneracoes: string
- vinculo: string
- detalhe_vinculo: string
- liminar: string
- arquivo_id: string

**Dados**

```json
{
    "empresa": "SPTRANS",
    "mes": "1",
    "ano": "2020",
    "nome": "MARA FERNANDA FORMAGIO TSUSHIMA",
    "cargo": "TCNICO DE PROC. ADM. PL - ADM. GERAL",
    "lotacao": "DO/SOP/RSU-GER REGIONAL OPERACOES SUL",
    "admissao": "06/02/1990",
    "nascimento": "1969",
    "vencimentos": "R$11.645,39",
    "encargos": "R$2.248,34",
    "beneficios": "R$2.429,70",
    "outras_remuneracoes": "R$-",
    "vinculo": "CLT: contrato por tempo indeterminado",
    "detalhe_vinculo": "Concursado NO ocupante de cargo em comisso",
    "liminar": "-",
    "arquivo_id": "fd5c5c41-6907-486f-a41a-e6fb8cbb142c"
}
```