
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ESTEVAM - Portfólio</title>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;500;600&family=Open+Sans:wght@300;400;600&display=swap" rel="stylesheet">
    <link href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" rel="stylesheet">
    <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css" rel="stylesheet">
    <style>
        /* Estilos Globais */
        body {
            font-family: 'Open Sans', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #F4F9F4; /* Cor de fundo mais suave e sofisticada */
            scroll-behavior: smooth;
            box-sizing: border-box;
        }

        /* Cabeçalho fixo */
        .contenedor-header {
            background-color: #006400; /* Verde escuro sofisticado */
            position: fixed;
            width: 100%;
            top: 0;
            left: 0;
            z-index: 99;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
        }

        .contenedor-header header {
            max-width: 1200px;
            margin: auto;
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 15px 20px;
        }

        .contenedor-header .logo a {
            font-family: 'Poppins', sans-serif;
            font-size: 36px;
            color: #fff;
            text-decoration: none;
            text-transform: uppercase;
            letter-spacing: 2px;
            transition: color 0.3s ease;
        }

        .contenedor-header .logo a:hover {
            color: #A8E6CF; /* Verde mais suave no hover */
        }

        .contenedor-header .logo a span {
            font-size: 30px;
            margin-left: 10px;
        }

        .contenedor-header header nav ul {
            display: flex;
            list-style: none;
        }

        .contenedor-header header nav ul li {
            margin-left: 20px;
        }

        .contenedor-header header nav ul li a {
            color: #fff;
            font-weight: 500;
            text-decoration: none;
            padding: 8px 12px;
            transition: color 0.3s ease, background-color 0.3s ease;
            border-radius: 5px;
        }

        .contenedor-header header nav ul li a:hover {
            color: #1e2326;
            background-color: #A8E6CF; /* Verde suave no hover */
        }

        /* Seções */
        section {
            padding: 80px 20px;
            text-align: center;
            opacity: 0;
            transform: translateY(20px);
            transition: opacity 1s ease, transform 1s ease;
            padding-top: 100px; /* Espaço extra para compensar o cabeçalho fixo */
        }

        section.visible {
            opacity: 1;
            transform: translateY(0);
        }

        h2, h3 {
            font-size: 3rem;
            color: #333;
            font-weight: 600;
            margin-bottom: 20px;
            letter-spacing: 1px;
        }

        p {
            font-size: 1.2rem;
            color: #555;
            margin-bottom: 30px;
        }

        .sobre-mim, .contato {
            background-color: #E8F5E9; /* Verde claro para contraste suave */
        }

        .curriculo-academico {
            background-color: #A5D6A7; /* Verde suave para destacar a seção */
        }

        /* Estilo do botão Conversar */
        .contato button {
            padding: 15px 40px;
            background-color: #006400; /* Verde escuro */
            color: #fff;
            border: none;
            border-radius: 50px;
            font-size: 1.5rem;
            font-weight: 600;
            cursor: pointer;
            transition: background-color 0.3s ease, transform 0.3s ease;
            text-align: center;
            display: inline-block;
        }

        .contato button:hover {
            background-color: #A8E6CF; /* Verde suave */
            transform: scale(1.05); /* Efeito de aumentar o botão ao passar o mouse */
        }

        .contato a {
            text-decoration: none;
        }

        /* Footer */
        footer {
            background-color: #006400; /* Verde escuro sofisticado */
            color: #fff;
            padding: 40px 20px;
            text-align: center;
        }

        footer .arriba i {
            font-size: 30px;
            margin-bottom: 15px;
        }

        footer .redes a {
            color: #fff;
            margin: 0 15px;
            font-size: 1.5rem;
            transition: color 0.3s ease;
        }

        footer .redes a:hover {
            color: #A8E6CF; /* Verde suave no hover */
        }

        footer p {
            font-size: 16px; /* Tamanho da fonte um pouco maior para melhorar a legibilidade */
            margin-top: 20px;
            color: #e0e0e0; /* Cor mais clara para o texto */
        }

        /* Responsividade */
        @media (max-width: 768px) {
            .contenedor-header header nav ul {
                flex-direction: column;
                align-items: center;
                padding: 10px;
            }

            .contenedor-header header nav ul li {
                margin: 10px 0;
            }

            .logo a {
                font-size: 28px;
            }
        }

    </style>
