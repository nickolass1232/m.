# m.<!DOCTYPE html>
<html>

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>BookHouse</title>
    <link rel="stylesheet" href="reset.css">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=EB+Garamond:ital@1&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="style.css">
</head>

<body>
    <header class="cabecalho">
        <div class="container">
            <input type="checkbox" id="menu" class="container__botao">
            <label for="menu" class="container__rotulo">
                <span class="cabecalho__menu-hamburguer container__imagem"></span>
            </label>
            <ul class="lista-menu">
                <li class="lista-menu__titulo">Categorias</li>
                <li class="lista-menu__item">
                    <a href="#" class="lista-menu__link">Romance</a>
                </li>
                <li class="lista-menu__item">
                    <a href="#" class="lista-menu__link">Terror</a>
                </li>
                <li class="lista-menu__item">
                    <a href="#" class="lista-menu__link">Suspense</a>
                </li>
            </ul>
            <img src="Screenshot_20230905-120636.png" alt="Logo do BookHouse" class="container__imagem">
            <h1 class="container__titulo"><b class="container__titulo--negrito">Book</b>House</h1>
        </div>

        <ul class="opcoes">
            <input type="checkbox" id="opcoes-menu" class="opcoes__botao">
            <label for="opcoes-menu" class="opcoes__rotulo">
                <li class="opções__item">Categorias</li>
            </label>

            <ul class="lista-menu">
                <li class="lista-menu__item">
                    <a href="#" class="lista-menu__link">Romance</a>
                </li>
                <li class="lista-menu__item">
                    <a href="#" class="lista-menu__link">Terror</a>
                </li>
                <li class="lista-menu__item">
                    <a href="#" class="lista-menu__link">Suspense</a>
                </li>
            </ul>

            <li class="opcoes__item"><a href="#" class="opcoes__link">Favoritos</a></li>
            <li class="opcoes__item"><a href="#" class="opcoes__link">Minha estante</a></li>
        </ul>

        <div class="container">
            <a href="#"><img src="" alt="Meus favoritos"
                    class="container__imagem container__imagem-transparente"></a>
            <a href="#" class="container__link">
                <img src="3594363.png" alt="Carrinhos de compras" class="container__imagem">
                <p class="images (2).png">Minha sacola</p>
            </a>
            <a href="#" class="container__link">
                <img src="images (1).png" alt="Meu perfil" class="container__imagem">
                <p class="">Meu perfil</p>
            </a>
        </div>
    </header>
    <section class="banner">
        <h2 class="banner__titulo">Já sabe por onde começar?</h2>
        <p class="banner__texto">Encontre em nossa estante o que precisa para seu desenvolvimento!</p>
        <input type="search" class="banner__pesquisa" placeholder="Qual será sua próxima leitura?">
    </section>
    <section class="carrossel">
        <h2 class="carrossel__titulo">Novos lançamentos</h2>
        <!-- Slider main container -->
        <div class="carrossel__container">
            <div class="swiper">
                <!-- Additional required wrapper -->
                <!-- If we need pagination -->
                <div class="swiper-pagination"></div>

                <div class="swiper-wrapper">
                    <!-- Slides -->
                    <div class="swiper-slide"><img src="91fQ51I4TRL._AC_UF1000,1000_QL80_.jpg"
                            alt="O Exorcista"></div>
                    <div class="swiper-slide"><img src="9786555654127_7fc22a57-9943-44e3-add0-f2c10ec12bf3.webp"
                            alt="A Hipótese do Amor"></div>
                    <div class="swiper-slide"><img src="image5-14-.webp"
                            alt="O Paiente"></div>
                    <div class="swiper-slide"><img src="o-homem-de-giz-202x300.jpg" alt="O Homem de Giz"></div>
                    <div class="swiper-slide"><img src="saboroso-cadaver.png" alt="saboroso-cadaver"></div>
                    <div class="swiper-slide"><img src="índice.jpeg" alt="Como eu era ante de você"></div>
                </div>

                <!-- If we need navigation buttons -->
                <div class="swiper-button-prev"></div>
                <div class="swiper-button-next"></div>
            </div>

            <div class="card">
                <!-- 1º linha -->
                <div class="card__descricao">
                    <!-- 1º coluna -->
                    <div class="descricao">
                        <h3 class="descricao__titulo">Talvez você também se interesse por...</h3>
                        <h2 class="descricao__titulo-livro">A culpa é das estrelas</h2>
                        <p class="descricao__texto">hazel é uma adolescente que luta pel vida, há algun anos,por causa de um câncer em estado avançado.</p>
                    </div>
                    <!-- 2º coluna -->
                    <img src="a culpa é das estrelas - Pesquisa Google.png" class="descricao__imagem">
                </div>

                <!-- 2º linha -->
                <div class="card__botoes">
                    <!-- 1º coluna -->
                    <ul class="botoes">
                        <li class="botoes__item"><img src="992020a0ecd344219e94abe6192d7601.jpg" alt="Favoritar livro"></li>
                        <li class="botoes__item"><img src="3594363.png" alt="Adicionar no carrinho de compras"></li>
                    </ul>
                    <!-- 2º coluna -->
                    <a href="#" class="botoes__ancora">Saiba mais</a>
                </div>
            </div>
        </div>
    </section>

    <section class="carrossel">
        <h2 class="carrossel__titulo">Mais vendidos</h2>
        <!-- Slider main container -->
        <div class="carrossel__container">
            <div class="swiper">
                <!-- Additional required wrapper -->
                <!-- If we need pagination -->
                <div class="swiper-pagination"></div>

                <div class="swiper-wrapper">
                    <!-- Slides -->
                    <div class="swiper-slide"><img src="0cc9a92376d1529a2cea4d8787c12c5e.webp"
                            alt="Livro sobre apache kafka e spring boot da alura books"></div>
                    <div class="swiper-slide"><img src="MED_os-sete-maridos-de-evelyn-hugo-taylor-jenkins-reid-8122022844.jpg"
                            alt="Livro sobre liderança em design da alura books"></div>
                    <div class="swiper-slide"><img src="download.png"
                            alt="Livro sobre javascript assertivo da alurabooks"></div>
                    <div class="swiper-slide"><img src="20202ed06536ce44333c47c05d9683ec.jpeg" alt="Livro Guia front end"></div>
                    <div class="swiper-slide"><img src="3823001.webp" alt="Livro sobre portugol"></div>
                    <div class="swiper-slide"><img src="livros-mais-vendidos.webp" alt="livro sobre acessibilidade"></div>
                </div>

                <!-- If we need navigation buttons -->
                <div class="swiper-button-prev"></div>
                <div class="swiper-button-next"></div>
            </div>

            <div class="card">
                <!-- 1º linha -->
                <div class="card__descricao">
                    <!-- 1º coluna -->
                    <div class="descricao">
                        <img src="IMG_20230910_152559_179.webp" alt="Avaliação 5 estrelas">
                        <h3 class="descricao__titulo">Autora do Mês</h3>
                        <h2 class="descricao__titulo-livro">Caroline Ribas Rosa</h2>
                        <p class="descricao__texto">Escritora, Caroline é especialista em escrever livros de romance.
                        </p>
                    </div>
                    <!-- 2º coluna -->
                    <img src="IMG_20230910_152559_179 (3).webp" class="descricao__imagem">
                </div>

                <!-- 2º linha -->
                <div class="card__botoes">
                    <!-- 1º coluna -->
                    <ul class="botoes">
                        <li class="botoes__item"><img src="img/Favoritos.svg" alt="Favoritar livro"></li>
                        <li class="botoes__item"><img src="img/Compras.svg" alt="Adicionar no carrinho de compras"></li>
                    </ul>
                    <!-- 2º coluna -->
                    <a href="#" class="botoes__ancora">Saiba mais</a>
                </div>
            </div>
        </div>
    </section>

    <section class="topicos">
        <h2 class="topicos__titulo">TÓPICOS VISITADOS RECENTEMENTE</h2>
        <ul class="topicos__lista">
            <li class="topicos__item">
                <a href="#" class="topicos__link">Romance</a>
            </li>
            <li class="topicos__item">
                <a href="#" class="topicos__link">Suspense</a>
            </li>
            <li class="topicos__item">
                <a href="#" class="topicos__link">terror</a>
            </li>
            <li class="topicos__item"> 
            <li class="topicos__item">
                <a href="#" class="topicos__link">Casos criminais</a>
            </li>
        </ul>
    </section>

    <section class="contato">
        <div class="contato__descricao">
            <h2 class="contato__titulo">Fique por dentro das novidades!</h2>
            <p class="contato__texto">Atualizações de e-books, novos livros, promoções e outros.</p>
        </div>
        <input type="email" placeholder="Cadastre seu e-mail" class="contato__email">
    </section>

    <hr />

    <footer class="rodape">
        <h2 class="rodape__titulo">Grupo Alura</h2>
        <ul class="lista-rodape">
            <li class="lista-rodape__titulo">Educação</li>
            <li class="lista-rodape__item">
                <img src="img/CasaDoCodigo.svg" alt="Logo da casa do código">
                <a href="#" class="lista-rodape__link">Casa do código</a>
            </li>
            <li class="lista-rodape__item">
                <img src="img/Caelum.svg" alt="Logo da caelum">
                <a href="#" class="lista-rodape__link">Caelum</a>
            </li>
        </ul>

        <ul class="lista-rodape">
            <li class="lista-rodape__titulo">Educação online</li>
            <li class="lista-rodape__item">
                <img src="img/Alura.svg" alt="Logo da Alura">
                <a href="#" class="lista-rodapé__link">Alura</a>
            </li>
            <li class="lista-rodape__item">
                <img src="img/AluraEmpresas.svg" alt="Logo da Alura para Empresas">
                <a href="#" class="lista-rodapé__link">Alura para Empresas</a>
            </li>
            <li class="lista-rodape__item">
                <img src="img/AluraLATAM.svg" alt="Logo da Alura Latam">
                <a href="#" class="lista-rodapé__link">Alura LATAM</a>
            </li>
            <li class="lista-rodape__item">
                <img src="img/AluraStart.svg" alt="Logo da Alura START">
                <a href="#" class="lista-rodapé__link">Alura Start</a>
            </li>
            <li class="lista-rodape__item">
                <img src="img/MusicDot.svg" alt="Logo da Music Dot">
                <a href="#" class="lista-rodapé__link">Music Dot</a>
            </li>
            <li class="lista-rodape__item">
                <img src="img/AluraLingua.svg" alt="Logo da Alura Lingua">
                <a href="#" class="lista-rodapé__link">Alura Lingua</a>
            </li>
            <li class="lista-rodape__item">
                <img src="img/PM3.svg" alt="Logo da PM3">
                <a href="#" class="lista-rodape__link">PM3</a>
            </li>
        </ul>

        <ul class="lista-rodape">
            <li class="lista-rodape__titulo">Comunidade</li>
            <li class="lista-rodape__item">
                <img src="img/HipstersTech.svg" alt="Logo do Hipsters ponto Tech">
                <a href="#" class="lista-rodape__link">Hipsters ponto Tech</a>
            </li>
            <li class="lista-rodape__item">
                <img src="img/ScubaDev.svg" alt="Logo do Scuba Dev">
                <a href="#" class="lista-rodape__link">Scuba Dev</a>
            </li>
            <li class="lista-rodape__item">
                <img src="img/LayersTech.svg" alt="Logo do Layers ponto Tech">
                <a href="#" class="lista-rodape__link">Layers ponto Tech</a>
            </li>
            <li class="lista-rodape__item">
                <img src="img/LikeABoss.svg" alt="Logo do Like a Boss">
                <a href="#" class="lista-rodape__link">Like a Boss</a>
            </li>
            <li class="lista-rodape__item">
                <img src="img/CarreiraSemFronteira.svg" alt="Logo do Carreira sem fronteiras">
                <a href="#" class="lista-rodape__link">Carreira sem fronteiras</a>
            </li>
            <li class="lista-rodape__item">
                <img src="img/HipstersJobs.svg" alt="Logo do Hipsters ponto jobs">
                <a href="#" class="lista-rodape__link">Hipsters ponto jobs</a>
            </li>
            <li class="lista-rodape__item">
                <img src="img/GUJ.svg" alt="Logo do GUJ">
                <a href="#" class="lista-rodape__link">GUJ</a>
            </li>
        </ul>
    </footer>

    <script src="https://unpkg.com/swiper@8/swiper-bundle.min.js"></script&gt;
    <script>
        const swiper = new Swiper('.swiper', {
            spaceBetween: 10,
            slidesPerView: 3,
            pagination: {
                el: '.swiper-pagination',
                type: 'bullets',
            },
        });
    </script>
</body>

</html>
