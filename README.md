# 📌 AGM Classificados

Portal web de classificados desenvolvido em **HTML, CSS, JavaScript, jQuery e Bootstrap**.  
O sistema permite anunciar e visualizar ofertas de **Carros, Imóveis, Negócios e Empregos**, com formulário modal para criar anúncios e armazenamento temporário de dados via **cookies**.

---

## 🚀 Funcionalidades

- 🏠 **Página inicial (index.html)** com navegação para todas as categorias.
- 🚗 **Carros** – Criar e visualizar anúncios de veículos.
- 🏢 **Imóveis** – Criar e visualizar anúncios de imóveis.
- 💼 **Negócios** – Publicar e consultar oportunidades de negócios.
- 👔 **Empregos** – Publicar vagas de emprego (estrutura similar às demais páginas).
- 📦 **Modal de criação de anúncios** com validação de campos.
- 🍪 **Persistência de nome do usuário** via cookies (preenchimento automático).
- 🎨 **Layout responsivo** utilizando [Bootstrap 5](https://getbootstrap.com/).

---

## 📂 Estrutura de Arquivos

/agm-classificados
│── index.html # Página inicial
│── carros.html # Página de classificados de Carros
│── imoveis.html # Página de classificados de Imóveis
│── negocios.html # Página de classificados de Negócios
│── empregos.html # Página de classificados de Empregos
│── css/
│ └── style.css # Estilos personalizados

yaml
Copiar código

---

## 🛠️ Tecnologias Utilizadas

- **HTML5**
- **CSS3**
- **Bootstrap 5.3**
- **JavaScript (ES6)**
- **jQuery 3.6**
- **Cookies para persistência de dados do usuário**

---

## ▶️ Como Executar o Projeto

1. Clone este repositório ou baixe o código:
   ```bash
   git clone https://github.com/seu-usuario/agm-classificados.git
Abra o arquivo index.html em seu navegador.

Você pode clicar duas vezes no arquivo ou utilizar uma extensão como Live Server no VS Code.

Navegue pelas categorias e crie anúncios através dos modais disponíveis.

📸 Demonstração
Página inicial
Navbar com links para categorias.

Destaques com cards de Carros, Imóveis, Negócios e Empregos.

Exemplo de Anúncio
Modal para cadastrar título, descrição, preço/investimento e nome do anunciante.

Após salvar, o anúncio é exibido em cards dinâmicos na página.

✅ Validações
Todos os campos do formulário são obrigatórios.

O preço deve ser maior ou igual a zero.

O nome do usuário é salvo em cookie e reutilizado automaticamente.

📌 Próximos Passos (Sugestões de melhoria)
Armazenamento em LocalStorage para manter anúncios entre sessões.

Integração com backend (Node.js, Spring Boot ou PHP) para salvar anúncios em banco de dados.

Sistema de autenticação de usuários.

Upload de imagens nos anúncios.

📄 Licença
Este projeto é de uso livre para estudos e pode ser modificado conforme sua necessidade.

