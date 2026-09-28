# lisan1313.github.io

Sitio raíz de GitHub Pages. Existe para una cosa concreta: servir el archivo
**`app-ads.txt`** en la raíz del dominio (`https://lisan1313.github.io/app-ads.txt`),
que es donde AdMob lo busca.

## Por qué hace falta un repositorio aparte

GitHub Pages solo sirve la raíz del dominio desde un repositorio que se llame
exactamente igual que el usuario (`lisan1313.github.io`). El repositorio de la
política de privacidad (`botonrandom-privacy`) se sirve en una subcarpeta
(`lisan1313.github.io/botonrandom-privacy/`), y ahí AdMob no mira.

## Qué es app-ads.txt

Declara qué vendedores están autorizados a vender el espacio publicitario de
las apps. Sin él, algunos compradores pujan menos o no pujan, porque no pueden
confirmar que quien vende es el dueño legítimo. No es obligatorio, pero sin él
se cobra menos.

Para que funcione, la ficha de la app en Google Play tiene que declarar
`https://lisan1313.github.io` como **sitio web del desarrollador**: ese enlace
es el que AdMob sigue para encontrar el archivo.

## Si se añaden más apps

El archivo es por **cuenta de editor**, no por app. La línea de
`pub-7422167007141688` ya cubre todas las apps de esa cuenta de AdMob: no hay
que añadir una línea por cada app nueva.
