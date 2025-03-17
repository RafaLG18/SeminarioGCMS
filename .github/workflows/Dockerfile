# Usar uma imagem leve do Nginx como base
FROM nginx:alpine

# Copiar o arquivo HTML para o diretório de conteúdo do Nginx
COPY index.html /usr/share/nginx/html/index.html

# Expor a porta 80
EXPOSE 80

# Comando para iniciar o Nginx
CMD ["nginx", "-g", "daemon off;"]
