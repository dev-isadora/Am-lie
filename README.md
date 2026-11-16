# Amélie

Sistema para monitoramento de aproveitamento estudantil.

- Vários cadernos (um por objetivo), disciplinas com peso, domínio e tópicos
- Registro de sessões de estudo, questões e acertos
- Painel com meta semanal, conteúdo coberto, taxa de acerto e sequência de dias
- Sugestão do que estudar agora e revisão espaçada (1, 7 e 30 dias)
- Cronograma semanal automático
- Backup: exportar e restaurar os dados em JSON

É uma página única (`index.html`), sem build e sem dependências. Os dados ficam no navegador (localStorage).
Aberta pelo Claude (claude.ai), ganha sincronização na conta e a mentora com IA.

## Publicar no GitHub Pages

Settings → Pages → Source: *Deploy from a branch* → Branch: `main`, pasta `/ (root)`.
