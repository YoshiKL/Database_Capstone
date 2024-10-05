# Base de Datos de Imágenes CXR para Detección de Tuberculosis

Este repositorio contiene una base de datos de **7000 imágenes de radiografías de tórax (CXR)** utilizada en el proyecto de investigación titulado **"PROTOTIPO DE APLICATIVO MÓVIL PARA LA DETECCIÓN DE TUBERCULOSIS MEDIANTE DEEP LEARNING UTILIZANDO RADIOGRAFÍAS DE TÓRAX"**.

## Descripción del Proyecto

Este proyecto tiene como objetivo desarrollar un prototipo de aplicación móvil para la **detección automática de tuberculosis** a través de radiografías de tórax utilizando técnicas avanzadas de **Deep Learning**. El propósito es ayudar en la identificación temprana de la tuberculosis, una enfermedad altamente infecciosa que afecta principalmente los pulmones, utilizando redes neuronales convolucionales (CNN) entrenadas en imágenes CXR.

### Componentes del Proyecto

- **Aplicación móvil**: Desarrollada para procesar imágenes de radiografías de tórax y realizar la predicción de posibles casos de tuberculosis.
- **Modelo de Deep Learning**: Implementado usando una red neuronal convolucional (CNN) entrenada en las imágenes de esta base de datos.
- **Base de datos CXR**: 7000 imágenes de radiografías de tórax clasificadas como saludables o con presencia de tuberculosis.

## Contenido del Repositorio

- **/DA_and_DB_278_imagenes_tuberculosis/**: Imágenes recopiladas de bases de datos DA y DB con un total de 278 imágenes.
- **/India_Database_TB_78_imagenes/**: Conjunto de 78 imágenes provenientes de bases de datos de India.
- **/montgomery_TB_58_imagenes/**: Imágenes de la base de datos Montgomery, con un total de 58 imágenes.
- **/NLM_TB_88_imagenes/**: Conjunto de 88 imágenes proporcionadas por NLM.
- **/Shenzhen_TB_336_imagenes/**: 336 imágenes recopiladas de Shenzhen.
- **/TB_Chest_Radiography_Database_2881_imagenes/**: Imágenes de la base de datos de radiografía torácica con un total de 2881 imágenes.
- **/TBX11K_3281_imagenes/**: Conjunto extenso de 3281 imágenes de la base de datos TBX11K.

## Uso de la Base de Datos

Las imágenes de CXR en este repositorio se utilizan para entrenar, validar y probar modelos de Deep Learning con el fin de detectar patrones asociados a la tuberculosis pulmonar. Las imágenes están clasificadas y preparadas para ser procesadas directamente en modelos de aprendizaje automático.

### Ejemplo de uso

1. Clonar el repositorio:
    ```bash
    git clone https://github.com/YoshiKL/Database_Capstone.git
    ```

2. Cargar las imágenes en el entorno de trabajo o en la aplicación móvil para el preprocesamiento y la inferencia del modelo.

## Requisitos

- **Git LFS (Large File Storage)**: Dado que las imágenes superan el límite de tamaño de archivos de GitHub, Git LFS es necesario para gestionar los archivos grandes.

### Instalación de Git LFS:

```bash
git lfs install
