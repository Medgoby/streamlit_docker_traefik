# streamlit docker and traefik

Applicatif qui permet d'approuver ou de rejetter une demande de credit

Streamlit : framework python 

#### creation d'une application web pour appouver ou rejeter une demande de crédit

### Applicatif
app:
    * applicatif streamlit ==>app.py
    * modeles ===> pickle
    * notebook jupyter

### Docker
 docker :
    * streamlit
        * Dockerfile
    * traefik :
        * Dockerfile
    
docker-compose up -d --build

docker-compose up -d --build
docker container run -p 8501:8501 -d streamlitapp

