<head>
    <style>
      * {
    margin: 0;
    padding: 0;
}

body{
    background-color: lightgray;
}

main{
    max-width: 80%;
    margin: auto;
}

li {
    list-style-type: none;
    padding: .15em 0;
}

h2{
    text-align: center;
    margin: 0.5em 0;
}

ul {
    padding: 0 .5em;
    padding-bottom: .5em;
    margin: 0 auto;
}

.header {
    text-align: center;
    margin: 1em 0;
}
.tecnologias{
    padding: 1em 0;
}


.gh__container {
    display: flex;
    justify-content: center;
}

.gh__img{
    margin: 0 1em;
    max-width: 54%;
}

.cards{
    display: flex;
    justify-content: center;
}

.card__container{
    display: flex;
    flex-direction: column;
    margin: 0 1em;
    width: 40%;
}

.card__container h3 {
    text-align: center;
    padding: .5em;
    margin: 0;
}

.footer{
    display: flex;
    flex-direction: column;
    text-align: center;
}
    </style>
</head>
<body>
    <header class="header">
        <h1>Bem vindo(a) ao meu perfil.</h1>
        <p>Olá, eu sou o Elias Moura, especialista em investimentos e apaixonado por tecnologia!</p>
    </header>
    <main>
    <section>
        <div class="gh__container">
            <img class="gh__img" src="https://github-readme-stats.vercel.app/api?username=Elias-Moura&show_icons=true&theme=dark&include_all_commits=true&count_private=true"/>
            <img class="gh__img" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Elias-Moura&layout=compact&langs_count=7&theme=dark"/>
        </div>
    </section>

    <div class="tecnologias" style="text-align: center;">
        <div style="display: inline_block"></div>
            <img align="center" src="https://cdn.worldvectorlogo.com/logos/java-14.svg" alt="Java" height="30" width="40" />
            <img align="center" src="https://cdn.worldvectorlogo.com/logos/spring-3.svg" alt="Spring" height="30" width="40" />
            <img align="center" alt="JavaScript" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-plain.svg">
            <img align="center" src="https://cdn.worldvectorlogo.com/logos/typescript.svg" alt="typescript" height="30" width="40"/>
            <img align="center" alt="Python" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg">
            <img align="center" src="https://www.vectorlogo.zone/logos/reactjs/reactjs-icon.svg" alt="react.js" height="30" width="40"/>
        </div>
    </div>

    <section class="cards">
        <div class="card__container">
            <h3>Meus hobbies:</h3>
            <ul>
                <li>👨‍👩‍👦 Passar o tempo em família</li>
                <li>🏋️‍♂️ Praticar musculação</li>
                <li>🎮 Jogar com amigos</li>
                <li>🎸 Escutar música</li>
                <li>📚 Ler</li>
                <li>📺 Assistir conteúdos sobre dev</li>
            </ul>
        </div>
        <div class="card__container">
            <h3>Atualmente estudando:</h3>
            <ul>
                <li>☕ Java e Spring Boot (Back-end)</li>
                <li>💻 TypeScript - React (Front-end)</li>
            </ul>
        </div>
    </section>

    <h2>Projetos em destaque⚡</h2>
    
    <section class="cards">
        <div class="card__container">
            <h3>Alura Books 📚</h3>
            <ul>
                <li><b>Categoria:</b> Front-end.</li>
                <li>Página web de uma livraria on-line.</li>
                <li><a href="https://elias-moura.github.io/alura-books/">Projeto em produção</a></li>
                <li><a href="https://github.com/Elias-Moura/alura-books">Repositório</a></li>
                <li><b>Tecnologias abordadas:</b> HTML5 e CSS3 com mobile first e design responsivo.</li>
            </ul>
        </div>
        <div class="card__container">
            <h3>Alura Plus ✨</h3>
            <ul>
                <li><b>Categoria:</b> Front-end.</li>
                <li>Uma landing page da Alura e Alura lingua.</li>
                <li><a href="https://elias-moura.github.io/AluraPlus/">Projeto em produção</a></li>
                <li><a href="https://github.com/Elias-Moura/AluraPlus">Repositório</a></li>
                <li><b>Tecnologias abordadas:</b> HTML5 e CSS3.</li>
            </ul>
        </div>
        <div class="card__container">
            <h3>Alura-studies 📚</h3>
            <ul>
                <li><b>Categoria:</b> Front-end.</li>
                <li>Gerenciador de tempo de estudos com React e Typescript.</li>
                <li>Projeto em construção 🏗️</li>
                <li><a href="https://github.com/Elias-Moura/alura-studies">Repositório</a></li>
                <li><b>Tecnologias abordadas:</b> React, Typescript, SCSS, CSS Modules.</li>
            </ul>
        </div>
        <div class="card__container">
            <h3>Blog Pessoal 🖊️</h3>
            <ul>
                <li><b>Categoria:</b> Back-end.</li>
                <li>Blog pessoal com Java.</li>
                <li>Projeto em construção 🏗️</li>
                <li><a href="https://github.com/Elias-Moura/blog-java">Repositório</a></li>
                <li><b>Tecnologias abordadas:</b> Java, Spring Boot, MySQL</li>
                <li><b>Boas práticas:</b> DTO, Separation of Concerns, SOLID</li>
            </ul>
        </div>
    </section>
    </main>

    <footer class="footer">
        <h2>Meus contatos</h2>
        <div> 
            <a href = "mailto:eliasmoura.py@gmail.com"><img src="https://img.shields.io/badge/-Gmail-%23333?style=for-the-badge&logo=gmail&logoColor=white" target="_blank"></a>
            <a href="https://www.linkedin.com/in/elias-s-moura" target="_blank"><img src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white" target="_blank"></a>
        </div>
    </footer>
</body>
