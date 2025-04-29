# Roteiro de Atividade de Pesquisa
**Disciplina**: Estrutura de Dados  
**Tema**: Balanceamento em Árvores AVL  
**Formato**: Trabalho em grupo (máx. 3 alunos)  

## Entregáveis
1. **Apresentação** (10–15 min)  
2. **Três questões de múltipla escolha** com gabarito  

---

## 1. Objetivos de Aprendizagem
- **Compreender** o que caracteriza uma árvore AVL.  
- **Explicar** como o fator de balanceamento é calculado e mantido.  
- **Descrever** e **demonstrar** as rotações simples e duplas.  
- **Analisar** o custo de inserção, remoção e busca em AVL.  
- **Aplicar** o conhecimento escrevendo questões conceituais bem‑formuladas.  

---

## 2. Organização dos Grupos
### 2.1 Formação (Dia 0)
- Autoseleção ou sorteio; máximo 3 integrantes.  
- Registrar no AVA/Canvas: nomes, RA e um e‑mail de contato do **líder**.  

### 2.2 Distribuição de Papéis  
| Papel | Responsabilidades principais |
|-------|------------------------------|
| **Pesquisador‑1** | Aprofundar a teoria (definições, propriedades). |
| **Pesquisador‑2** | Criar diagramas/figuras e reunir exemplos de aplicações. |
| **Editor** | Compilar slides, revisar linguagem e redigir as questões. |

> *Se o grupo tiver apenas 2 pessoas, rotacionem os papéis ao longo do trabalho.*

---

## 3. Linha do Tempo Recomendada
| Semana | Atividade‑chave | Entregável (checkpoint) |
|-------:|-----------------|-------------------------|
| **1** | Pesquisa bibliográfica e divisão de papéis | Lista de fontes + esboço de tópicos |
| **2** | Criação de diagramas e coleta de exemplos visuais | Pasta de recursos visuais organizada |
| **3** | Redação dos slides e das questões | Rascunho dos slides |
| **4** | Revisão cruzada entre grupos (*peer review*) | Feedback recebido ✔️ |
| **5** | Apresentação em aula + entrega final | Slides PDF + 3 MCQs |

*Ajuste conforme o calendário da turma.*

---

## 4. Etapas Detalhadas

### 4.1 Levantamento Teórico
1. **Leitura‑base**: capítulo sobre AVL em *CLRS* (Cormen), Goodrich & Tamassia ou notas da disciplina.  
2. **Pontos mínimos a cobrir**  
   - Definição de árvore balanceada e fator de balanceamento.  
   - Como o balanceamento se perde após inserção/remoção.  
   - Rotações: LL, RR, LR, RL — passo a passo.  
   - Prova (ou justificativa) de altura `O(log n)`.  
   - Comparação breve com *Red‑Black Trees* e *Treaps*.  

> **Dica**: use visualizadores online (VisuAlgo, BST‑Visualizer) para gerar GIFs ilustrativos.

### 4.2 Construção da Apresentação
- **Estrutura sugerida (≈10 slides)**  
  1. Motivação: por que balancear árvores?  
  2. Definição & propriedades.  
  3. Cálculo do fator de balanceamento.  
  4‑7. Cada rotação com diagrama “antes/depois”.  
  8. Complexidade e prova de altura.  
  9. Exemplos de uso em aplicações reais.  
  10. Conclusões + temas para estudo futuro.  

> **Boas práticas**  
> - Use fonte ≥ 18 pt para legibilidade.  
> - Prefira diagramas coloridos e animações sutis.  
> - Reserve cerca de 1 min por slide.

### 4.3 Elaboração das Questões de Múltipla Escolha
1. **Cobertura**: cada questão deve focar em **um** conceito (ex.: fator de balanceamento, rotações, complexidade).  
2. **Formato**: 4 alternativas; 1 ou mais corretas; forneça o gabarito ao final.  
3. **Qualidade**  
   - Evite “todas as alternativas acima”.  
   - Explique (em nota separada para o professor) por que cada alternativa está certa ou errada.  

---

## 5. Recursos Recomendados
- **Livros**  
  - *Introduction to Algorithms* — Cormen et al., cap. 13 (3ª ed.).  
  - *Data Structures & Algorithm Analysis* — Mark Allen Weiss.  
- **Artigos & Blogs**  
  - “How AVL Trees Keep Themselves Balanced” — *GeeksforGeeks*.  
  - Módulo interativo de AVL — *Brilliant.org*.  
- **Ferramentas**  
  - VisuAlgo (visualizador de BST/AVL).  
  - draw.io ou Excalidraw para diagramas.  
  - Google Slides, PowerPoint ou LaTeX Beamer.  

---

## 6. Dicas Pedagógicas para o Grupo
| Desafio Comum | Estratégia Sugerida |
|---------------|---------------------|
| Memorizar as quatro rotações | Crie flashcards ou diagramas comparativos (LL / RR / LR / RL). |
| Entender por que a altura é `O(log n)` | Refaça a justificativa passo a passo e discuta no grupo. |
| Dividir o trabalho de forma justa | Use um quadro Kanban (Trello/Notion) com tarefas de 2 dias. |
| Preparar boas perguntas | Teste‑as com colegas de outro grupo; refine se houver confusões. |

---

## 7. Entrega Final
- **Slides**: PowerPoint ou link editável (Google Slides/PowerPoint Online;etc).  
- **Arquivo “Questoes.pdf”**:  
  - 3 questões numeradas.  
  - Alternativas A–D.  
  - Gabarito ao final.  

### Checklist antes de enviar
- [ ] Fator de balanceamento definido claramente.  
- [ ] Todos os tipos de rotação ilustrados.  
- [ ] Questões revisadas (ortografia & coerência).  
- [ ] Referências citadas no último slide (formato ABNT ou APA).  

---

**Boa pesquisa e ótimos estudos!**
