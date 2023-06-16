    Tailwind CSS

Bem vindo ao Projeto de Newsletter utilizando o Tailwind CSS, classes utilitárias dentro do HTML. Esse é um projeto desenvovido pela Alura, onde sou aluna, voltado para Front-end, trabalhando Frameworks para o dia a dia de um DEV.

    Inserindo o TailwindCSS no arquivo HTML:

<!doctype html>
<html>
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <script src="https://cdn.tailwindcss.com"></script>
</head>
<body>
  <h1 class="text-3xl font-bold underline">
    Hello world!
  </h1>
</body>
</html>

É importante ressaltar que deve ser inserido no head e após, devemos abrir um novo script para customizar cores, fontes, animações(...) que utilizaremos no projeto!

<script>
    tailwind.config = {
      theme: {
        extend: {
          colors: {
            clifford: '#da373d',
          }
        }
      }
    }
  </script>
  
    Links que valem leitura e aprofundamento:
  
  + https://tailwindcss.com/docs/configuration
  + https://tailwindcss.com/docs/theme
  + https://tailwindcss.com/docs/customizing-colors
  + https://tailwindcss.com/docs/box-sizing
  + tps://tailwindcss.com/docs/display
  + tps://tailwindcss.com/docs/position
  + tps://tailwindcss.com/docs/gap
  + tps://tailwindcss.com/docs/padding
  + tps://tailwindcss.com/docs/margin
  + tps://tailwindcss.com/docs/width
  + tps://tailwindcss.com/docs/height
  + tps://tailwindcss.com/docs/border-radius
  + tps://tailwindcss.com/docs/box-shadow
  + tps://tailwindcss.com/docs/animation
  + tps://tailwindcss.com/docs/transition-duration
  + tps://tailwindcss.com/docs/fill
  + tps://tailwindcss.com/docs/stroke

