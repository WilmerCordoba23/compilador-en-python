# Compilador de Texto a Binario

Este es un simple compilador de texto a binario que permite a los usuarios convertir texto en lenguaje natural en representaciones binarias. La herramienta utiliza un diccionario para mapear letras del alfabeto a sus representaciones binarias correspondientes.

## Funcionalidades

1. **Entrada de Texto:** El usuario puede ingresar texto en lenguaje natural.
2. **Validación de Entrada:** El programa verifica que el texto solo contenga letras y espacios en blanco, generando un mensaje de error en caso contrario.
3. **Normalización del Texto:** Se realiza la normalización del texto, convirtiendo caracteres con acentos o diacríticos en caracteres sin acentos.
4. **Conversión a Minúsculas:** El texto se convierte a minúsculas para asegurar que las letras sean reconocidas en el diccionario de mapeo.
5. **Mapeo a Binario:** Se utiliza un diccionario predefinido para mapear las letras a sus representaciones binarias.
6. **Compilación a Binario:** El código binario se compila a partir del texto en lenguaje natural.
7. **Visualización del Resultado:** El código binario resultante se muestra en un formato legible en binario.

## Uso

### Requisitos
- Python 3.x
- Bibliotecas estándar de Python: re, binascii, struct, unicodedata

### Instrucciones
1. Ejecute el programa en un entorno que admita Python 3.x, como Jupyter Notebook.
2. Siga las instrucciones para ingresar el texto en lenguaje natural.
3. El programa generará y mostrará el código binario resultante.

## Ejemplo

Si se ingresa "Hola Mundo", el programa generará y mostrará el código binario correspondiente a las letras "hola mundo".

**Nota:** Este programa asume que se está trabajando con texto en idioma español y no maneja caracteres especiales, números u otros idiomas.

## Autor

- Wilmer Alexander Córdoba Arroyo
- Yoni Mosquera Mosquera