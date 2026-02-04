# 🚀 Sistema Integrado - Knowledge Base & Prompt Manager

Uma **Single Page Application (SPA)** leve e autossuficiente para gerenciamento pessoal de conhecimento, prompts de IA e comandos de terminal. Desenvolvido para rodar inteiramente no navegador, sem necessidade de servidores, banco de dados externo ou instalação complexa.

![Status do Projeto](https://img.shields.io/badge/Status-Funcional-success) ![Tecnologia](https://img.shields.io/badge/Tech-Vanilla_JS-yellow)

## ✨ Funcionalidades

* **📚 Gestão de Procedimentos (KBs):** Editor de texto rico com suporte a imagens (colar printscreen direto da área de transferência), tags coloridas e sistema de "Pin" (fixar).
* **🤖 Gerenciador de Prompts:** Organize seus melhores prompts com formatação e botão de cópia rápida.
* **💻 Biblioteca de Comandos:** Interface estilo "Terminal" para salvar snippets de código e comandos complexos.
* **🎨 UI/UX Moderna:** Design "Corporate Zen" limpo, responsivo e com **Dark Mode** automático/manual.
* **💾 Armazenamento Local Robusto:**
    * Uso de **IndexedDB** para armazenar imagens e tutoriais pesados sem travar o navegador.
    * Uso de **LocalStorage** para configurações rápidas e prompts leves.
* **📂 Backup & Restore:** Exporte e importe seus dados em formato JSON para garantir a segurança das informações.
* **🖼️ Customização:** Suporte para alteração de imagem de fundo personalizada.

## 🛠️ Tecnologias Utilizadas

O projeto foi construído com a filosofia "No-Build", ou seja, não requer compiladores (Webpack, Vite, etc). É puro código nativo:

* **HTML5 Semantic**
* **CSS3 Variables** (para temas e responsividade)
* **Vanilla JavaScript (ES6+)**
* **IndexedDB API** (Armazenamento de dados complexos)

## 🚀 Como Usar

1.  Faça o download do arquivo `index.html` (ou clone este repositório).
2.  Abra o arquivo diretamente em qualquer navegador moderno (Chrome, Edge, Firefox, Brave).
3.  Comece a cadastrar seus dados. Tudo fica salvo automaticamente no seu navegador.

> **Nota:** Como os dados ficam no navegador, lembre-se de usar o botão **"Backup"** regularmente caso precise limpar o cache ou formatar o computador.

## 📸 Screenshots

<img width="1920" height="1234" alt="image" src="https://github.com/user-attachments/assets/5280670e-8ebd-47de-9c35-87bb28c67465" />
<img width="1920" height="1411" alt="image" src="https://github.com/user-attachments/assets/f34e7e71-0d37-4af7-b297-4148ea6d3e40" />
<img width="1920" height="1172" alt="image" src="https://github.com/user-attachments/assets/5d0a079a-8c3f-4a06-a491-3f1c34d4f589" />

## 🤝 Contribuição

Sinta-se à vontade para fazer um fork e submeter Pull Requests. Sugestões de melhorias no CSS ou otimizações no IndexedDB são bem-vindas.

## 📄 Licença

Este projeto está sob a licença MIT. Sinta-se livre para usar e modificar.
