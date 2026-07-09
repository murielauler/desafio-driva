# Site do Desafio Driva — pré-work do Workshop de Claude Cowork

Site estático (fictício) da empresa **Driva**, usado como case de pré-work. Os participantes navegam para entender a empresa e baixam os materiais na página **Sala de Dados** para analisar no Claude Cowork.

## 👀 Pré-visualizar antes de publicar
Dê **dois cliques em `index.html`** — abre no navegador, sem instalar nada. Navegue pelo menu e teste os downloads.

## 📁 O que tem aqui
```
site-driva/
├── index.html              → Home (a cara da empresa)
├── como-funciona.html      → Planos e como funciona
├── quem-somos.html         → Personas e operação
├── sala-de-dados.html      → Briefing do desafio + downloads
├── setup.html              → Guia de setup do pré-work
├── assets/css/style.css    → Estilo (identidade Driva)
└── downloads/              → Os arquivos que os alunos baixam
    ├── driva_base_operacional.xlsx
    ├── driva_institucional.pdf
    ├── driva_diretrizes_atendimento_sla.pdf
    └── driva_ata_operacoes.pdf
```

## 🚀 Publicar no GitHub Pages (3 passos)

1. **Crie um repositório** no GitHub (ex.: `desafio-driva`), público. Faça upload de **todo o conteúdo desta pasta `site-driva`** para a raiz do repo (o `index.html` precisa ficar na raiz). Pode arrastar os arquivos direto na interface do GitHub → *Add file* → *Upload files* → *Commit*.
2. No repo, vá em **Settings › Pages**. Em *Build and deployment › Source*, escolha **Deploy from a branch**; em *Branch* selecione **main** e a pasta **/(root)**; clique **Save**.
3. Aguarde ~1 minuto. O link aparece no topo da mesma página, no formato:
   **`https://SEU-USUARIO.github.io/desafio-driva/`**

Esse é o link que você manda para a turma. 🎉

> Os links de download são **relativos** (`downloads/...`), então funcionam automaticamente no GitHub Pages sem nenhum ajuste.

## 🎨 Quer trocar algo?
- **Nome/cor:** a cor principal está no topo do `style.css` (`--teal`). O nome "Driva" está no texto das páginas.
- **Trocar um arquivo do desafio:** substitua o arquivo dentro de `downloads/` mantendo o mesmo nome, ou me peça para regenerar.

---
⚠️ **Driva é uma empresa fictícia.** Todo o conteúdo é material didático para o workshop de Claude Cowork.
