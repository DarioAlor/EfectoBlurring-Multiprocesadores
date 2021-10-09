# Efecto Blurring-Multiprocesadores
## Instrucciones
Desarrollar un programa que realice el efecto de desenfoque sobre una imagen de gran pixelaje (mayor a 2000 pixeles ya sea en alto o ancho de la imagen). Determine la dimensión mínima de la mascara para observar el efecto de desenfoque y el número de threads óptimo para desarrollar este proceso en el menor tiempo posible.
## Resultados
### Threads óptimos
![imagen](https://user-images.githubusercontent.com/83479688/136637258-1d033995-17d9-4091-b116-20ba073960a4.png)
Como podemos observar en la imagen, el número óptimos de threads fue de 1. Al ir aumentando el número de threads nos damos cuenta que el tiempo va incrementando en aproximadamente 2 segundos por cada threads.
### Imagenes
Original
![imagen](https://user-images.githubusercontent.com/83479688/136637510-04ef85ff-219a-474c-b0ad-9d12be5e5f86.png)
Desenfocada
![imagen](https://user-images.githubusercontent.com/83479688/136637536-bcc1f490-6904-4a26-95b1-2d2c7d88cad6.png)
Original
![imagen](https://user-images.githubusercontent.com/83479688/136637837-851da389-c937-4a2b-a8b2-18bb076c2832.png)
Desenfocada
![imagen](https://user-images.githubusercontent.com/83479688/136637841-a449f69d-9092-4e4d-a998-afd6f5317772.png)
Original
![imagen](https://user-images.githubusercontent.com/83479688/136638464-324739c0-6e9b-48a2-a3f0-c17d34e05467.png)
Desenfocada
![imagen](https://user-images.githubusercontent.com/83479688/136638460-7725a76e-0dc7-4e9f-b4f9-381e1cc68eba.png)
Original
![imagen](https://user-images.githubusercontent.com/83479688/136637857-953ed81a-951a-43cd-9184-95b9565e2796.png)
Desenfocada
![imagen](https://user-images.githubusercontent.com/83479688/136637992-3d4047bc-f73f-4e3a-b041-29ad8a019c94.png)

En esta ocasión se usó una máscara de 9x9 y podemos observar que en la última imagen es en donde el blurring se aprecia de mejor manera, esto debido a que es la de menor pixelaje. Sin embargo, en las demás imágenes también podemos observar que se realiza un buen trabajo con el desenfoque.
