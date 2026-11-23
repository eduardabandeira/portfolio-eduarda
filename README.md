# Portfólio Pessoal — Eduarda Porto

Portfólio estático desenvolvido originalmente para a atividade prática da disciplina **Fundamentos da Programação Web** (UNINTER), reunindo apresentação, formação, projetos e contato em página única.

🔗 **Site publicado:** https://eduardabandeira.github.io/portfolio-eduarda/

## Sobre o projeto

Single Page Website com navegação por âncoras e menu fixo, dividido em quatro seções:

- **Sobre mim** — resumo da trajetória entre pesquisa de mercado, dados e automação, com card de informações rápidas.
- **Formação** — linha do tempo de formação e cursos, além de idiomas.
- **Portfólio** — cards de projetos de dados, automação e estudo.
- **Contato** — dados de contato e formulário com validação no navegador e modal de confirmação simulada.

## Funcionalidades

- Navegação por âncoras sem recarregamento da página.
- Menu responsivo (hambúrguer) para telas menores.
- Alternância de tema claro/escuro com preferência salva no `localStorage` (e fallback para `prefers-color-scheme`).
- Validação de campos obrigatórios e formato de e-mail com feedback inline.
- Modal de confirmação na simulação de envio.

## Tecnologias

- HTML5
- CSS3 (variáveis CSS, Grid/Flexbox e media queries, sem frameworks)
- JavaScript (vanilla JS)
- GitHub Pages (publicação via GitHub Actions)

## Estrutura de arquivos

```text
portfolio-eduarda/
├── index.html      # Estrutura e conteúdo das seções
├── estilo.css      # Estilos, temas claro/escuro e responsividade
├── script.js       # Tema, menu responsivo e validação do formulário
└── README.md       # Documentação do repositório
