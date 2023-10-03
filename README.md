<!-- Título -->
Olá, eu sou o roberirobson 👋
<!-- Subtítulo -->
Sobre mim
gosto do ramo de informatica e estudo no estudo federal baiano eu me enteressei por esse curso e quis aproveitar a chance q eu conseguir para estudar nesse ramo

<!-- Ícones de Redes Sociais -->
Redes Sociais
[![GitHub](https://img.shields.io/badge/GitHub-roberiorobson-purple)](https://github.com/roberiorobson)
[![LinkedIn](https://img.shields.io/badge/Instagram-___5JUNIOR5___-blue)](https://www.linkedin.com/in/roberiorobson)
[![Twitter](https://img.shields.io/badge/Twitter-nenhum-white)](https://twitter.com/roberiorobson)

<!-- Linguagens -->
!html e css

<!-- Footer -->
<hr>
<p align="center">
  Feito com ❤️ por roberiorobson
</p>

<!DOCTYPE html>
<html>
<head>
    <title>20:49</title>
    <script>
        function mostrarDataHora() {
            var dataHoraAtual = new Date();
            var data = dataHoraAtual.toLocaleDateString();
            var hora = dataHoraAtual.toLocaleTimeString();
            document.getElementById("data-hora").innerHTML = "Data: " + data + "<br>Hora: " + hora;
        }

        // Chama a função inicialmente e, em seguida, a atualiza a cada segundo
        mostrarDataHora();
        setInterval(mostrarDataHora, 1000);
    </script>
</head>
<body>
    <div id="data-hora"></div>
</body>
</html>
