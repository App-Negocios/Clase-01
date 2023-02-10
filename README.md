# Componente

Se trata de una directiva o elemento que puede ser reutilizado. Es un elemento que compone a un todo y que esta compuesto.

## Elementos de un componente

1. Template, en este caso fue el "app.component.html".
2. Archivo lógico, en este caso se trata de "app.component.ts".
3. Un archivo de estilos CSS
PUEDE TENER MÁS ARCHIVOS DEPENDIENDO DE LAS NECESIDADES DEL PROYECTO.

## Módulo

Se trata de un contenedor de código dedicado a una aplicación o para cierta funcionalidad. Se define mediante una clase de @NgModule.

## Función de Patrón de diseño decorator

Nos permite componer nuevos objetos a partir de objetos ya existentes sin utilizar directamente la herencia. podremos añadir dinámicamente funcionalidades a un objeto, constituyendo una alternativa a la herencia de clases.

## Menciona y describe los elementos importantes de un @NgModule

NgModulees un decorador que recibe un objeto de metadatos que definen el módulo (al final del artículo tienes más detalles sobre los metadatos. Los metadatos más importantes de un NgModule son:

1. Declarations: Las vistas que pertenecen a tu módulo. Hay 3 tipos de clases de tipo vista: componentes, directivas y pipes.
2. exports: Conjunto de declaraciones que deben ser accesibles para templates de componentes de otros módulos.
3. Imports: Otros NgModules, cuyas clases exportadas son requeridas por templates de componentes de este módulo.
4. Providers: Los servicios que necesita este módulo, y que estarán disponibles para toda la aplicación.
5. Bootstrap: Define la vista raíz. Utilizado solo por el root module.
