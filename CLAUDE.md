## Fluxo advisor/executor
- Antes de implementar qualquer mudança não trivial, chame um subagente com `model: opus` para planejar e revisar a abordagem.
- Execute a implementação você mesmo (modelo da sessão).
- Ao terminar, chame um subagente `model: opus` para revisar o diff e apontar bugs.
- Pule o Opus em tarefas triviais: typo, tradução, renomear, ajuste de texto.
