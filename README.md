# Em-buscado-tesouro
Em busca do tesouro
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Bai+Jamjuree:ital,wght@0,200;0,300;0,400;0,500;0,600;0,700;1,200;1,300;1,400;1,500;1,600;1,700&display=swap" rel="stylesheet">
    <title>Em busca do tesouro</title>
</head>
<body>
    <main>
        <div class="passo ativo" id="passo-0">
            <img src="cenario-passo0.jpg" alt="">
            <p>Um dia desses estava em minha casa conversando com meu amigo, já que meu aniversário está chegando, ele resolveu que iria me ajudar buscar um tesouro, e então começamos a discutir sobre como iamos achar, como já estava anoitecendo decidimos que esse seria o nosso plano para a semana</p>
            <button class="btn-proximo" data-proxima="1">Buscar Tesouro</button>
            <button class="btn-proximo" data-proxima="2">Buscar Tesouro mais perto</button>
        </div>
        <div class="passo" id="passo-1">
            <p>Começa a jornada na internet para pesquisar sobre historias na regiao, o qual nos agradou muito</p>
            <button class="btn-proximo" data-proxima="3"> procurar o melhro tesouro de todos</button>
            <button class="btn-proximo" data-proxima="4">ir nele por ser mais perto</button>
        </div>
        <div class="passo" id="passo-2">
         <p>Na spesquisas para o encontrar o tesouro perfeito, identificamos que agrada muito a nos dois, no entanto ele estaria em uma cidade um pouco mais longe.</p>
         <button class="btn-proximo" data-proxima="3"> procurar melhor tesouro</button>
         <button class="btn-proximo" data-proxima="4">ir nele por ser mais legal</button>
        </div>
    </main>
    <script src="script.js"></script>

</body>
</html>
