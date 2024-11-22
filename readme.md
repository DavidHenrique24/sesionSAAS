# Sass tutorial

1. Primero se pone el comando pa descargar sass: npm install -g sass en la terminal
2. Se crea el archivo style.scss y index 
3. escribimos el codigo del sass  en style
4. Compilamos sass a css con: "sass styles.scss styles.css" en la terminal
5. al hacer eso se crea automaticamente el archivo css y podemos continuar con el scss tranquilamente
6. Se pueden crear crear tus propias funciones en Sass para reutilizar lógica específica. Aquí tienes un ejemplo de cómo crear una función personalizada:
@function calcular-rem($pixels) {
  @return $pixels / 16 * 1rem;
}

.container {
  width: calcular-rem(320px);
  padding: calcular-rem(16px);
}

Basicamente  una herramienta poderosa para mejorar la productividad y la calidad del código CSS. Te permite escribir estilos más organizados, reutilizables y mantenibles. Con este ejemplo básico, ya tienes una idea de cómo comenzar a usar Sass en tus proyectos.
