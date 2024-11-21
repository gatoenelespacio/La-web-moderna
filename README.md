# web moderna 

## Autor:
Nombre: Jose Antonio Macedo 
Avila 

Nombre del curso: 201 

Email: asentryx@gmail.com

fecha de creacion: 20/11/24

## Sobre el proyecto: 
En “La Web Moderna” podrás leer los conceptos clave que todo Desarrollador de Software debe saber para crear aplicaciones web.

## eslintrc 

1. env: Define los entornos en los que el código se ejecuta.

"browser": true: El código está destinado a ejecutarse en un navegador, habilitando variables globales como window y document.
"es2021": true: El código usa características de ECMAScript 2021 (ES12), como async/await y otras mejoras.
2. extends: Usa la configuración base eslint:recommended, que incluye reglas básicas para evitar errores comunes.

3. parserOptions: Configura el analizador (parser) de ESLint.

  - "ecmaVersion": "latest": Permite la última versión de ECMAScript.
   - "sourceType": "module": Indica que se usan módulos ECMAScript (import/export).
4. rules: Define reglas específicas de estilo y calidad de código.

- "indent": ["error", 2]: Usa 2 espacios para la indentación.
- "linebreak-style": ["error", "unix"]: Usa saltos de línea estilo Unix (\n).
- "quotes": ["error", "single"]: Usa comillas simples (') para las cadenas.
- "semi": ["error", "always"]: Exige punto y coma al final de las instrucciones.
- "no-unused-vars": "warn": Advierte sobre variables no utilizadas.
- "no-console": "warn": Advierte sobre el uso de console.log() u otros métodos de consola.

## Despliegue 
