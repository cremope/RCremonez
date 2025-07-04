# RCremonez

Este projeto foi criado com o objetivo de servir como aplicação web base para testes automatizados

Ele simula um fluxo simples de autenticação com validação de campos, e redirecionamento para uma página inicial após o login.

---

## 🔗 Acesso ao projeto publicado no GitHub Pages

> Acesse a página de login clicando no link abaixo:

👉 [https://cremope.github.io/RCremonez/](https://cremope.github.io/RCremonez/)

---

## 📄 Páginas disponíveis

### `index.html`
Página de login com validação:

- Validação de campos obrigatórios.
- Validação de formato de e-mail.
- Verificação de credenciais:
    - Usuário válido: `admin@teste.com`
    - Senha válida: `teste`

Mensagens específicas são exibidas em caso de erro (usuário inválido, senha inválida, ou ambos).

### `home.html`
Página inicial acessível apenas após o login bem-sucedido.

- Exibe mensagem de boas-vindas.
- Contém um link para **sair** e retornar à página de login.

---

## 🎯 Finalidade

Esta aplicação será utilizada como base para:

- Escrita de cenários de teste automatizados.
- Execução em pipeline com GitHub Actions.
- Publicação de relatórios em GitHub Pages.

---

## 📦 Tecnologias utilizadas

- HTML5
- CSS3
- JavaScript (puro)
- GitHub Pages

---