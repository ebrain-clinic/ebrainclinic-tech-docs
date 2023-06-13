# Operadora de saúde
<p align="justify"> 
Neste documento, estão descritos os campos necessários para importar os dados das operadoras de saúde no sistema Ebrain. A tabela de descrição dos campos abrange as principais informações dessas operadoras/convênios médicos.
 </p>

 ## Descrição dos campos

| Campo                       | Tipo      | Descrição                                                                  | Restrição       |
|-----------------------------|-----------|----------------------------------------------------------------------------|-----------------|
| externo_cod                 | varchar     | Código único da operadora de saúde                       |     Obrigatório            |
| nome               | varchar | Nome da operadora de saúde                                       |   Obrigatório              |
| data_registro          | Timestamp     | Data do registro                        |   Obrigatório              |
| registro_ans    | varchar     | Registro ANS da operadora de saúde                 |                 |
| codigo_na_operadora | varchar     |   Código usado na operadora                           |                 |
| versao_tiss            | varchar |    Versão do padrão TISS que a operadora usa       |                 |
| particular               | boolean | Indica se é particular                    |                 |
| cortesia     | boolean   | Indica se é cortesia                                  |                 |



  