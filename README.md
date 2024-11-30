<!DOCTYPE html>
<html lang="pt-br">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <!--Link para o Css-->
    <link rel="stylesheet" href="index.css">
    <title>Portifólio De Wane</title>
    <!--Link para importar a Font do Google-->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Pathway+Gothic+One&display=swap" rel="stylesheet">
    <!--Link para importar o Font Awesome-->
    <link href='https://unpkg.com/boxicons@2.1.4/css/boxicons.min.css' rel='stylesheet'>

    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.6.0/css/all.min.css"
        integrity="sha512-Kc323vGBEqzTmouAECnVceyQqyqdsSiqLQISBL29aUW4U/M7pSPA/gEUZQqv1cwx4OnYxTxve5UMg5GT6L4JJg=="
        crossorigin="anonymous" referrerpolicy="no-referrer" />
</head>

<body>
    <!-- NavBar Configurações -->
    <header class="header">
        <a href="#home" class="logo"><span>WANE</span></a>
        <ul class="navbar">
            <li><a href="#home" class="active">Início</a></li>
            <li><a href="#skills">Habilidades</a></li>
            <li><a href="#works">Trabalhos</a></li>
            <li><a href="#contact">Contatos</a></li>
        </ul>
        <!-- Dark Mode Configurações -->
        <div class="main">
            <div class="dark-mode">
                <input type="checkbox" class="checkbox" id="chk">
                <label class="label" for="chk">
                    <i class="fas fa-moon"></i>
                    <i class="fas fa-sun"></i>
                    <div class="ball"></div>
                </label>

            </div>
            <!-- NavBar Responsiva Configurações -->
            <div class="bx bx-menu" id="menu-icon"></div>
        </div>
    </header>

    <!-- Seção de Início -->
    <!-- Seção de Início -->
    <section class="home" id="home">
        <!-- Imagem do Início (essa pode permanecer a mesma para todos os dispositivos) -->
        <div class="home-img">
            <img src="img/sant.jpg" alt="">
        </div>

        <!-- Texto da tela de início para DESKTOP -->
        <div class="home-content desktop">
            <h1> Eu sou <span>Wane</span></h1>
            
            <p>Tenho 19 anos, sou desenvolvedor front-end e estudante de Análise e Desenvolvimento de Sistemas, com foco
                em Front-End e
                interesse em agilidade com Scrum. Participei de um projeto escolar desenvolvendo um site para
                professores compartilharem
                conteúdos com alunos. Já atuei como freelancer, o que aprimorou minhas habilidades e colaboração. Busco
                oportunidades
                para aplicar meus conhecimentos e crescer profissionalmente em um ambiente dinâmico. .</p>
            <!-- Links Sociais e botão de currículo como estão -->
            <div class="social-icons">
                <a href="" target="_blank"><i
                        class="fa-brands fa-linkedin"></i></a>
                <a href="https://github.com/wanevl" target="_blank"><i class="fa-brands fa-github"></i></a>
                <a href="https://www.instagram.com/xlwany/?hl=pt_BR" target="_blank"><i class="fa-brands fa-instagram"></i></a>
                <a href=""><i class="fa-brands fa-x-twitter"></i></a>
            </div>
            <a href="Currículo Wane.pdf" target="_blank" class="btn">Baixe o Currículo</a>
        </div>

        <!-- Texto da tela de início para MOBILE -->
        <div class="home-content mobile">
            <h1>Oi, Eu sou <span>Sant</span></h1>
            <h3 class="text-typing">E sou <span></span></h3>
            <p>Tenho 19 anos,sou desenvolvedor front-end e estudante de Análise e Desenvolvimento de Sistemas, com foco
                em Front-End e
                interesse em agilidade com Scrum. Participei de um projeto escolar desenvolvendo um site para
                professores compartilharem
                conteúdos com alunos. Já atuei como freelancer, o que aprimorou minhas habilidades e colaboração. Busco
                oportunidades
                para aplicar meus conhecimentos e crescer profissionalmente em um ambiente dinâmico.</p>
            <div class="social-icons">
                <a href="" target="_blank"><i
                        class="fa-brands fa-linkedin"></i></a>
                <a href="https://github.com/devsantx" target="_blank"><i class="fa-brands fa-github"></i></a>
                <a href="https://www.instagram.com/xlwany/?hl=pt_BR"target="_blank"><i class="fa-brands fa-instagram"></i></a>
                <a href="#"><i class="fa-brands fa-x-twitter"></i></a>
            </div>
            <a href="Curriculo Pessoal.pdf" target="_blank" class="btn">Baixe o Currículo</a>
        </div>
    </section>
    <!-- Seção de habilidades -->
    <section class="skills" id="skills">
        <h2 class="heading">Habilidades</h2>
        <!-- Box contendo as Tecnologias -->
        <div class="container">
            <div class="row" id="skillsContainer">
                <!-- Tecnologias -->
                <div class="bar">
                    <div class="info">
                        <img src="img/icons8-figma.svg" alt="">
                        <span>Figma</span>
                    </div>
                </div>
                <div class="bar">
                    <div class="info">
                        <img src="img/html5-brands-solid (1).svg" alt="">
                        <span>HTML</span>
                    </div>
                </div>
                <div class="bar">
                    <div class="info">
                        <img src="img/css3-alt-brands-solid (1).svg" alt="">
                        <span>CSS</span>
                    </div>
                </div>
                <div class="bar">
                    <div class="info">
                        <img src="img/js-brands-solid (1).svg" alt="">
                        <span>JavaScript</span>
                    </div>
                </div>
                <div class="bar">
                    <div class="info">
                        <img src="img/react-brands-solid (1).svg" alt="">
                        <span>React JS</span>
                    </div>
                </div>
            </div>
        </div>
        </div>
    </section>

    <!-- Seção de Formação Acadêmica -->
    <!-- <section class="education" id="education">
    
         </section> -->
    <!-- Seção de Trabalhos -->
    <section class="works" id="works">
        <h2 class="heading">Trabalhos</h2>
        <div class="works-container">
            <!-- Box contendo os Trabalhos -->
            <div class="box">
                <div class="sizac">
                    <img src="img/sizac logo.png" alt="">
                    <h1 class="site">Site Institucional</h1>
                    <div class="text">
                        <p>O SIZAC, criado em 2023, facilita o acesso de estudantes ao conteúdo acadêmico, organizando
                            atividades e prazos de forma prática. A plataforma oferece uma interface intuitiva e
                            integração
                            com ferramentas como Google Drive, tornando o aprendizado mais acessível e eficiente.
                            Publicado
                            na Google Play Store, o sistema segue em expansão com foco em novas funcionalidades para
                            melhorar a experiência educacional.</p>
                    </div>
                    <div class="botao">
                        <a href="https://sizac.org/index.php" target="_blank" rel="noopener noreferrer"
                            class="btn">Saiba
                            Mais!</a>
                    </div>
                </div>
            </div>
            <div class="box">
                <div class="sizac">
                    <img src="img/Simbolo_colorido.png" alt="">
                    <h1 class="site">Site Profissional</h1>
                    <div class="text">
                        <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Nam mollitia nihil necessitatibus
                            ipsa? Laboriosam sapiente assumenda repellendus voluptate doloremque iste, quae sequi ex
                            quasi minus voluptatibus a, velit iure rem? Lorem ipsum dolor sit amet consectetur
                            adipisicing elit. Aspernatur cupiditate tempora sapiente accusantium voluptates? A
                            reprehenderit quidem optio eaque accusamus adipisci vero, ipsa quibusdam eos aspernatur quia
                            libero repellendus nisi.</p>
                    </div>
                    <div class="botao">
                        <a href="#" rel="noopener noreferrer" class="btn" onclick="alerta()">Saiba Mais!</a>
                    </div>
                </div>
            </div>
            <div class="box">
                <div class="sizac">
                    <img src="img/infinito amor.png" class="infinito" alt="">
                    <h1 class="site">Site Profissional</h1>
                    <div class="text">
                        <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Est consectetur, doloribus optio
                            assumenda aut alias minima repellendus porro quos perspiciatis odio vitae magnam provident
                            sit accusantium sed doloremque, quisquam voluptatum. Lorem ipsum dolor sit amet consectetur,
                            adipisicing elit. Labore quam corporis eveniet quae tempora, necessitatibus placeat neque
                            illo dolore nostrum maxime consequuntur vitae porro! Maiores magnam ea consequuntur earum
                            nihil.</p>
                    </div>
                    <div class="botao">
                        <a href="#" rel="noopener noreferrer" class="btn" onclick="alerta()">Saiba
                            Mais!</a>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Seção de Contatos -->
    <section class="contact" id="contact">
        <h2 class="heading">Contact-<span>Me</span></h2>
        <form id="contact-form">
            <div class="input-box">
                <input type="text" name="name" placeholder="Nome" required>
                <input type="email" name="email" placeholder="Email" required>
                <input type="text" id="number" name="number" placeholder="Número" required>
                <input type="text" name="subject" placeholder="Assunto" required>
            </div>
            <textarea name="message" cols="30" rows="10" placeholder="Sua Mensagem"></textarea>
            <input type="submit" value="Enviar Mensagem" class="btn">
        </form>
    </section>

    <!-- Inclua o SDK do EmailJS -->
    <script type="text/javascript" src="https://cdn.emailjs.com/dist/email.min.js"></script>
    <!-- Seção de Footer -->
    <footer class="footer">
        <!-- Botões do Footer -->
        <div class="social">
            <a href="https://www.linkedin.com/in/wanderson-menezes-ab916a33b/" target="_blank"><i class="fa-brands fa-linkedin"></i></a>
            <a href="https://github.com/wanevl" target="_blank"><i class="fa-brands fa-github"></i></a>
            <a href="https://www.instagram.com/xlwany/?hl=pt_BR" target="_blank"><i class="fa-brands fa-instagram"></i></a>
            <a href=""><i class="fa-brands fa-x-twitter"></i></a>
        </div>
        <ul class="list">
            <!-- <li><a href="#">FAQ</a></li> -->
            <li><a href="#home">Início</a></li>
            <li><a href="#skills">Habilidades</a></li>
            <!-- <li><a href="#education">Formação Acadêmica</a></li> -->
            <li><a href="#works">Trabalhos</a></li>
            <li><a href="#contac">Contact</a></li>
            <li><a href="#">Privacy Policies</a></li>
        </ul>
        <p class="copyright">
            &copy; Wane Developer | Todos os Direitos <Ri:viewport></Ri:viewport>Reservados
        </p>
    </footer>
    <!-- Link para o Script -->
    <script src="index.js"></script>
</body>

</html>
