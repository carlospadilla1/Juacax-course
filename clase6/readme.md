## Creación de clases para Tailwind

Con las clases no repetimos código, y respetamos el principio dry. 
don't repeat yourself

-

crear clase en css o crear la etiqueta style en el head seguido del nombre y asignar la palabra reservada @apply para que sean aplicables a los elementos correspondientes.

ejemplo:

.h1Custom{
    @apply  text-4xl font-bold;
}

luego colocamos la clase guardada en una etiqueta html.