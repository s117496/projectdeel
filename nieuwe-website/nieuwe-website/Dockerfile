# Gebruik een kleine en snelle webserver image (nginx)
FROM nginx:alpine

# Verwijder standaard NGINX bestanden
RUN rm -rf /usr/share/nginx/html/*

# Kopieer de inhoud van de public map (inclusief index.html) naar de juiste NGINX directory
COPY public/ /usr/share/nginx/html/

# Zorg dat NGINX op poort 80 draait (standaard)
EXPOSE 80
