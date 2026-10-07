# Portfólio dos Alunos — Projeto Base

Projeto base de portfólio pessoal feito com **HTML, CSS e JavaScript puros** (sem frameworks).
Cada aluno deve personalizar com os próprios dados.

## O que já vem pronto

- Menu responsivo (vira "hambúrguer" no celular)
- Seções: **Sobre mim**, **Habilidades**, **Projetos**, **Formação** e **Contato**
- Barras de habilidades animadas
- Link do menu destacado conforme a seção da página
- Formulário de contato com validação simples
- Layout adaptado para celular, tablet e computador

## Estrutura de pastas

```
portfolio-alunos/
├── index.html        <- conteúdo da página (edite seus dados aqui)
├── css/
│   └── style.css     <- estilos e cores
├── js/
│   └── script.js     <- menu, animações e formulário
└── README.md
```

## Como rodar no VS Code (Live Server)

1. **Baixe** o arquivo `.zip` do projeto.
2. **Extraia** o zip (botão direito > "Extrair tudo...").
3. Abra o **VS Code**.
4. Vá em **File > Open Folder** (Arquivo > Abrir Pasta) e escolha a pasta `portfolio-alunos`.
5. Instale a extensão **Live Server** (autor: Ritwick Dey):
   - Clique no ícone de extensões (`Ctrl+Shift+X`), pesquise por **Live Server** e clique em **Install**.
6. Abra o arquivo `index.html`, clique com o botão direito e escolha **Open with Live Server**
   (ou clique em **Go Live** no canto inferior direito).
7. O navegador abrirá em `http://127.0.0.1:5500`. Ao salvar um arquivo, a página atualiza sozinha.

> Dica: o projeto também funciona dando duplo clique no `index.html`, mas o Live Server é recomendado.

## Como personalizar

Tudo o que você precisa trocar está marcado por comentários no `index.html`:

| O que mudar | Onde |
|---|---|
| Nome, cargo e título | Seção `INÍCIO (HERO)` e `<title>` |
| Foto | `src` da imagem em `SOBRE MIM` (use uma imagem da pasta, ex.: `img/foto.jpg`) |
| Texto sobre você | Parágrafos em `SOBRE MIM` |
| Habilidades e níveis | `HABILIDADES`: altere o nome, o `%` e o `data-level` (os dois valores devem ser iguais) |
| Projetos | `PROJETOS`: copie um bloco `<article class="card">` para adicionar mais |
| Cursos e escolaridade | `FORMAÇÃO`: copie um bloco `timeline-item` |
| E-mail, GitHub e LinkedIn | `CONTATO` |
| Cores | `css/style.css`, bloco `:root` no topo (`--cor-primaria`, etc.) |

### Usando suas próprias imagens

1. Crie uma pasta `img/` dentro de `portfolio-alunos`.
2. Coloque suas imagens nela.
3. No `index.html`, troque o `src`, por exemplo: `src="img/foto.jpg"`.

As imagens de exemplo (placeholder) vêm da internet e precisam de conexão para aparecer.

## Desafios para praticar

- [ ] Adicionar mais um projeto com link real do GitHub
- [ ] Trocar a paleta de cores
- [ ] Criar um botão de modo escuro (dark mode)
- [ ] Enviar o formulário de verdade com [Formspree](https://formspree.io) ou [EmailJS](https://www.emailjs.com)
- [ ] Publicar o portfólio no **GitHub Pages** ou **Netlify**

Bons estudos! 🚀
