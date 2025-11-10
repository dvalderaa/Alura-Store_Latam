
# Proyecto Alura Store_Latam que forma parte del Challenge 1 del curso de especialización para Data Science de Alura.

Este proyecto realiza un análisis exploratorio y visualización de datos de ventas usando pandas y matplotlib en Google Colab.

## Instalación

Clona este repositorio:

git clone https://github.com/dvalderaa/Alura-Store_Latam.git

Instala las dependencias necesarias:

!pip install pandas matplotlib

## Uso

Las bases de datos están cargadas en Github:

url = "https://raw.githubusercontent.com/alura-es-cursos/challenge1-data-science-latam/refs/heads/main/base-de-datos-challenge1-latam/tienda_1%20.csv"
url2 = "https://raw.githubusercontent.com/alura-es-cursos/challenge1-data-science-latam/refs/heads/main/base-de-datos-challenge1-latam/tienda_2.csv"
url3 = "https://raw.githubusercontent.com/alura-es-cursos/challenge1-data-science-latam/refs/heads/main/base-de-datos-challenge1-latam/tienda_3.csv"
url4 = "https://raw.githubusercontent.com/alura-es-cursos/challenge1-data-science-latam/refs/heads/main/base-de-datos-challenge1-latam/tienda_4.csv"

tienda = pd.read_csv(url)
tienda2 = pd.read_csv(url2)
tienda3 = pd.read_csv(url3)
tienda4 = pd.read_csv(url4)

El programa generará diferentes gráficos (barras, circulares, etc.) y mostrará estadísticas generales del desempeño general de cada tienda analizada.

## Resultados

Se dará una recomendación sobre qué tienda obtuvo mejor desempeño y resultado, de igual forma qué tienda obtuvo el peor resultado. De acuerdo a ello, se recomendará el cierre de la tienda correspondiente.

## Posibles problemas

Verifica los separadores de los archivos csv. En este caso se encuentran como comas ",".

Si los gráficos no se muestran automáticamente, utiliza plt.show() al final del script.