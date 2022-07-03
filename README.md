# Proyecto-Arquitectura-de-computadoras
Algoritmo Otsu-Thresholding con diferentes implementaciones

Los archivos otsu.ipynb, otsu_statistics.ipynb y otsu_histograma.ipynb son las que se encargaran de procesar las imagenes para enviarlas a un cliente en la red local

# Implementación Multiprocessing
Realiza el histograma y la regeneracion de la imagen en forma serial y en paralelo, para esto la imagen se separa en 5 partes

# Implementación statisctics
Se utilizan las funciones statistics.mean() y statistics.variance()

# Implementación Multiprocessing
Se utiliza la función cv2.calcHist()

# Otsu client
Es un cliente, el cual se encuentra en la red local del server. El cliente enviará una imagen al server para que la imagem sea procesada, posteriormente el server enviará la imagen procesada al cliente.

# Procesamiento de las imagenes

## Imagenes de prueba
![perro](https://user-images.githubusercontent.com/102978460/177020563-e91fa346-8126-4cbc-9927-727e5c71167f.jpg)
![prueba](https://user-images.githubusercontent.com/102978460/177020585-feaf82f1-791a-43df-a6fc-6812957eea17.jpg)
![prueba](https://user-images.githubusercontent.com/102978460/177020568-f8986ef8-7fe0-410c-b319-e6f3a573691d.jpg)

## Imagenes procesadas
![prueba_otsu](https://user-images.githubusercontent.com/102978460/177020604-b615864b-a0b2-4ebd-be4c-7385f821e296.jpg)
![prueba_otsu](https://user-images.githubusercontent.com/102978460/177020593-c179fbe9-4946-4cb2-8aac-3cddd4669c15.jpg)
![prueba_otsu](https://user-images.githubusercontent.com/102978460/177020618-0bed903a-f01f-4e3f-8caa-f36eb5f054c4.jpg)

# Información del proceso en los servers
## Otsu base
![otsu_simple](https://user-images.githubusercontent.com/102978460/177023180-080199be-f483-41ad-8c1c-a9d03c6f5fd4.jpg)
## Otsu socket
![otsu_htop](https://user-images.githubusercontent.com/102978460/177022680-370b772c-886b-4990-b93b-788048ff4b31.jpg)
## Otsu_statistics
![otsu_statis_htop](https://user-images.githubusercontent.com/102978460/177022788-f2424ed3-fcbf-4c18-b59c-cc30b2f54f32.jpg)
## Otsu_histograma
![otsu_hist_htop](https://user-images.githubusercontent.com/102978460/177022889-015b43ad-0502-4f17-a452-134fe6e52ba9.jpeg)
## Otsu Multiprocessing
![otsu_multiproc](https://user-images.githubusercontent.com/102978460/177023440-97030515-69de-4143-9f53-cb0e957bca25.jpg)
