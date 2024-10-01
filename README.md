<!-- Código omitido… -->

<body>
    <header>
        <h1>Relatório das redes sociais</h1>
        <nav>
            <a href="index.html">Mundo</a>
            <a href="#">Minha escola</a>
        </nav>
    </header>
    <main class="graficos-section">
        <section id="graficos-container" class="graficos-container">
            <!-- crie os gráficos aqui -->
        </section>
    </main>
    <footer>
        <p>Desenvolvido por Gui Lima</p>
    </footer>
</body>
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Redes Sociais</title>
</head>
<body>

</body>
</html>
<body>
    <header>
        <h1>Relatório das redes sociais</h1>
        <nav>
            <a href="index.html">Mundo</a>
            <a href="#">Minha escola</a>
        </nav>
    </header>
    <main class="graficos-section">
        <section id="graficos-container" class="graficos-container">
            <!-- crie os gráficos aqui -->
        </section>
    </main>
    <footer>
        <p>Desenvolvido por Gui Lima</p>
    </footer>
</body>
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Redes Sociais</title>
</head>
<body>
    <header>
        <h1>Relatório das redes sociais</h1>
        <nav>
            <a href="index.html">Mundo</a>
            <a href="#">Minha escola</a>
        </nav>
    </header>
    <main class="graficos-section">
        <section id="graficos-container" class="graficos-container">
            <!-- crie os gráficos aqui -->
        </section>
    </main>
    <footer>
        <p>Desenvolvido por Gui Lima</p>
    </footer>
</body>
</html>
@import url('https://fonts.googleapis.com/css2?family=Nunito+Sans:ital,opsz,wght@0,6..12,200..1000;1,6..12,200..1000&display=swap');

:root {
    --bg-color: #222831;
    --primary-color: #DDDDDD;
    --secondary-color: #F05454;
    --font: "Nunito Sans", sans-serif;
}

body {
    background-color: var(--bg-color);
}
@import url('https://fonts.googleapis.com/css2?family=Nunito+Sans:ital,opsz,wght@0,6..12,200..1000;1,6..12,200..1000&display=swap');

:root {
    --bg-color: #222831;
    --primary-color: #DDDDDD;
    --secondary-color: #F05454;
    --font: "Nunito Sans", sans-serif;
}

body {
    background-color: var(--bg-color);
    color: var(--primary-color);
    font-family: var(--font);
}
async function vizualizarInformacoesGlobais() {
  const res = await fetch(url)
  const dados await res.json()
  const paragrafo document.createElement('p')
  paragrafo.classList.add('graficos-container__texto')
 paragrafo.innerHTML = `Você sabia que o mundo tem ${dados.total_pessoas_mundo} de pessoas e que aproximadamente ${dados.total_pessoas_conectadas} estão conectadas em alguma rede social e passam em média ${dados.tempo_medio} horas conectadas.`
  console.log(paragrafo)
}

vizualizarInformacoesGlobais()
async function vizualizarInformacoesGlobais() {
    const res = await fetch(url)
    const dados = await res.json()
    const pessoasConectadas = (dados.total_pessoas_conectadas / 1e9)
    const pessoasNoMundo = (dados.total_pessoas_mundo / 1e9)
    const horas = parseInt(dados.tempo_medio)
    const minutos = Math.round((dados.tempo_medio - horas) * 100)

    const paragrafo = document.createElement('p')
    paragrafo.classList.add('graficos-container__texto')
    paragrafo.innerHTML = `Você sabia que o mundo tem <span>${pessoasNoMundo} bilhões</span> de pessoas e que aproximadamente <span>${pessoasConectadas} bilhões</span> estão conectadas em alguma rede social e passam em média <span>${horas} horas</span> e <span>${minutos} minutos</span> conectadas.`

    const container = document.getElementById('graficos-container')
    container.appendChild(paragrafo)
}
