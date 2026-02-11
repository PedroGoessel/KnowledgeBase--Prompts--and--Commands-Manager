<p align="center">
</p> <h1 align="center">🚀 Sistema Integrado: NOC, Prompts, KBs & Commands</h1> <p align="center">

<div align="center">

![Version](https://img.shields.io/badge/version-1.0.0-blue.svg)
![License](https://img.shields.io/badge/license-MIT-green.svg)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)

**Sistema completo para gerenciamento de operações de NOC (Network Operations Center)**

[Demo](#) · [Reportar Bug](../../issues) · [Solicitar Feature](../../issues)

</div>

---

## 📋 Sobre o Projeto

O **Sistema Integrado NOC** é uma aplicação web moderna e completa desenvolvida para profissionais de TI, equipes de NOC e administradores de sistemas. Com uma interface intuitiva e recursos poderosos, o sistema facilita o gerenciamento de rotinas diárias, documentação técnica, e geração de relatórios operacionais.

### ✨ Destaques

- 🎯 **100% Client-Side** - Funciona sem servidor, todos os dados ficam no navegador
- 🌓 **Modo Escuro/Claro** - Interface adaptável com temas elegantes
- 📱 **Totalmente Responsivo** - Funciona perfeitamente em desktop, tablet e mobile
- 💾 **LocalStorage** - Seus dados permanecem salvos localmente
- 🔒 **Privacidade Total** - Nenhum dado é enviado para servidores externos
- ⚡ **Performance** - Interface rápida e fluida
- 🎨 **Design Moderno** - Interface limpa seguindo princípios de UX/UI

---

## 🎯 Funcionalidades Principais

### 📝 Gerenciador de Prompts
- ✅ Criação e organização de prompts reutilizáveis
- ✅ Sistema de fixação para acesso rápido
- ✅ Editor de texto rico com formatação
- ✅ Busca e filtro de prompts
- ✅ Exportação/Importação de dados

### 📚 Base de Conhecimento de Tutoriais
- ✅ Sistema completo de tutoriais técnicos
- ✅ Organização por tags personalizáveis
- ✅ Editor rico com suporte a imagens
- ✅ Sistema de fixação de tutoriais importantes
- ✅ Lightbox para visualização de imagens
- ✅ Busca avançada por título ou tags

### 💻 Comandos
- ✅ Biblioteca de comandos frequentes
- ✅ Categorização por tipo de comando
- ✅ Cópia rápida com um clique
- ✅ Sistema de busca integrado
- ✅ Edição e personalização de comandos

### 📊 Sistema de Relatórios NOC
- ✅ Gerenciamento de clientes
- ✅ Cadastro de rotinas de backup/monitoramento
- ✅ Geração automática de relatórios
- ✅ Verificação de status (OK, ERRO, NÃO EXECUTA)
- ✅ Período customizável de análise
- ✅ Sistema de tickets integrado
- ✅ Ordenação manual ou alfabética
- ✅ Cópia rápida de relatórios formatados

---

## 🚀 Começando

### Pré-requisitos

Você só precisa de um navegador web moderno:
- Google Chrome (recomendado)
- Firefox
- Safari
- Edge

### Instalação

1. Clone o repositório:
```bash
git clone https://github.com/seu-usuario/sistema-integrado-noc.git
```

2. Navegue até o diretório:
```bash
cd sistema-integrado-noc
```

3. Abra o arquivo `index.html` no seu navegador favorito:
```bash
# No Windows
start index.html

# No macOS
open index.html

# No Linux
xdg-open index.html
```

Ou simplesmente arraste o arquivo `index.html` para o navegador!

---

## 📖 Como Usar

### Gerenciador de Prompts

1. **Criar um Prompt**
   - Clique na aba "Prompts"
   - Preencha o título do prompt
   - Use o editor rico para adicionar o conteúdo
   - Clique em "Adicionar Prompt"

2. **Fixar um Prompt**
   - Clique no ícone de 📌 ao lado do prompt
   - Prompts fixados aparecem no topo da lista

3. **Copiar um Prompt**
   - Clique no botão "Copiar" ao lado do prompt
   - O conteúdo será copiado para a área de transferência

### Sistema de Relatórios NOC

1. **Adicionar um Cliente**
   - Na aba "Relatórios", digite o nome do cliente
   - Clique em "Adicionar Cliente"

2. **Cadastrar Rotinas**
   - Selecione o cliente
   - Adicione o número e nome da rotina
   - Clique em "Adicionar Rotina"

3. **Gerar Relatório**
   - Selecione a data (ou período)
   - Defina o status de cada rotina (0=OK, 1=ERRO, 10=NÃO EXECUTA)
   - Clique em "Gerar Relatório"
   - Use "Copiar Texto" para copiar o relatório

### Tutoriais

1. **Criar Tutorial**
   - Vá para a aba "Tutoriais"
   - Digite o título
   - Adicione tags para organização
   - Use o editor rico para o conteúdo
   - Cole imagens diretamente no editor (Ctrl+V)

2. **Buscar Tutoriais**
   - Use o campo de busca no topo
   - Filtre por tags específicas
   - Busque por palavras-chave no título

---

## 🎨 Personalização

### Temas

O sistema oferece dois temas visuais:
- **Modo Claro**: Interface clean e profissional
- **Modo Escuro**: Perfeito para trabalho noturno ou ambientes com pouca luz

Alterne entre os modos clicando no botão 🌓 no topo da página.

### Papel de Parede

1. Clique no botão "Trocar Papel de Parede"
2. Selecione uma imagem do seu computador
3. A imagem será salva localmente e aplicada como fundo

---

## 💾 Exportação e Importação de Dados

### Exportar Dados
- Cada seção possui um botão "Exportar"
- Gera um arquivo JSON com todos os dados
- Útil para backup ou transferência entre dispositivos

### Importar Dados
- Use o botão "Importar" em cada seção
- Selecione o arquivo JSON exportado anteriormente
- Os dados serão restaurados automaticamente

---

## 🛠️ Tecnologias Utilizadas

- **HTML5** - Estrutura semântica e moderna
- **CSS3** - Estilização avançada com variáveis CSS
- **JavaScript (Vanilla)** - Lógica da aplicação
- **LocalStorage API** - Persistência de dados
- **IndexedDB** - Armazenamento de imagens dos tutoriais
- **Google Fonts** - Tipografia (Inter & Fira Code)
- **ContentEditable API** - Editores de texto rico

---

## 📂 Estrutura do Projeto

```
sistema-integrado-noc/
│
├── index.html          # Arquivo principal (aplicação completa)
└── README.md           # Documentação do projeto
```

---

## 🔧 Funcionalidades Técnicas

### Armazenamento de Dados

O sistema utiliza duas APIs para armazenamento:

1. **LocalStorage**: Para dados textuais (prompts, comandos, relatórios)
2. **IndexedDB**: Para armazenamento de imagens dos tutoriais

### Segurança

- Sanitização de HTML para prevenir XSS
- Validação de valores CSS personalizados
- Nenhuma comunicação externa

### Performance

- Carregamento lazy de imagens
- Debounce em operações de busca
- Otimização de re-renderização

---

## 🤝 Contribuindo

Contribuições são sempre bem-vindas! Se você tem sugestões para melhorar este projeto:

1. Faça um Fork do projeto
2. Crie uma Branch para sua Feature (`git checkout -b feature/NovaFeature`)
3. Commit suas mudanças (`git commit -m 'Adiciona nova feature'`)
4. Push para a Branch (`git push origin feature/NovaFeature`)
5. Abra um Pull Request

---

## 📝 Roadmap

- [ ] Exportação de relatórios em PDF
- [ ] Sistema de backup automático
- [ ] Integração com APIs de monitoramento
- [ ] Modo de visualização em grid
- [ ] Sistema de notificações
- [ ] Suporte a múltiplos idiomas
- [ ] PWA (Progressive Web App)
- [ ] Sincronização em nuvem opcional

---

## 📄 Licença

Este projeto está sob a licença MIT. Veja o arquivo `LICENSE` para mais detalhes.

---

## 👤 Autor

**Pedro Goessel**

- Github: [@PedroGoessel](https://github.com/PedroGoessel/)
- LinkedIn: [@pedrogoessel](https://www.linkedin.com/in/pedrogoessel/)

---

<div align="center">

**⭐ Se este projeto foi útil para você, considere dar uma estrela!**

</div>
