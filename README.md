# VS Code Power Settings

Este repositório contém um `settings.json` focado em **produtividade**, **padronização de código** e **automação agressiva** para desenvolvedores que trabalham com múltiplas linguagens e projetos.

O objetivo não é estética, é **eficiência e previsibilidade**.

---

## Filosofia

- Código deve ser **legível em qualquer ambiente**
- O editor deve **corrigir erros automaticamente**
- Ferramentas > hábitos manuais
- Menos decisões repetitivas, mais foco em lógica

Este setup transforma o VS Code em uma IDE opinada.

---

## Principais Benefícios

- Padronização visual (80 colunas)
- Formatação automática por linguagem
- Imports, lint e fixes no save
- Git otimizado para fluxo profissional
- Explorer organizado e limpo
- Copilot e Chat controlados por regras
- UX fluida sem ruído visual

---

## Padronização de Código

```json
"editor.rulers": [80]
"editor.minimap.maxColumn": 80
"editor.tabSize": 2
