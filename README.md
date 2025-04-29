# 💻 Chat FURIA - Interface Estilizada com CSS

Este projeto é uma **interface front-end** desenvolvida em HTML e CSS, com foco em um design moderno e responsivo, inspirado no tema escuro da organização FURIA. Ele pode ser utilizado como base para um chatbot oficial ou como página de boas-vindas interativa.

---

## 🎨 Estilo e Layout

A interface conta com:

- 🎯 **Design escuro e gamer-friendly**, usando gradientes e sobreposição de imagem de fundo.
- 🧱 **Grid responsivo**, adaptando-se perfeitamente a diferentes tamanhos de tela.
- ✨ **Animações suaves**, como `fadeIn`, para elementos que aparecem gradualmente.
- 🔘 **Botões interativos** com transições de cor e sombra ao passar o mouse.
- 🧩 **Cards de funcionalidades** que destacam recursos do chatbot ou seções da página.

---

## 🧾 Tecnologias Utilizadas

- HTML5
- CSS3 com variáveis (`:root`) e `clamp()` para responsividade.
- Grid Layout e Flexbox para estruturação.
- Responsividade com media queries.

---


---

## 📱 Responsividade

A interface adapta-se automaticamente para:

- **Desktops e notebooks**
- **Tablets** (ex: layout 2 colunas)
- **Smartphones** (ex: layout 1 coluna + botão em tela cheia)

---

## 🖼️ Imagem de Fundo

A imagem de fundo é carregada de forma fixa, com **opacidade ajustada** para não interferir na legibilidade dos textos:

```css
body::before {
    background-image: url("https://pbs.twimg.com/media/F98rmOiWYAAFMyD?format=jpg&name=large");
    background-attachment: fixed;
    opacity: 0.2;
}


🚀 Como Usar
Clone o repositório:

git clone https://github.com/seu-usuario/LandingPage.git
Abra o arquivo index.html em qualquer navegador moderno.

Modifique os textos, funcionalidades ou imagem conforme sua necessidade.

Observação: Para que a integração com o Telegram funcione corretamente, o código do Telegram precisa estar ativo localmente. Certifique-se de rodar a aplicação para visualizar a interação completa.
