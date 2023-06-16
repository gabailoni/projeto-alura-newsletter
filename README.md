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
  https://tailwindcss.com/docs/display
  https://tailwindcss.com/docs/position
  https://tailwindcss.com/docs/gap
  https://tailwindcss.com/docs/padding
  https://tailwindcss.com/docs/margin
  https://tailwindcss.com/docs/width
  https://tailwindcss.com/docs/height
  https://tailwindcss.com/docs/border-radius
  https://tailwindcss.com/docs/box-shadow
  https://tailwindcss.com/docs/animation
  https://tailwindcss.com/docs/transition-duration
  https://tailwindcss.com/docs/fill
  https://tailwindcss.com/docs/stroke

