# Serviços
<p align="justify"> 
Este documento descreve os campos necessários para importar os dados de serviços ou procedimentos ofertados pela clínica no sistema Ebrain. A tabela de descrição dos campos abrange as principais informações destes serviços médicos.
 </p>

 ## Descrição dos campos

| Campo                       | Tipo      | Descrição                                                                  | Restrição       |
|-----------------------------|-----------|----------------------------------------------------------------------------|-----------------|
| unique_cod                 | varchar     | Código único do serviço                       |     Obrigatório            |
| nome               | varchar | Nome do serviço                                      |   Obrigatório              |
| data_inicio          | timestamp     | Data do ínicio deste serviço                   |   Obrigatório              |
| data_importacao    | timestamp     | Data que ocorreu a importação     |                 |
| data_fim | Timestamp     |   Data que o serviço parou de ser realizado        |                 |
| agendavel            | boolean |   Indica se é agendavel      |                 |
| agendavel_via_app               | boolean | Indica se é agendável via app                 |                 |
| gratuito     | boolean   | Indica se é um serviço gratuito                                  |                 |
| atende_particular     | boolean   | Indica se aceita atendimento particular                                  |                 |
| atende_convenio     | boolean   | Indica se aceita convênio médico                                 |                 |
| especialidade_id     | boolean   | Especialidade do serviço                                 |                 |
| valor_particular     |  decimal(10, 2)   | Valor do serviço particular                           |                 |


## Arquivo
<p align="justify">Realize o dowload do arquivo de exemplo abaixo:</p>

[Clique aqui para baixar o arquivo csv](https://drive.google.com/uc?export=download&id=1_lWIyxqXTPap8pkN9fLN3vcohTemex6V)
