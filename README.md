# Cafetería Agere (HTML y SASS)

## Tabla de Contenidos

- [Descripción](#descripción)
- [Estructura de Archivos](#estructura-de-archivos)
- [Tecnologías Utilizadas](#tecnologías-utilizadas)
- [Instalación](#instalación)
- [Autores](#autores)

## Descripción

Este es un proyecto de Homepage para la cafetería Agere, utilizando HTML y SASS, fue organizada siguiendo el método 7-1 para una mejor gestión y mantenimiento del código CSS.

[Revisa el resultado final aqui](https://vickyazola.github.io/HomepageCafeteria-DesafioLatam/)

![mockup_cafe-agere](https://github.com/VickyAzola/HomepageCafeteria-DesafioLatam/assets/116470398/6dbfac42-3944-4a4e-ba24-54133602e47b)


## Estructura de Archivos

```plaintext
HomepageCafeteria-DesafioLatam/
├── assets/
│   ├── css/
│   │   └── main.css
│   │
│   ├── img/
│   │   ├── logo.png
│   │   ├── img-1.png
│   │   ├── img-2.png
│   │   ├── img-3.png
│   │   └── img-4.png
│   │    
│   └── sass/
│       ├── abstracts/
│       │   ├── _mixins.scss
│       │   └── _variables.scss
│       │ 
│       ├── base/
│       │   ├── _reset.scss
│       │   └── _typography.scss
│       │ 
│       ├── components/
│       │   ├── _box.scss
│       │   ├── _buttons.scss
│       │   ├── _coffee.scss
│       │   ├── _link.scss
│       │   ├── _map.scss
│       │   ├── _nav.scss
│       │   ├── _stats.scss
│       │   └── _textBlock.scss
│       │ 
│       ├── layout/
│       │   ├── _navbar.scss
│       │   └── _section.scss
│       │ 
│       ├── pages/
│       ├── themes/
│       ├── vendors/
│       └── main.scss
│
├── index.html
└── README.md
```

## Tecnologías Utilizadas

- **HTML5**: Para la estructura del sitio web.
- **SASS**: Para el diseño y la presentación del sitio web. Los archivos SASS están organizados siguiendo la metodología 7-1 para mantener el código modular y fácil de mantener.
- **Google Fonts**: Biblioteca de fuentes de texto. Se utilizaron:
  - [PT Mono](https://fonts.google.com/specimen/PT+Mono?query=pt+mono)
  - [Roboto - regular](https://fonts.google.com/specimen/Roboto?query=roboto)

## Instalación

1. **Clonar el repositorio**:
   
    ```bash
    git clone git@github.com:VickyAzola/HomepageCafeteria-DesafioLatam.git
    ```
    
2. **Navega al directorio del proyecto**
   
    ```bash
    cd HomepageCafeteria-DesafioLatam
    ```
    
3. **Instala las dependencias:**

    Este proyecto asume que tienes Sass instalado globalmente. Si no lo tienes, puedes instalarlo con:

    ```bash
    npm install -g sass
    ```

4. **Compila los archivos Sass:**

    Navega al directorio raíz del proyecto y ejecuta el siguiente comando para compilar los archivos Sass:

    ```bash
    sass assets/sass/main.scss assets/css/main.css
   
6. Abrir `index.html` en tu navegadorpara ver el sitio web.

## Autores

- **Desarrollador Principal**: [Victoria Azola Silva](https://github.com/VickyAzola) - Responsable del desarrollo del código.
- **Diseñador**: [Desafío Latam](https://desafiolatam.com/admision/?utm_term=desafio%20latam&utm_campaign=Brand&utm_source=adwords&utm_medium=ppc&hsa_acc=1239562006&hsa_cam=16998643182&hsa_grp=136655824715&hsa_ad=596057942540&hsa_src=g&hsa_tgt=kwd-340546658839&hsa_kw=desafio%20latam&hsa_mt=b&hsa_net=adwords&hsa_ver=3&gad_source=1&gclid=CjwKCAjwvvmzBhA2EiwAtHVrbzEJGJPqUuTuFDuNIFtSh4eKqGXcLXmCO9u12vwlU553fGXV93Q5zxoCGmEQAvD_BwE) - Responsable del diseño gráfico y visual del proyecto.
