# Aplicación Fitness V1 (archivo)

> **Proyecto archivado.** Era la primera demo en **HTML/CSS/JavaScript puro**.  
> La versión actual para portafolio es **[aplicacionfitness-angular](https://github.com/juancasano/aplicacionfitness-angular)** (Angular + TypeScript, v1–v9).

---

Ejemplo didáctico de una app web CRUD modular (ejercicios, entrenamientos y usuarios) con documentación separada del código.

## Demo (histórica)

- [App de ejercicios (GitHub Pages)](https://juancasano.github.io/aplicacionfitnessV1/app/exercises.html)
- [Versión actual en Angular](https://github.com/juancasano/aplicacionfitness-angular)

## Estructura

```
aplicacionfitnessV1/
├── README.md
├── spec.md
├── docs/          # arquitectura, BD, módulos
├── app/           # HTML/CSS/JS
├── data/          # CSV de muestra
└── sql/           # esquema de ejemplo
```

## Uso local

1. Clona el repositorio.
2. Copia `app/js/config.example.js` a `app/js/config.js` y pon tus claves de Supabase (no se versiona).
3. En las páginas HTML, cambia `config.example.js` por `config.js` si usas claves locales.
4. Abre `app/exercises.html`, `app/users.html` o `app/workouts.html`.

> En GitHub Pages carga `config.example.js` (sin claves reales).
