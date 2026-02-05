🚀 Sistema Integrado: Knowledge Base, AI Prompts & Commands

<p align="center"> <img src="https://img.shields.io/badge/Status-Funcional-success?style=for-the-badge" alt="Status"> <img src="https://img.shields.io/badge/Tech-Vanilla_JS-yellow?style=for-the-badge&logo=javascript&logoColor=black" alt="Tech"> <img src="https://img.shields.io/badge/Architecture-No--Build-orange?style=for-the-badge" alt="Architecture"> <img src="https://img.shields.io/badge/License-MIT-blue?style=for-the-badge" alt="License"> </p>

<p align="center"> <strong>Uma SPA "Corporate Zen" leve e autossuficiente para produtividade máxima com fricção zero.</strong> <br /> <i>Centralize seu segundo cérebro técnico em uma interface minimalista e local-first.</i> </p>

<p align="center"> <a href="https://pedrogoessel.github.io/KnowledgeBase--Prompts--and--Commands-Manager/"><strong>Explore o Live Demo »</strong></a> </p>
📑 Sumário

    Sobre o Projeto

    Funcionalidades Principais

    Diferenciais Técnicos

    Como Utilizar

    Segurança e Privacidade

    Visual da Ferramenta

    Contribuição

📖 Sobre o Projeto

Esta Single Page Application (SPA) foi concebida para desenvolvedores e entusiastas de tecnologia que precisam organizar fluxos de trabalho sem a complexidade de bancos de dados externos. Desenvolvida puramente com tecnologias nativas, ela garante longevidade e performance instantânea diretamente no navegador.
✨ Funcionalidades Principais
📚 Gestão de Knowledge Base (KB)

    Editor Rico: Suporte nativo a Markdown e colagem direta de imagens (Ctrl+V).

    Organização Inteligente: Sistema de tags coloridas e priorização através de "Pin".

🤖 Prompt Manager

    Workflow de IA: Organize prompts complexos com formatação limpa.

    Ação Rápida: Botão de cópia instantânea para agilizar a interação com LLMs.

💻 Command Library

    Interface Terminal: Snippets de código e comandos de CLI salvos em um ambiente visual familiar.

    Acesso Rápido: Pesquisa otimizada para encontrar aquele comando esquecido em segundos.

🛠️ Diferenciais Técnicos

    Filosofia No-Build: Sem Webpack, Vite ou dependências de pacotes. Funciona hoje e funcionará daqui a uma década.

    Arquitetura de Armazenamento Híbrida:

        IndexedDB: Gerencia dados densos (blobs de imagem e textos longos).

        LocalStorage: Persiste preferências de UI e metadados leves.

    Customização Dinâmica: Suporte a Dark Mode nativo e backgrounds personalizados via CSS Variables.

🚀 Como Utilizar
Pré-requisitos

Nenhum. Apenas um navegador moderno (Chrome, Firefox, Edge, Brave).
Instalação Local

    Clone o repositório:
    Bash

    git clone https://github.com/PedroGoessel/KnowledgeBase--Prompts--and--Commands-Manager.git

    Execução: Basta abrir o arquivo index.html no seu navegador de preferência.

Backup e Portabilidade

Como a aplicação é local-first, utilize a ferramenta de Backup & Restore (JSON) integrada para mover seus dados entre diferentes máquinas ou navegadores.
🛡️ Segurança e Privacidade

    [!IMPORTANT] Privacidade Total: Seus dados nunca saem do seu computador. O processamento e armazenamento são 100% locais.

    Aviso de Cache: Limpezas agressivas de histórico/cache do navegador podem afetar o IndexedDB. Exporte seu Backup JSON regularmente para garantir a integridade dos seus dados.

📸 Visual da Ferramenta

<details> <summary>Clique para expandir os screenshots</summary> <br /> <p align="center"> <img width="100%" alt="Dashboard Preview" src="https://github.com/user-attachments/assets/5280670e-8ebd-47de-9c35-87bb28c67465" /> <img width="100%" alt="Editor Preview" src="https://github.com/user-attachments/assets/f34e7e71-0d37-4af7-b297-4148ea6d3e40" /> <img width="100%" alt="Commands Preview" src="https://github.com/user-attachments/assets/5d0a079a-8c3f-4a06-a491-3f1c34d4f589" /> </p> </details>
🤝 Contribuição e Licença

Sugestões de melhorias no CSS, otimizações no IndexedDB ou novas funcionalidades são bem-vindas.

    Faça um Fork do projeto.

    Crie uma Feature Branch (git checkout -b feature/NovaFeature).

    Dê Commit nas mudanças (git commit -m 'Add: Nova Feature').

    Faça o Push da Branch (git push origin feature/NovaFeature).

    Abra um Pull Request.

Distribuído sob a Licença MIT. Veja LICENSE para mais informações.

<p align="center">Desenvolvido com ❤️ por <a href="https://github.com/PedroGoessel">Pedro Goessel</a></p>
