# Brasa Alta — Hamburgueria Artesanal

Projeto acadêmico de site institucional para uma hamburgueria artesanal, criado para a Missão Sprint 1.

## Arquivos
- `index.html`: estrutura e conteúdo do site.
- `style.css`: identidade visual, layout e responsividade.

## Como abrir no VS Code
1. Extraia o arquivo ZIP.
2. Abra a pasta `brasa_alta_hamburgueria` no Visual Studio Code.
3. Abra `index.html` no navegador. Se tiver a extensão Live Server, clique com o botão direito no arquivo e escolha **Open with Live Server**.

As fotografias e fontes são carregadas de serviços externos; é necessária conexão com a internet para exibi-las. Os textos, endereço, preços e telefone são demonstrativos e devem ser personalizados pela equipe antes da publicação.

## Fluxo Git para a Sprint
Execute os comandos dentro da pasta do repositório da equipe. Não faça commits diretamente na `main`.

```bash
git checkout main
git pull origin main
git checkout -b feature/site-hamburgueria
```

### Commit 1 — estrutura HTML
```bash
git add index.html README.md
git commit -m "Cria estrutura do site da hamburgueria"
```

### Commit 2 — estilos CSS
```bash
git add style.css
git commit -m "Adiciona identidade visual responsiva da hamburgueria"
```

### Enviar a branch
```bash
git push -u origin feature/site-hamburgueria
```

## Pull Request
No GitHub, abra um Pull Request comparando `feature/site-hamburgueria` com `main`. Inclua:
- Resumo das seções criadas (início, cardápio, história e contato).
- Captura de tela do site aberto no navegador.
- Palavra-chave `Closes #N`, substituindo N pelo número real da Issue.
- Solicitação de revisão de um colega.

Após a revisão e aprovação, faça o merge conforme as regras da equipe e exclua a branch pelo GitHub. Atualize a `main` local e teste novamente.

## Comentário sugerido para a Issue
"Meta da aula: construir a primeira versão responsiva do site da hamburgueria artesanal, com apresentação da marca, cardápio, história e contato; validar no navegador e enviar as alterações por uma feature branch para revisão."
