## Primer contenedor 

Es el código muestra utilizando para el tutorial 
**Docker la mejor explicación**
explicado en el siguiente link 
https://www.youtube.com/watch?v=n8R2LxdbtXQ

### Instrucciones 

```
# Crear la imagen 
docker build -t nginx_img . 

# Ejecutar la computadora
docker run -it -p 80:80 nginx_img 

```