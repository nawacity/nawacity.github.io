# Tu propia documentacion! 
Vamos a salirnos de la tematica principal de la documentacion y te voy a compartir como armar tu propia documentacion! (Tambien me sirve escribirlo por si me olvido en el futuro xd).
Por el momento no voy a escribir para los noobies, eso en algun momento lo voy a agregar. 

## Requisitos.
- Saber como funciona git.
- Tener cuenta en github. 
- Entender sobre github actions.
- Experiencia previa con levantar mkdos localmente con docker o docker compose. 

## 1. Directorio. 

Si revisan el repositorio de esta pagina se van a encontrar con una estructura similar a esta: 

```
tu-repositorio/
├── docs/
│   ├── index.md
│   └── ... (otros archivos .md)
├── mkdocs.yml
└── .github/workflows/deploy.yml
```

A ver, tenes tu repo principal, tenes un mkdocs.yml que es un archivo que estructura la configuracion del servicio mkdocs, de como se va a ver y comportar. Tenes el folder docs que va a ser el contenido de la pagina. Y vas a tener el deploy de github actions, que se va a ejecutar cada vez que hagas un push al repo. 

{% include '../mkdocs.yml' %}

