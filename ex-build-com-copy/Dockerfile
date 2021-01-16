FROM nginx:latest
LABEL maintainer 'Aluno Cod3r.com.br -> Werner Luiz Gottschalt'

RUN echo '<h1>Sem Conteudo</h1>' > /usr/share/nginx/html/conteudo.html
COPY *.html /usr/share/nginx/html/
#Usamos o comando Copy para copiar os arquivos que estão dentro da mesma pasta do Dockerfile para a build da imagem.