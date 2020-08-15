# outline
Outline - Selfhosted Notion alternative - guided docker installation

Features:

* A simple make and interactive bash script to help you generate all the conf required
* A docker-compose to run your service
* Dummy https certificate generator. Replace with your certificates after generation
* Use minio instead of AWS S3, so that everything is really self-hosted
* nginx reverse proxy for outline and minio

Runs the outline server with https if required

# How to use 

```
git clone https://github.com/chsasank/outline-wiki-docker-compose.git
cd outline-wiki-docker-compose
make install
```

Then you should follow intructions and fill the required values from your slack app and you server information 

