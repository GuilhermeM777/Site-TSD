# Site-TSD
Desenvolvemos esse Site para servir como um "Portifolio" da nossa empresa, apresentando nossos trabalhos e nossa visão de mundo. Para a programação, utilizamos duas linguagems para Web, sendo a primeira o HTML, essencial para a estrutura basíca do site e o CSS, essencial para dar "Cor" e uma boa aparencia para ele. Estaremos divindo a explicação do desenvolvimento em duas partes: **HTML e CSS**.
Na fase inicial fizemos o basico, criamos as pastas para cada linguagem e uma pasta que guardaria todas imagens que utilizariamos no site. Durante toda fase de programação foi utilizado o **Visual Studio Code** para a programação.
## Apresentação do Site(Clique para ver o video)
[![Captura de tela 2024-12-01 152032](https://github.com/user-attachments/assets/68f73539-68bb-4fc8-9806-889113169029)](https://drive.google.com/file/d/17adZoJ1g90JOjKWAtci0OPKRLXXazsXI/view?usp=sharing)<br>

## Funcionalidades

- **Navegação intuitiva:** Menu fixo no topo da página para acesso rápido às seções.
- **Apresentação dos valores da empresa:** Páginas dedicadas à missão, visão e valores.
- **Equipe:** Seção que apresenta os integrantes da equipe com fotos, cargos e descrições.
- **Jogos e produtos:** Galeria com informações detalhadas sobre os jogos e outros conteúdos criados.
- **Contato:** Formulário para envio de mensagens diretamente pelo site.
- **História:** Um espaço dedicado para compartilhar a trajetória da equipe.

## Estrutura do Projeto

### HTML (Script)
      <!DOCTYPE html>
     <html lang="pt-BR">
    <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Trap Spider Developer</title>
    <link rel="stylesheet" href="CSS/style.css" >
    <link rel="shortcut icon" href="CSS/img/Logo.png">
        <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
     </head>
     <body>
    <header>
        <div class="container">
            <img src="CSS/img/Logo2.png" alt="Trap Spider Developer Logo" class="logo">
            <nav>
                <ul>
                    <li><a href="#about">Sobre Nós</a></li>
                    <li><a href="#games">Jogos</a></li>
                    <li><a href="#contact">Contato</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <section id="hero">
        <div class="container">
            <h2>Desenvolvendo jogos memoráveis e emocionantes</h2>
            <p>Descubra nosso primeiro jogo e mergulhe nessa nostalgia!</p>
            <a href="#games" class="btn">Veja nosso jogo</a>
        </div>
    </section>

    <section id="about" class="container">
        <h2>Sobre Nós</h2>
        <p>Somos uma equipe em busca de criar jogos que não sejam contidos por barreiras, e queremos sempre buscar a maior criatividade possível nos nossos projetos. Queremos criar jogos de gêneros nunca explorados, acessível a todos e principalmente, agradar a todos. </p>
    </section>

    <section id="Missao" class="container">
        <h2>Nossa Missão </h2>
        <p>Nosso objetivo e simplesmente criar "Teias" que prendam o publíco. Essas teias na verdade serão nossos jogos, com o objetivo de serém emocionantes ao ponto de agarrar nosso publíco, como uma teia.</p>
    </section>

    <section id="Visao" class="container">
        <h2>Nossa Visão </h2>
        <p>Assim como uma aranha tem 8 olhos, nos queremos ir além e conseguir ter olhos para todos tipos de publícos! Assim com o intuito de agradar a todos e não neglicenciar ninguém.</p>
    </section>

    <section id="Valores" class="container">
        <h2>Nossos Valores </h2>
        <ul>
            <li>Diversidade</li>
            <li>Transparência</li>
            <li>Comprometimento</li>
        </ul>
    </section>

    <section id="integrantes" class="container">
        <h2>Nossa Equipe</h2>
        <div class="Fotos">
            <div class="dev">
                <img src="CSS/img/Galeria/Bryan.jpg" alt="dev 1">
                <h2>Game Designer</h2>
                <h3>Bryan Henrique</h3>
                <p>
                    Gosto de pintar projetos em branco através da arte que faço.<br /><br />
                </p>
            </div>
            <div class="dev">
                <img src="CSS/img/Galeria/Erick.jpg" alt="dev 2">
                <h2>Game Developer</h2>
                <h3>Erick Felipe</h3>
                <p>
                    Gosto muito de dar vida às ideias dos meus amigos com a programação e sou apaixonado por gastronomia.
                </p>
            </div>
            <div class="dev">
                <img src="CSS/img/Galeria/Guilherme.jpg" alt="dev 3">
                <h2>Diretor Criativo</h2>
                <h3>Guilherme Matos</h3>
                <p>
                   Sou o diretor criativo da nossa empresa, gosto de idealizar nossos projetos e dar a vida ao nossos jogos.<br />
                </p>
            </div>
            <div class="dev">
                <img src="CSS/img/Galeria/Kaua.jpg" alt="dev 4">
                <h2>Game Artist</h2>
                <h3>Kauã Castro</h3>
                <p>
                    Gosto muito de criar universos fictícios, seus habitantes e dar vida a eles por meio da arte.<br /><br /><br /><br />
                </p>
            </div>
            <div class="dev">
                <img src="CSS/img/Galeria/Kauan.jpg" alt="dev 5">
                <h2>Programador BACK-END</h2>
                <h3>Kauan Jesus</h3>
                <p>
                    Um programador raiz que busca um dia trabalhar programando fora do Brasil em jogos grandes (e com grande orgulho).<br /><br />
                </p>
            </div>
            <div class="dev">
                <img src="CSS/img/Galeria/Lucas.jpg" alt="dev 6">
                <h2>Design de Interface</h2>
                <h3>Lucas Noel</h3>
                <p>
                    Gosto de me empenhar em fazer as ideías dos meu colegas funcionarem no projeto.<br /><br />
                </p>
            </div>
        </div>
    </section>

    <section id="historia">
        <div class="container">
            <img src="CSS/img/Logo2.png" alt="Trap Spider Developer Logo" class="Logo">
            <h2>Nossa História</h2>
            <p>
                Com o intuito de criar jogos acessíveis para todos, focando mais em histórias envolventes e jogabilidade de qualidade do que em uma consistência superficial, nosso grupo de amigos – que pode ser visto na seção de membros da empresa – decidimos fundar esta empresa para realizar nossos sonhos. Queremos criar jogos que tragam satisfação aos jogadores, com uma produção independente que explora temas pouco presentes no mercado. Além disso, buscamos oferecer preços acessíveis para alcançar o maior número de pessoas possível.<br /><br />
                Desde cedo, desejávamos que a indústria de jogos priorizasse esses valores, mas, infelizmente, não é o que observamos há muito tempo. Queremos reacender a chama da verdadeira essência dos jogos, trazendo de volta a alegria de chegar em casa após um dia cansativo, ligar o console ou computador e se desconectar do mundo.
            </p>
        </div>
    </section>

    <section id="games" class="container">
        <h2>Nossos produtos</h2>
        <div class="gallery">
            <div class="game">
                <img src="CSS/img/CapaHq.png" alt="Jogo 1">
                <h3>Aço e Vapor</h3>
                <p>
                    Um jogo inspirado em Gun Fight (1975) publicado pela Taito, no qual o principal objetivo e trazer uma grande dose de nostalgia por jogos de Velho Oeste. Inspirado em uma jogabilidade Metrodvania do Genêro plataforma, Aço e Vapor e divido em 5 fases com cada uma tendo inimigos unicos.<br /><br /><br /><br />
                    Baseado num universo SteamPunk, a temática gira em torno de um mundo destruido e desertíco onde o protagonista deseja vingança contra "Duque". Para isso ele deve ir até "Saint Louis" e enfrentar os chefes de cada departamento, algo que não sera facíl.<br /><br /><br /><br />

                </p>
            </div>
            <div class="game">
                <img src="CSS/img/HQIcon.png" alt="HQ">
                <h3>Historia do Protagonista(HQ)</h3>
                <p>
                    Essa e uma HQ que conta a historia de nosso protagonista que é um Xerife em um pequeno vilarejo no deserto desolado. Durante uma de suas patrulhas um homem chamado Duque Holliday ataca a vila do agora solitário Xerife.<br /><br />
                    Para acessar a HQ inteira, va nos arquivos desse site e procure a pasta de "HQ".
                </p>
            </div>
        </div>
    </section>

    <section id="contact" class="container">
        <h2>Contato</h2>
        <form>
            <label for="name">Nome:</label>
            <input type="text" id="name" name="name" required>

            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required>

            <label for="message">Mensagem:</label>
            <textarea id="message" name="message" required></textarea>

            <button type="submit">Enviar</button>
        </form>
    </section>

    <footer>
        <div class="container">
            <nav>
                <ul>
                   <li>&copy; 2024 Trap Spider Developer. Todos os direitos reservados.</li>
                    <li>E-Mail para contato:Spiderdev@gmail.com</li>
                    <li>Telefone para contato:11 97153-7358</li>
                    <li>Endereço:R.Dos Gusmões, 624 Santa efigênia</li>
                </ul>
            </nav>
        </div>
    </footer>
     </body>
    </html>

# HTML (Explicação)
- **Cabeçalho (`<header>`):** Menu de navegação com links para as seções.
- **Seções principais:**
  - Hero: Banner inicial com mensagem de boas-vindas.
  - Sobre Nós: Informações sobre os objetivos da empresa.
  - Missão, Visão e Valores.
  - Equipe: Apresentação dos membros.
  - Produtos: Detalhes sobre jogos e HQs.
  - Contato: Formulário de envio.
  - História: Histórico da empresa.
- **Rodapé (`<footer>`):** Informações de contato.

### CSS (Script PT1)

    body {
    font-family: 'Roboto', sans-serif;
    margin: 0;
    padding: 0;
    background-image: url(img/FundoClaro.png);
    background-size: 50px 50px;
    color: #333;
    overflow-x: hidden;
    }

    html, body {
    width: 100vw;
    height: 100vh;
    }

    header .logo {
    display:inline;
    margin: 0px -400px 0px 0px;
    }

    header {
    background-image: url(img/FundoEscuro.png);
    background-size: 50px 50px;
    background-position: center;
    color: #be0000;
    padding: 0px 0px;
    margin: 0px;
    position: fixed;
    width: 100%;
    height: -100%;
    top: -10px;
    z-index: 1000;
    }

    header .container {
        display: flex;
        justify-content: space-between;
        align-items: center;
        text-decoration-line: underline;
        color: whitesmoke;
        margin: 0px 1px;
    }

    header h1 {
    margin: 0;
    font-size: 48px;
    align-self:initial;
     }

    header nav ul {
    margin: 0px -800px;
    padding: 0px;
    display: flex;
    color: whitesmoke;
    }

    header nav ul li {
        margin: 0 15px;
        color: whitesmoke;
        font-size:25px;
    }

    header nav ul li a {
    color: whitesmoke;
    margin: 0px 90px;
    text-decoration: none;
    font-weight: 700;
    transition: color 0.3s;
    font-size: 25px
    }

    header nav ul li a:hover {
    color: red;
    }

    #hero {
    background-image: url(img/SalaRaio.png);
    background-repeat: no-repeat;
    background-position:center;
    background-size: 100% 130%;
    height: 100vh;
    display: flex;
    justify-content: center;
    align-items: center;
    text-align: center;
    color: white;
    position: relative;
    }

    #historia {
    background-image: url(img/FundoHistoria.jpg);
    background-repeat: no-repeat;
    background-size: cover;
    height: 100vh;
    display: flex;
    justify-content: center;
    align-items: center;
    text-align: justify;
    color: purple;
    position: relative;

    }

    #historia::after {
    content: '';
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background: rgba(0, 0, 0, 0.8);
    z-index: 0;
     }

    #historia .container {
    position: relative;
    z-index: 1;
    }

    #historia h2{
    font-size: 48px;
    margin: 0;
    color:whitesmoke;

    }

    #historia p {
    font-size: 24px;
    margin: 20px 0;
    color: white;
    }

    #hero .container {
    position: relative;
    z-index: 1;
      }

    #hero::after {
    content: '';
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background: rgba(0, 0, 0, 0.8);
    z-index: 0;

     }

     #hero h2 {
    font-size: 48px;
    margin: 0;
    color: white;
         }

     #hero p {
        font-size: 24px;
        margin: 20px 0;
        color: white;
     }

    #hero .btn {
        background: red;
        color: white;
        padding: 10px 20px;
        text-decoration: none;
        border-radius: 5px;
        transition: background 0.3s;
    }

    #hero .btn:hover {
    background: darkred;
    }

    .container {
    max-width: 1200px;
    margin: 0 auto;
    padding: 20px;
    }

    section {
    padding: 60px 0;
    }
 
    #about, #Missao, #Visao {
    background-image: url(img/FundoEscuro.png);
    background-size: 30px 30px;
    margin: 20px 350px;
    border-radius: 5px;
    padding: 20px;
    box-shadow: 0 0 10px rgba(0,0,0,0.1);
    color: whitesmoke;
    font-size: 20px;
    text-align: center;
    justify-content:center;
    }

    #contact {
    background-image: url(img/FundoEscuro.png);
    background-size: 30px 30px;
    margin: 20px 350px;
    border-radius: 5px;
    padding: 20px;
    box-shadow: 0 0 10px rgba(0,0,0,0.1);
    color: whitesmoke;
    font-size: 20px;
    align-self:center;
    align-content:center;
    align-items:center;
    }

