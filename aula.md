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

Palavra chave da primeira aula é: MARVEL

# Segunda aula: Aprenda CI(Continuous Integration(Integração Contínua))/CD na prática: automatize do build ao deploy
Palavras "chaves": YML/YAML,  
## Primeiro:
