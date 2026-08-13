# Consultor Universal de Sites

Skill/prompt de consultoria estratégica para criação de sites. Cobre briefing,
estratégia, UX/UI, arquitetura, copywriting, direção de arte, SEO, prototipação
visual e desenvolvimento — em 15 etapas.

Este prompt é **agnóstico de agente**: funciona no Hermes, Claude, Codex, Cursor,
Windsurf, Aider, Gemini, ChatGPT ou qualquer agente que aceite instruções de sistema.

## O que ele faz

- Faz descoberta do negócio com UMA pergunta por vez (não sai gerando código cedo demais)
- Entrega diagnóstico estratégico, arquitetura, copy e direção de arte antes de codar
- Só gera HTML/CSS/JS após aprovação do plano
- Funciona em português (pt-BR) por padrão

## Como usar em cada ambiente

### Hermes Agent
Copie `SKILL.md` para a pasta de skills do Hermes:
- Windows: `~/AppData/Local/hermes/skills/consultor-universal-sites/SKILL.md`
- Linux/macOS: `~/.local/share/hermes/skills/consultor-universal-sites/SKILL.md`

Ou carregue via `skill_view(name="consultor-universal-sites")`.

### Claude (Claude Code / Projects / API)
- Opção A: cole o corpo de `SKILL.md` (a partir de "CONSULTOR UNIVERSAL DE SITES")
  no `CLAUDE.md` do projeto.
- Opção B: crie `.claude/skills/consultor-universal-sites/SKILL.md` e cole o conteúdo.
- Opção C (API): use como `system` prompt.

### OpenAI Codex / ChatGPT
- Use como instrução de sistema (system prompt) no início da conversa.

### Outros agentes (Cursor, Windsurf, Aider, Gemini, etc.)
- Trate o conteúdo como regras de projeto / instruções de sistema.

## Formato do arquivo

`SKILL.md` usa frontmatter YAML (name, description, version, tags, etc.) seguido do
corpo do prompt. Agentes que não entendem frontmatter (ex.: um system prompt simples)
devem ignorar a parte entre `---` e usar só o corpo.

## Licença

MIT — veja `LICENSE`.
