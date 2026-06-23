# Bloco 24 — Reformulação da Prestação de Contas (DOCX)

Reformulação da última Prestação de Contas (R$ 1.458.577,22) seguindo o padrão exigido pela **Matriz Consolidada de Entregas e Comprovação SEE/AC** (Bloco 23) e pelas orientações do **Legado Estratégico** (Bloco 22).

## Arquivos

| Arquivo | Conteúdo | Páginas |
| --- | --- | --- |
| `Relatorio_Consolidado_IDECACE_v2.docx` | Relatório principal — organizado por eixo, item, status documental e evidência. Substitui em estrutura e padrão de evidência a versão anteriormente apresentada à SEE/AC. | 17 |
| `Caderno_Simulacao_Logistica_523_2024.docx` | Documento separado — simulação detalhada do item "Logística" (R$ 44.951,23) por viagem, com vínculo NF/comprovante/finalidade educacional. | 9 |
| `*.pdf` | Versões em PDF dos mesmos documentos. | — |

## O que mudou em relação à versão anterior

1. **Conciliação numérica obrigatória** abre o relatório: 7.065 contratados / 4.243 atendidos (Of. 185) / 4.444 laudos / 6.455 cadastros sistema / 2.263 validados ASAI — em uma tabela.
2. **Estrutura por Eixo (1, 2, 3, 4, 7)** com status badge em cada item: **FATURADO E ATESTADO** / **PARCIAL A CONCILIAR** / **DISPONIBILIZADO** / **SEM ENTREGA FINAL IDENTIFICADA**.
3. **Padrão único de evidência (6 camadas)** aplicado a todos os itens: Identificação, Matriz físico-financeira, Beneficiários, Evidência material, Alterações, Validação.
4. **Eixo 7 — Pré-lançamento Grupo Q9** com a ressalva exigida pela Matriz (substituição condicionada à autorização documental).
5. **Eixo 7-B — Logística** apenas remete ao Caderno separado, não polui o relatório principal.
6. **Anexos I a IX** listados como suporte rastreável.

## Padrão visual

- A4 paisagem, margens 0,75".
- Tipografia Arial — H1 16pt, H2 13pt, H3 11pt, corpo 10pt, caption 8pt.
- Paleta teal (Hydra Teal #01696F) + neutros + 4 cores semânticas para os status.
- Tabelas com cabeçalho preenchido, linhas zebradas, sem bordas decorativas.

## Gerado por

Construção programática via `docx` (Node.js).

- Scripts: `docs-out/build_relatorio.js` e `docs-out/build_logistica.js` (não versionados — apenas os artefatos).
- Conteúdo extraído de:
  - `../Bloco-23-Matriz-Prestacao/Matriz_Consolidada_Entregas_Contrato_523_2024-SEE-DNA.pdf`
  - `../Bloco-23-Matriz-Prestacao/Relatorio-Prestacao-Contas-DNA-Acre-2.pdf`
