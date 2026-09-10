# notesgo-site

Site público oficial do NotesGO — hospedado via GitHub Pages em
`https://edsonpsantos.github.io/notesgo-site/`.

Usado inicialmente para publicar a Política de Privacidade exigida pela Google Play Console, e
futuramente para hospedar `app-ads.txt` quando a conta AdMob real for configurada.

## Conteúdo

- `index.html` — página inicial (apresentação do app + link para a Política de Privacidade)
- `privacy-policy.html` — Política de Privacidade oficial, baseada em
  `notesgo/docs/privacy-policy.md` (repositório privado do app)
- `style.css` — folha de estilo simples e responsiva, compartilhada pelas páginas

## Princípios

- HTML/CSS simples, sem frameworks, sem build step.
- Sem analytics, cookies ou trackers.
- Conteúdo em PT-BR.
- O conteúdo jurídico da Política de Privacidade reflete exatamente o documento oficial do app —
  qualquer mudança de conteúdo deve começar por `notesgo/docs/privacy-policy.md`, não por aqui.

## Pendências conhecidas

- `app-ads.txt` ainda não foi criado (depende da conta AdMob real).
