# tree-sitter-wasm-typescript-bindings

TypeScript declarations (.d.ts) for Tree-sitter WebAssembly module compiled with Emscripten. Automatic bindings to use the parser in browser/Node.js.

## ¿Qué es?

Bindings de bajo nivel para interactuar con el core de Tree-sitter en WebAssembly.

**Nota importante:** Para la mayoría de los casos, usa el paquete oficial [`web-tree-sitter`](https://www.npmjs.com/package/web-tree-sitter). Trae tipos más amigables, mejor documentación y ya está listo para usar en proyectos reales.

Este repo es útil si estás compilando tu propio Tree-sitter WASM custom o necesitas los bindings crudos autogenerados por Emscripten.

## Instalación

Si publicas este paquete en npm (recomendado), instala así:

```bash
npm install @cerdaqu/tree-sitter-wasm-typescript-bindings
# o si no lo publicaste aún: npm install github:cerdaqu/tree-sitter-wasm-typescript-bindings
