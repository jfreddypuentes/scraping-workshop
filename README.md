# 🕷️ Web Scraping Workshop 🕷️
Web Scraping de Wikipedia, Leer contenido de archivos txt dentro de un .zip, Python

### 👀 Sobre esto

- El archivo permite manipular archivos .zip desde Python
- Permite hacer web scraping de una web donde toma una serie de nombres de los mejores programadores a 2020, construye url de wikipedia con dichos nombres y vuelve a hacer web scraping en cada página de cada programador.

#### 🤖 Funciones interesantes:

- **unzip_file(zip_file, target_folder)** => Descomprime el cotenido de [zip_file] en la carpeta [target_folder] Devuelve la ruta final del contenido.

- **get_file_names_in_path(path)** => Devuelve una lista con los nombres de archivos en la ruta [path]

- **read_file_and_count_words(file_list)** => Devuelve una lista ordeneda de tuplas con el nombre del archivo y la cantidad de palabras que contiene. Lee los datos de un listado de archivos que es pasado como parámetro [file_list].

- **get_soup(link)** => Hacer petición GET a una URL dada y devuelve el html como objeto soup.

- **call_wiki(link)** => Obtiene e imprime los datos de interes que se encuentran en la etiquetas de la pagina descargada.

- **build_link_to_scraping(main_link, base_url_wiki)** => Esta función hace scraping de una pagina que contiene datos de personas. Con esos datos construye un listado de links a los que nuevamente puede hacer scrapy.
