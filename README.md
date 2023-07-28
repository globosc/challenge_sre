![Banner](https://github.com/globosc/challenge_sre/assets/71105387/71093d0b-a910-4cd8-9267-1bf9c11b42b7)


# Objetivo
El objetivo del presente reositorio es cumplir con el challenge planteado.

# Desafio 
 
Link del repositorio: <https://github.com/globosc/challenge_sre>

Link DockerHub: <https://hub.docker.com/repository/docker/globoscx/sre-challenge/general>


### Instrucciones

El desafío puede ser validado de 2 maneras:
- Clonando el Repositorio
- Utilizando la imagen en DockerHub

#### Validación desde el Repositorio

1. Clonar: `git clone https://github.com/globosc/challenge_sre.git`
2. Build: `docker build -t web .`
3. Ejecutar Contaniner: `docker run -d -p 8080:80 web`
4. Abrir un Browser y acceder a: <http://localhost:8080/>
5. Testing al texto cifrado: `curl -sL http://localhost:8080 |base64 -d`

#### Validación desde DockerHub

1. Recall a la imagen: `docker pull globoscx/sre-challenge:latest`
2. Ejecutar Contaniner: `docker run -d -p 8080:80 globoscx/sre-challenge`
3. Abrir un Browser y acceder a: <http://localhost:8080/>
4. Testing al texto cifrado: `curl -sL http://localhost:8080 |base64 -d`
















