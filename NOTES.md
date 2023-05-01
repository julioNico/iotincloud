# These are simple notes to remember during development.

- docker container ls (-a)
- docker image ls
- docker network ls
- docker run -it ubuntu
- every container has a entrypoint. Ex: in Ubuntu, is the bash.

## Container em execução:

    Como sair do container sem matá-lo?
    - docker run -it ubuntu
    - Ctrl+p+q

    Como acessar um container já em execução?
    - docker container attach "CONTAINER ID"

    Como executar um comando em um container que "Não tem shell (-it) ?"
    - utiliza o comando "exec".
    - docker container exec -ti "CONTAINER ID" "COMANDO"
    - docker container exec -ti fa89ef9887535 bash
