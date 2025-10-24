# 🚀 Alura Plus

<p align="center">
  <img src="assets/combo_principal.jpg" alt="Captura de tela da seção Combo+ do Alura Plus" width="650"/>
</p>

## 🌟 Descrição do Projeto

Este projeto é um *landing page* desenvolvido como parte do curso da Alura, focado em HTML e CSS, para simular a página de um serviço de streaming de conteúdo, o **Alura Plus**. O objetivo principal foi aplicar conceitos de _layout_ responsivo, Flexbox e estrutura semântica de código.

## 💻 Tecnologias Utilizadas

| Tecnologia | Versão | Descrição |
| :---: | :---: | :--- |
| **HTML5** | - | Estrutura e semântica do conteúdo. |
| **CSS3** | - | Estilização, layout e responsividade. |

## 💡 Demonstração do Código

Para mostrar como o projeto foi estruturado, seguem os trechos de código mais importantes do HTML e CSS.

### 📄 HTML Principal (`index.html`)

Este é o código da estrutura da página, mostrando a organização das principais seções:

```html
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Alura Plus</title>
    <link rel="stylesheet" href="style.css"> 
</head>
<body>
    <section class="container principal">
        <div class="container__caixa">
            <h1 class="container__titulo">
                Com o Combo+, você pode aproveitar o Alura+ e o Alura Língua por um preço único.
            </h1>
            <img class="container__imagem" src="[LINK DA IMAGEM DO COMBO]" alt="Combo Alura">
            <a class="container__botao" href="[LINK PARA CADASTRO]">Assine por 12x de R$ 120,00*</a>
            <a class="container__botao botao_secundario" href="[LINK PARA O PLANO BÁSICO]">Assinar somente o Alura+</a>
            <p class="container__aviso">*O preço pode variar caso a assinatura seja feita em outras plataformas.</p>
        </div>
    </section>

    <footer class="rodape">
        <img class="rodape__logo" src="[LINK DA LOGO DO RODAPÉ]" alt="Alura">
        <ul class="rodape__lista">
            </ul>
        <p class="rodape__texto">® 2024 Alura, Alura+ e Alura Língua. Todos os direitos reservados. [Seu nome]</p>
    </footer>
</body>
</html>

