# Memórias das reuniões do GAD

Memórias das **reuniões semanais** (quintas, **14:00 — America/Sao_Paulo**).  
Contém sumários, decisões, encaminhamentos e responsáveis.

---

## 📅 Como publicar uma nova memória (ata)

1. Crie um arquivo em `_posts/` no formato:
```

YYYY-MM-DD-reuniao-semanal.md

````

2. Use este *front matter* no início do arquivo:
```yaml
---
layout: post
title: "Reunião Semanal — DD/MM/YYYY"
date: YYYY-MM-DD 14:00:00 -0300
tags: [reunião, semanal]
---
````

3. No corpo, comece com um parágrafo-resumo (vira o *excerpt* exibido na página inicial).

   Exemplo:

```markdown
---
layout: post
title: "Reunião Semanal — DD/MM/YYYY"
date: YYYY-MM-DD 14:00:00 -0300
tags: [reunião, semanal]
---

**Resumo.**  (duas ou três linhas que viram *excerpt* na lista)

---

## Pauta
- …
- …
---

## Decisões e encaminhamentos
- …
- …
- …
---

## Ações definidas
- …
- …
- …
---

## Pendências / próximos passos
- …
- …
---

## Observações complementares
- …
- …
```

---

## ✏️ Como atualizar ou corrigir uma memória existente

1. Localize o arquivo correspondente em `_posts/`.
   O nome segue o padrão `YYYY-MM-DD-reuniao-semanal.md`.

2. Faça as modificações necessárias no texto:

   * Atualize o conteúdo de seções existentes (Resumo, Decisões, Ações…).
   * Adicione um bloco de **Atualização** no final, se for uma correção posterior:

   ```markdown
   ---
   **Atualização (DD/MM/YYYY):**
   Foi adicionada a decisão referente à nova rodada de testes do SMNA.
   ---
   ```

3. Salve, *commit* e *push*:

   ```bash
   git add _posts/2025-10-16-reuniao-semanal.md
   git commit -m "Update meeting minutes (2025-10-16): add follow-up actions"
   git push origin main
   ```

4. O site é atualizado automaticamente pelo **GitHub Pages** após o *push*.

---

## ⚙️ Publicação automática

* As memórias são publicadas via **GitHub Pages (Jekyll)** usando o tema `minima`.
* O arquivo `_config.yml` define o fuso horário, idioma e formato de data.
* O parâmetro `future: true` permite publicar reuniões com data futura próxima (ex.: da semana corrente).

perfeito 👌 — segue um **modelo completo de ata** (formato `.md`), pronto para ser copiado e renomeado toda quinta-feira.
O arquivo pode se chamar, por exemplo:
`_posts/2025-10-23-reuniao-semanal.md`

---

### 🧩 **Template padrão – `reuniao-semanal.md`**

```markdown
---
layout: post
title: "Reunião Semanal — DD/MM/YYYY"
date: YYYY-MM-DD 14:00:00 -0300
tags: [reunião, semanal]
---

**Resumo.**  
(Escreve aqui de 2 a 4 linhas resumindo os principais assuntos tratados, decisões gerais e próximos passos.  
Este texto aparece como *preview* na página inicial.)

---

## Pauta
1. [Tema 1] — breve descrição.
2. [Tema 2] — breve descrição.
3. [Tema 3] — breve descrição.

---

## Decisões e encaminhamentos
- **Decisão 1:** descrever brevemente a definição tomada.
- **Decisão 2:** se aplicável, indicar datas ou responsáveis.
- **Encaminhamento:** indicar ações derivadas.

---

## Ações definidas

### João Gerd
- [Ação 1]  
  (descrição curta e objetiva)
- [Ação 2]

### Carlos Frederico Bastarz
- [Ação 1]
- [Ação 2]

### Caroline Viezel
- [Ação 1]
- [Ação 2]

### Luiz Sapucci
- [Ação 1]
- [Ação 2]

*(adicione ou remova participantes conforme a reunião)*

---

## Pendências / próximos passos
- [Pendência 1]  
- [Pendência 2]

---

## Observações complementares
(Notas, dúvidas, sugestões de pauta futura, agradecimentos, ou registros informais.)

---

## Atualizações posteriores
*(Use esta seção quando quiser registrar complementos, revisões ou correções após a publicação.)*  
**Atualização (DD/MM/YYYY):** descrição da modificação realizada.
```

---

### 💡 **Como usar**

1. Copia esse conteúdo para um novo arquivo dentro de `_posts/`.
   Exemplo:

   ```
   _posts/2025-10-23-reuniao-semanal.md
   ```
2. Ajusta o campo `title` e `date` no *front matter*.
3. Preenche as seções conforme a reunião da semana.
4. `git add`, `commit`, `push` → o site atualiza automaticamente.

---

## ⚖️ Aviso Legal e Licenciamento

As memórias aqui publicadas têm caráter **técnico e informativo**, destinadas ao registro das discussões, decisões e encaminhamentos do **Grupo de Assimilação de Dados (GAD)** do **CPTEC/INPE**.

Todo o conteúdo textual deste repositório — incluindo atas, sumários e descrições — está licenciado sob a **Creative Commons Attribution–NonCommercial 4.0 International (CC BY-NC 4.0)**.

Isso significa que:

- O material pode ser **copiado, redistribuído e adaptado**, desde que seja dado o **crédito apropriado** ao GAD/CPTEC-INPE.  
- É **vedado o uso comercial** do conteúdo sem autorização prévia.  
- O conteúdo pode ser utilizado em apresentações, relatórios e materiais acadêmicos, desde que mantida a referência à fonte original.

> **Referência sugerida:**  
> Grupo de Assimilação de Dados (GAD) — CPTEC/INPE. *Memórias das reuniões do GAD*. Disponível em: [https://gad-dimnt-cptec.github.io/memorias-gad/](https://gad-dimnt-cptec.github.io/memorias-gad/)

© GAD/CPTEC-INPE — Uso não comercial permitido com atribuição.
