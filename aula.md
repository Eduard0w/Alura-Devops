# alura Devops

# Primeira aula: Crie ambientes reais com Docker e dê fim ao "na minha máquina funciona"
## Primeiro:
- Crie um Dockerfile
  - Configure-o de acordo com seu projeto
  - Caso necessário (Vai ser) vá para esse site -> [DockerHub](https://hub.docker.com)
  - É bom criar um .dockerignore (que funciona da mesma maneira de um 
  .gitignore).

## Segundo:
- Comandos no terminal para criar uma imagem docker
  - "docker build -t >nome da imagem<"
  - para ver as imagens criadas via terminal é só escrever o comando "docker images". Porém tem como ver pelo próprio "app" docker que pode ser instalado por esse site [Docker](https://www.docker.com).
- Para rodar a aplicação pode ser feito tanto pelo "app" docker quanto pelo terminal.
  - No terminal usamos: docker run -p 8000:8000 >nome da imagem<
  - também tem dessa forma docker run -d -p 8000:8000 >nome da imagem<

Palavra chave da primeira aula é: Marvel

# Segunda aula: Aprenda CI(Continuous Integration(Integração Contínua))/CD na prática: automatize do build ao deploy
Palavras interessantes para entender: YML/YAML 
## Primeiro:
- Criação do "docker-compose.yml" arquivo que facilita a inicialização da imagem criada.
  - Docker-compose.yml a principio facilita a maneira de dar run na imagem criada.
  - antes você precisava fazer um processo maior, agora com esse novo arquivo com apenas "docker compose up" já faz a aplicação rodar.

## Segundo:
- Após mandar para o seu repositorio vamos acrscentar pelo action do github um workflow, para facilitar as novas criações de imagens com CI.
  - Esse workflow "automatiza" a criação de novas imagens com a adição das novas atualizações do software.

Palavra chave da segunda aula é: Ellis


# Terceira aula: Fazendo o deploy na Google Cloud Plataform
- Baixar CLI gcloud no seu computador
  - fazer login com seu email, escolher seu projeto criado no google cloud(que por sinal é pago😢😢) e posta-lo. 
  - aceitar um monte de coisas.
  - escolher o servidor correto (no caso no brasil, tem um em sao paulo - (32)southamerica-east1).

Palavra chave da terceira aula é: YAML