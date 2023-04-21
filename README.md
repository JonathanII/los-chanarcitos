## Web "Los Chañarcitos"

### La pagina esta siendo desarrollada con HTML5, CSS3 y Bootstrap.

Acá te explico algunas cosas sobre las medidas que estoy utilizando:

- Los contenedores como Header  tiene una _class_ **px-4**  para sus laterales y Main tiene una _class_ en sus 4 lados de **p-4**

  - Esta tabla sirve tanto para padding como para margin

  ```scss
  $spacer: 1rem;
  $spacers: (
    0: 0,
    1: $spacer * .25,
    2: $spacer * .5,
    3: $spacer,
    4: $spacer * 1.5,
    5: $spacer * 3,
  );
  ```

  *Vale aclarar que 1 rem equivale a 16px*

- Dentro de los contenedores tenemos  _nav_ y _section_ tienen una _class_ __"container-fluid"__ y __"mx-5"__.

  