# CSS (Explicação)
  - Cores temáticas, com predominância de tons escuros, vermelho e branco.
  - Backgrounds personalizados para cada seção.
- **Responsividade:**
  - Layout adaptado para diferentes resoluções de tela.
- **Interatividade:**
  - Transições suaves para elementos interativos, como botões e links.
- **Galeria e grid:**
  - Uso de flexbox para organizar elementos em diferentes seções.
 
### CSS (Script PT 2)

    #Valores {
    background-image: url(img/FundoEscuro.png);
    background-size: 30px 30px;
    margin: 20px 350px;
    border-radius: 5px;
    padding: 20px;
    box-shadow: 0 0 10px rgba(0,0,0,0.1);
    color: whitesmoke;
    font-size: 30px;
    text-align: center;
    }

    #Valores ul li {
    list-style-type:none;
    text-decoration:underline;

    }

    #contact  h2 {
     font-size: 35px;
    }

    #Missao  h2 {
     font-size: 35px;
    }

    #Visao  h2 {
     font-size: 35px;
    }

    #Valores  h2 {
     font-size: 45px;
    }

    #games .gallery {
    display: flex;
    flex-wrap: wrap;
    gap: 20px;
    justify-content: center;
    color: whitesmoke;
    align-items: center;
    }

    #games .game {
    background: #3f0873;
    border-radius: 5px;
    overflow: hidden;
    box-shadow: 0 0 10px rgba(0,0,0,0.1);
    flex-basis: 30%;
    text-align: center;
    color: darkgoldenrod;
    }
 
    #games {
    color: whitesmoke;
    align-self: flex-start;
    text-align: center;
    }

    #games .game img {
    width: 100%;
    height: auto;
    }

    #games .game h3 {
    margin: 15px 0;
    font-size: 20px;
    color: white;
    }

    #games h2 {
    margin: 15px 0;
    font-size: 40px;
    color:whitesmoke;
    background-image: url(img/FundoEscuro.png);
    background-size: 50px 50px;
    }

    #games .gallery {
    display: flex;
    flex-wrap: wrap;
    gap: 20px;
    justify-content: center;
    color:whitesmoke;
    align-items:center;
    }

    #games .game {
    background-image: url(img/FundoEscuro.png);
    background-size: 30px 30px;
    border-radius: 5px;
    overflow: hidden;
    box-shadow: 0 0 10px rgba(0,0,0,0.1);
    flex-basis: 30%;
    text-align: center;
    color: whitesmoke;
    }

    #integrantes {
    color: whitesmoke;
    text-align: center;
    }

    #integrantes .dev img {
    width: 100%;
    height: auto;
    }

    #integrantes .dev h3 {
    margin: 15px 0;
    font-size: 20px;
    color: whitesmoke;
    }

    #integrantes .dev h2 {
    margin: 15px 0;
    font-size: 30px;
    color: whitesmoke;
    }

    #integrantes h2 {
    margin: 15px 0;
    font-size: 40px;
    color:whitesmoke;
    background-image: url(img/FundoEscuro.png);
    background-size: 50px 50px;
    }

    #integrantes .Fotos {
    display: inline-flex;
    flex-wrap: nowrap;
    gap: 20px;
    justify-content: center;
    color: whitesmoke;
    align-items: center;
    }

    #integrantes .dev {
    background-image: url(img/FundoEscuro.png);
    background-size: 30px 30px;
    border-radius: 5px;
    overflow: hidden;
    box-shadow: 0 0 10px rgba(0,0,0,0.1);
    flex-basis: 40%;
    text-align: center;
    color: whitesmoke;
    }

    integrantes .dev h2 {
    font-size: 27px;
    }




    form {
    display: flex;
    flex-direction: column;
    }

    form label {
    margin: 10px 0 5px;
    font-weight: 700;
    }

    form input, form textarea, form button {
        padding: 10px;
        margin: 5px 0 10px;
        border: 1px solid #ccc;
        border-radius: 5px;
        font-size: 16px;
        color: whitesmoke;
        background-color: #330169;
    }

    form button {
        background: whitesmoke;
        color: black;
        border: none;
        cursor: pointer;
        transition: background 0.3s;
    }

    form button:hover {
    background: darkred;
    }

    footer {
    background-image: url(img/FundoEscuro.png);
    background-size: 50px 50px;
    background-position: center;
    color: whitesmoke;
    text-align: center;
    padding: 20px 0;
    position: center;
    }

    footer .container {
    display: flex;
    }

    footer nav ul {
    list-style: none;
    margin: 0;
    padding: 0;
    display: flex;
    }

    footer nav ul li {
    margin: 0 15px;
    }
    
## Linguagens Usadas

- **HTML:** Para a estrutura e conteúdo do site.
- **CSS3:** Para estilização e responsividade.


## Créditos

Equipe Trap Spider Developer:
- **Bryan Henrique** - Game Designer
- **Erick Felipe** - Game Developer
- **Guilherme Matos** - Diretor Criativo
- **Kauã Castro** - Game Artist
- **Kauan Jesus** - Programador Back-End
- **Lucas Noel** - Designer de Interface



## Contato

- **E-mail:** Spiderdev@gmail.com  
- **Telefone:** 11 97153-7358  
- **Endereço:** R. dos Gusmões, 624, Santa Efigênia  

