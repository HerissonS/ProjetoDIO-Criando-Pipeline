# PROJETO DIO
## Criando Pipeline de CI/CD com Cloud Build e Terraform

Foi criada uma pipeline com Cloud Build na GCP, essa pipeline cria uma instancia com terraform.

Foi criado um gatilho e conectada a pipeline com um repositório no github, ao ser executado um push para o repositório, automaticamente a pipeline é executada.

Foi criado também um bucket para armazenar o estado do terraform.