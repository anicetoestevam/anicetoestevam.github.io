# Portfólio Pessoal - ESTEVAM

Este é o código-fonte do meu portfólio pessoal online. Ele apresenta minhas informações profissionais, certificados, projetos e formas de contato.

## Visão Geral

O portfólio é uma página web única (single page application) desenvolvida com HTML, CSS e JavaScript hospedada em github.io. Ela utiliza bibliotecas externas como Bootstrap, Font Awesome, Google Fonts e Chart.js para criar uma interface moderna e responsiva.

## Estrutura do Projeto

*   `index.html`: O arquivo principal contendo toda a estrutura HTML, estilos CSS embutidos (`<style>`) e scripts JavaScript.
*   `README.md`: Este arquivo.

## Funcionalidades

*   **Apresentação Pessoal:** Seção "Sobre Mim" detalhando formação, habilidades e interesses.
*   **Certificados:** Visualização em gráfico de pizza dos principais certificados obtidos, utilizando Chart.js.
*   **Currículo Acadêmico:** Informações sobre graduações e experiências acadêmicas.
*   **Projetos:** Lista de projetos desenvolvidos com links para repositórios no GitHub.
*   **Download de Currículo:** Link direto para download do currículo em PDF hospedado no Google Docs.
*   **Agendamento Online:** Integração com Calendly para permitir agendamentos diretos.
*   **Contato:** Link para um Typeform de contato.
*   **Links Sociais:** Links para LinkedIn, GitHub, Instagram e site pessoal.
*   **Modo Escuro:** Botão para alternar entre o modo claro e escuro.
*   **Design Responsivo:** Layout que se adapta a diferentes tamanhos de tela.
*   **Animações:** Efeitos de transição suaves ao rolar a página.

## Tecnologias Utilizadas

*   **HTML5**
*   **CSS3** (com variáveis CSS e Flexbox)
*   **JavaScript** (ES6+)
*   **[Bootstrap 4.5](https://getbootstrap.com/docs/4.5/getting-started/introduction/)** (para alguns componentes e utilidades)
*   **[Font Awesome 6.5](https://fontawesome.com/v6/docs)** (para ícones)
*   **[Google Fonts](https://fonts.google.com/)** (Poppins e Open Sans)
*   **[Chart.js 3+](https://www.chartjs.org/docs/latest/)** (para o gráfico de certificados)
*   **[Chartjs Plugin Datalabels 2+](https://chartjs-plugin-datalabels.netlify.app/)** (para rótulos no gráfico)
*   **[Calendly Embed API](https://help.calendly.com/hc/en-us/articles/223147027-Embed-Calendly-on-your-website)** (para agendamento)

## Como Executar

1.  **Baixe o arquivo:** Faça o download do arquivo `index.html`.
2.  **Abra no navegador:** Dê um clique duplo no arquivo `index.html` baixado. Ele será aberto no seu navegador padrão.

Não é necessário instalar dependências ou executar um servidor local, pois todas as bibliotecas são carregadas via CDN (Content Delivery Network).

## Personalização

Para adaptar este portfólio para seu próprio uso, você precisará modificar os seguintes elementos no código `index.html`:

1.  **Informações Pessoais:**
    *   Título da página (`<title>`).
    *   Nome e logo no cabeçalho (`.logo a`).
    *   Textos das seções "Sobre Mim", "Currículo Acadêmico".
    *   Links e nomes dos projetos na seção "Projetos".
    *   Link do currículo PDF (`href` do botão em `#download-curriculo`).
    *   Links das redes sociais no `footer`.
    *   Conteúdo do gráfico de certificados (`pieLabels`, `pieData` no script).
2.  **Integrações:**
    *   **Typeform:** Substitua o `href` do botão em `#contato` pelo link do seu Typeform.
3.  **Cores:** Modifique as variáveis CSS definidas em `:root` para alterar o esquema de cores do site.
4.  **Ano no Footer:** Atualize o ano no copyright (`&copy; 2025 ESTEVAM...`) conforme necessário.


## Autor

ESTEVAM
