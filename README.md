<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Minha Página Pessoal</title>
    <link rel="stylesheet" href="estilo.css">
</head>
<body>

    <h1>Felipe Matheus Mesquita da Silva</h1>
    
    <p>Olá! Meu nome é Felipe Matheus Mesquita, tenho 27 anos e moro em Santa Luzia. Sou apaixonado por tecnologia, games e tudo que envolve criatividade e inovação. Gosto de aprender coisas novas e sempre busco desafios que me façam crescer pessoal e profissionalmente.</p>

    <h2>Mensagem do Dia</h2>
    <button id="messageButton">Clique para ver uma mensagem</button>
    <p id="dynamicMessage"></p>

    <h2>Meus Hobbies e Interesses</h2>
    <ul>
        <li>Assistir filmes e séries</li>
        <li>Praticar esportes ao ar livre (ex: ciclismo, caminhada)</li>
        <li>Cozinhar e experimentar novas receitas</li>
    </ul>

    <h2>Um dos Meus Hobbies Favoritos</h2>
    <img src="https://tse3.mm.bing.net/th/id/OIP.TXnZQdPIiNhr79qkXN7AagHaEK?r=0&rs=1&pid=ImgDetMain&o=7&rm=3" alt="Ciclistas pedalando em uma paisagem bonita">
    <p>Adoro pedalar e explorar novos lugares!</p>

    <h2>Países Que Gostaria de Visitar</h2>
    <table border="1">
        <thead>
            <tr>
                <th>País</th>
                <th>Imagem</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>EUA</td>
                <td><img src="https://tse2.mm.bing.net/th/id/OIP.4JBWZnFKF97YQ0OYRJn8NQHaEJ?r=0&rs=1&pid=ImgDetMain&o=7&rm=3" alt="Estátua da Liberdade e paisagem dos EUA"></td>
            </tr>
            <tr>
                <td>Itália</td>
                <td><img src="https://cdn.americachip.com/wp-content/uploads/2022/12/Italia.png" alt="Bandeira ou paisagem da Itália"></td>
            </tr>
            <tr>
                <td>Canadá</td>
                <td><img src="https://th.bing.com/th/id/R.60a954551840e3069c2dffbdf0cdab25?rik=nwla4jcLPQxSoA&riu=http%3a%2f%2fbucketlistlists.com%2fwp-content%2fuploads%2f2021%2f06%2fcanada-bucket-list-10.jpg%3fis-pending-load%3d1&ehk=ol2%2fgmEU%2bhFL9QIJ6U8hWzOsVJ%2bjEHB99bzlyX5r1gY%3d&risl=&pid=ImgRaw&r=0" alt="Bandeira ou paisagem do Canadá"></td>
            </tr>
        </tbody>
    </table>
    <p>Tenho muita vontade de conhecer esses lugares e suas culturas!</p>

    <h2>Site de Interesse</h2>
    <p>Confira meu site favorito sobre tecnologia: <a href="https://www.tecmundo.com.br" target="_blank">TecMundo</a></p>

    <script>
        document.getElementById('messageButton').addEventListener('click', function() {
            const messages = [
                "Bem-vindo(a) à minha página! Espero que goste.",
                "Seja a mudança que você quer ver no mundo.",
                "O sucesso é a soma de pequenos esforços repetidos dia após dia.",
                "Nunca pare de aprender, porque a vida nunca para de ensinar."
            ];
            const randomIndex = Math.floor(Math.random() * messages.length);
            document.getElementById('dynamicMessage').innerText = messages[randomIndex];
        });
    </script>

</body>
</html>
