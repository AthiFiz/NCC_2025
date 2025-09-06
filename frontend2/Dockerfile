FROM nginx:alpine
WORKDIR /usr/share/nginx/html

# Copy static files into nginx html dir
COPY . .

EXPOSE 80
CMD ["nginx", "-g", "daemon off;"]