</head>
<body>

<!-- Cabeçalho -->
<div class="contenedor-header">
    <header>
        <div class="logo">
            <a href="#">ESTEVAM<span>💻</span></a>
        </div>
        <nav>
            <ul>
                <li><a href="#sobre-mim">Sobre Mim</a></li>
                <li><a href="#meus-certificados">Certificados</a></li>
                <li><a href="#curriculo-academico">Currículo Acadêmico</a></li>
                <li><a href="#projetos">Projetos</a></li>
                <li><a href="#contato">Contato</a></li>
            </ul>
        </nav>
    </header>
</div>

<!-- Seções -->
<section id="sobre-mim" class="sobre-mim">
    <h2>Sobre Mim</h2>
    <p>Profissional com formação em Ciências e Tecnologia Mecânica (UFRN) e técnico em Biocombustíveis (IFRN), buscando realocação em áreas tecnológicas de dados (especialmente em análise exploratória, programação, nuvem e segurança cibernética) e setores financeiros. Movido por desafios e soluções, desejo aplicar minhas habilidades em um ambiente dinâmico e inovador.</p>
    <p>Nos momentos livres, sou consultor de astroanálise (<a href="https://baseplus.com.br/c/heyastros" target="_blank">https://baseplus.com.br/c/heyastros</a>) e sou um life long learner. Pratico exercícios físicos e sou previsível e metódico em alguns aspectos. Não arrisco sem conhecimento.</p>
    <p>Segundo o levantamento de perfil da Mindsight, desenvolvo-me em áreas de gerenciamento, pesquisa e análise.</p>
</section>

<!-- Seção Certificados com os cursos adicionados -->
<section id="meus-certificados">
    <h2>Meus Certificados</h2>
    <p><strong>Google AI Essentials</strong> - 2024</p>
    <p><strong>Bootcamp Nexa - Machine Learning para Iniciantes na AWS</strong> - 2024</p>
    <p><strong>Santander 2024 - Preparatório Certificação AWS</strong> - 2024</p>
    <p><strong>Ciência da Computação Harvard No Brasil by Potência Tech</strong> - 2024</p>
    <p><strong>Certificado Profissional de Análise de Dados do Google</strong> - 2024</p>
    <p><strong>Trilha Digital | Coders 24 | Data Science</strong> - 2024</p>
    <p><strong>Trilha Digital | Coders 24 | Back End</strong> - 2024</p>
    <p><strong>Descubra a Nuvem em AWS by LocalizaLabs</strong> - 2023</p>
    <p><strong>Santander Bootcamp Cibersegurança</strong> - 2023</p>
    <p><strong>Bootcamp || Potência Tech by iFood - Ciência de Dados</strong> - 2023</p>
    <p><strong>Banco de Dados</strong> - 2023</p>
    <p><strong>Bootcamp || Desenvolvedor Python</strong> - 2023</p>
    <p><strong>Pacote Office 2016 (Word, Excel, PowerPoint)</strong> - 2023</p>
    <p><strong>Minicamp || Programação Básica</strong> - 2023</p>
    <p><strong>Introduction to Python</strong> - 2023</p>
    <p><strong>Formação Cybersecurity Specialist</strong> - 2022</p>
    <p><strong>Matemática Financeira</strong> - 2022</p>
    <p><strong>Minicamp || Cloud & Cybersecurity</strong> - 2022</p>
    <p><strong>Dominando HP12C</strong> - 2022</p>
    <p><strong>Aprenda a investir em ETFs</strong> - 2022</p>
    <p><strong>Desmistificando os COEs</strong> - 2022</p>
    <p><strong>Dominando o Linkedin</strong> - 2022</p>
    <p><strong>Contabilidade Básica</strong> - 2022</p>
    <p><strong>Contabilidade Comercial</strong> - 2022</p>
    <p><strong>Direito Constitucional</strong> - 2020</p>
</section>

<section id="curriculo-academico" class="curriculo-academico">
    <h2>Currículo Acadêmico</h2>
    <p><strong>Graduado Bacharel em Ciências e Tecnologia Mecânica pela Universidade Federal do Rio Grande do Norte (UFRN)</strong></p>
    <p>Entre junho de 2014 e junho de 2018, pude participar do programa de tutoria, auxiliando discentes nas disciplinas iniciais do curso.</p>
     <p></p>
    <div class="col-md-12 content-wrapper">
        <p><strong>Graduado Técnico em Biocombustíveis pelo Instituto Federal do Rio Grande do Norte (IFRN) </strong></p>
        <p>Entre janeiro de 2010 e dezembro de 2013 pude participar de programa de pesquisa da PFRH em análise de painel fotovoltaico.</p>
    </div>
    <div class="col-md-12 content-wrapper">
        <p><strong>Graduando em Licenciatura em Computação pela Universidade Federal Rural do Semi-Árido (UFERSA)</strong></p>
        <p> Desde agosto de 2024 até o momento pude participar de Programa Institucional de Bolsa de Iniciação à Docência (PIBID) </p>
    </div>
</section>

<section id="projetos">
    <h2>Projetos</h2>
    <p>Aqui estão alguns repositórios que desenvolvi com tecnologias </p>
    <ul>
        <a href="https://github.com/anicetoestevam/BOOTCAMP-DIO" target="_blank">BOOTCAMP DIO</a>,
        <a href="https://github.com/anicetoestevam/BOOTCAMP-DIO-SQL" target="_blank">BOOTCAMP DIO SQL</a>,
        <a href="https://github.com/anicetoestevam/ETL.py" target="_blank">ETL.py</a>,
        <a href="https://github.com/anicetoestevam/POWERBI.pbix" target="_blank">POWERBI.pbix</a>,
        <a href="https://github.com/anicetoestevam/lab-aws-sagemaker-canvas-estoque" target="_blank">AWS SageMaker Canvas - Estoque</a>,
        <a href="https://github.com/anicetoestevam/AWS-Rekognition" target="_blank">AWS Rekognition</a>,
        <a href="https://github.com/anicetoestevam/anicetoestevam.github.io" target="_blank">Portfolio Pessoal</a>
    </ul>
</section>

<!-- Seção de Contato com Botão para Typeform -->
<section id="contato" class="contato">
    <h2>Contato</h2>
    <a href="https://kwlbq8j1yfp.typeform.com/to/bS5foX70" target="_blank">
        <button type="button">Conversar</button>
    </a>
</section>

<!-- Footer -->
<footer>
    <div class="redes">
        <a href="https://www.linkedin.com/in/aniceto-estevam-0481b81a7/" target="_blank"><i class="fab fa-linkedin"></i></a>
        <a href="https://github.com/anicetoestevam" target="_blank"><i class="fab fa-github"></i></a>
        <a href="https://www.instagram.com/hey.astros" target="_blank"><i class="fab fa-instagram"></i></a>
        <a href="https://heyastros.com.br" target="_blank"><i class="fas fa-globe"></i></a> <!-- Ícone do Website -->
    </div>
    <p>&copy; 2025 ESTEVAM. Todos os direitos reservados.</p>
</footer>

<script>
    // Mostrar animação de entrada nas seções
    window.addEventListener('scroll', () => {
        document.querySelectorAll('section').forEach((section) => {
            if (section.getBoundingClientRect().top <= window.innerHeight / 1.3) {
                section.classList.add('visible');
            }
        });
    });
</script>

</body>
</html>
