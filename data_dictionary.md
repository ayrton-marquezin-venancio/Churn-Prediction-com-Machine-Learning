# 📖 Dicionário de Dados

A base utilizada neste projeto é **sintética** e foi criada exclusivamente para fins educacionais.

| Coluna | Tipo | Descrição |
|---|---|---|
| `Cliente_ID` | Texto | Identificador único do cliente. Não é usado como variável preditora. |
| `Genero` | Categórica | Gênero informado no registro. |
| `Idade` | Numérica | Idade do cliente em anos. |
| `Parceiro` | Categórica | Indica se o cliente possui parceiro(a). |
| `Dependentes` | Categórica | Indica se possui dependentes. |
| `Tempo_Cliente_Meses` | Numérica | Tempo de relacionamento com a empresa, em meses. |
| `Tipo_Contrato` | Categórica | Tipo de contrato: mensal, anual ou bienal. |
| `Servico_Internet` | Categórica | Tipo de serviço de internet contratado. |
| `Suporte_Tecnico` | Categórica | Indica disponibilidade/contratação de suporte técnico. |
| `Streaming` | Categórica | Indica contratação de serviço de streaming. |
| `Cobranca_Sem_Papel` | Categórica | Indica adesão à cobrança digital. |
| `Metodo_Pagamento` | Categórica | Forma de pagamento utilizada. |
| `Chamadas_Suporte_6M` | Numérica | Quantidade de chamadas ao suporte nos últimos 6 meses. |
| `Atrasos_Pagamento_12M` | Numérica | Quantidade de atrasos de pagamento nos últimos 12 meses. |
| `Valor_Mensal` | Numérica | Valor mensal cobrado do cliente. |
| `Valor_Total` | Numérica | Valor acumulado aproximado durante o relacionamento. |
| `Satisfacao` | Ordinal | Nota de satisfação de 1 a 5. |
| `Churn` | Alvo | `Sim` = cliente saiu; `Não` = cliente permaneceu. |

## Valores ausentes

Algumas colunas possuem valores ausentes propositalmente para permitir a prática de pré-processamento e imputação.

A variável alvo `Churn` não possui valores ausentes.
