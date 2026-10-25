# Segundo Cérebro: Estatística Descritiva

Projeto desenvolvido para uma atividade da [DIO](https://www.dio.me/) com o objetivo de documentar o uso do NotebookLM como apoio aos estudos de Estatística Descritiva.

## Tema e objetivo

**Tema:** Estudando Estatística Descritiva.

**Objetivo:** utilizar materiais de estudo em PDF para revisar conceitos, compreender fórmulas estatísticas e praticar a resolução de exercícios com apoio do NotebookLM, consultando as fontes utilizadas nas respostas.

## Ferramenta utilizada

- **NotebookLM:** utilizado para resumir os PDFs, explicar conceitos e fórmulas e auxiliar na resolução dos exercícios presentes nos materiais.

## Fontes utilizadas

Foram adicionados ao NotebookLM quatro PDFs relacionados ao conteúdo de Estatística Descritiva estudado na faculdade.

| Arquivo | Conteúdo abordado | Origem e confiabilidade |
|---|---|---|
| `estatistica_aula2.pdf` | Medidas de tendência central: média, moda e mediana; propriedades das medidas; somatório e produtório. | Material didático utilizado no estudo da disciplina. A captura do NotebookLM identifica o professor Mario Nobuyuki Nakashima para este arquivo. |
| `estatistica_aula3.pdf` | Exercícios sobre medidas de tendência central e questões contextualizadas, incluindo questões de exame. | Material didático utilizado no estudo da disciplina. A descrição foi identificada na resposta do NotebookLM; os dados de autoria devem ser conferidos no próprio PDF. |
| `estatistica_4.pdf` | Moda para dados agrupados em classes e medidas de dispersão, como variância, desvio padrão e coeficiente de variação. | Material didático utilizado no estudo da disciplina. Os dados de autoria devem ser conferidos no próprio PDF. |
| `estatistica_5.pdf` | Medidas separatrizes: quartis, decis e percentis; posições em distribuições ordenadas. | Material didático utilizado no estudo da disciplina. Os dados de autoria devem ser conferidos no próprio PDF. |

**Por que utilizar essas fontes:** os documentos foram selecionados por estarem diretamente relacionados ao conteúdo de Estatística Descritiva estudado na faculdade. A origem acadêmica, a autoria e a instituição responsável devem ser verificadas nas capas ou páginas iniciais dos PDFs antes da publicação final.

## Diretriz de comportamento do NotebookLM

A ferramenta foi orientada a:

1. Fazer um resumo de cada PDF, explicando os temas e as fórmulas apresentadas.
2. Ajudar a resolver e corrigir os exercícios que aparecem nos documentos.

A intenção foi usar os próprios materiais como base para revisar a matéria e acompanhar o desenvolvimento dos cálculos.

## Perguntas feitas e respostas obtidas

### 1. Resumo dos PDFs

**Pergunta enviada:**

> Quero que você faça um resumo sobre os temas dos PDFs que mandei, indo da estatistica_aula2 até estatistica_5.

**Resumo da resposta:**

O NotebookLM organizou os conteúdos por arquivo:

- **Estatística Aula 2:** medidas de tendência central, propriedades e comparação entre média, moda e mediana, além de somatório e produtório.
- **Estatística Aula 3:** exercícios de fixação sobre medidas de tendência central e questões contextualizadas.
- **Estatística 4:** métodos de cálculo da moda em classes e medidas de dispersão, incluindo variância, desvio padrão e coeficiente de variação.
- **Estatística 5:** medidas separatrizes, como quartis, decis e percentis.

**Fontes consultadas:** `estatistica_aula2.pdf`, `estatistica_aula3.pdf`, `estatistica_4.pdf` e `estatistica_5.pdf`, conforme a organização apresentada pelo NotebookLM. As citações individuais devem ser conferidas nas capturas de tela incluídas na pasta `evidencias/`.

### 2. Explicação de conceitos e fórmulas

**Pergunta enviada:**

> Agora me explique sobre os temas, mostrando fórmulas.

**Resumo da resposta:**

O NotebookLM explicou medidas de tendência central e apresentou fórmulas, incluindo:

**Média aritmética simples**

\[
\bar{x}=\frac{\sum x_i}{n}
\]

**Média ponderada**

\[
\bar{x}=\frac{\sum x_iw_i}{\sum w_i}
\]

**Mediana para dados agrupados em intervalos de classe**

\[
Md=L_{\mathrm{inf}}+
\left(\frac{E_m-FAC_{\mathrm{ant}}}{f_{\mathrm{md}}}\right)h
\]

A resposta também abordou moda para dados agrupados em classes e propriedades da média. As fórmulas acima são exemplos presentes na resposta registrada; para comprovar a correspondência exata entre cada explicação e a fonte, consulte as citações exibidas no NotebookLM e os respectivos prints.

**Fontes:** a associação precisa entre cada fórmula e o PDF citado deve ser conferida nas citações originais do NotebookLM.

### 3. Resolução dos exercícios da Aula 2

**Pergunta enviada:**

> Quero fazer os exercícios dos slides de estatistica_aula2.

**Exercício 1 — Atendimento bancário**

O enunciado informa que o gerente atendeu 19, 15, 17 e 21 clientes nos quatro primeiros dias. A média dos cinco dias foi de 19 clientes. Para encontrar o número de atendimentos do quinto dia:

\[
\frac{19+15+17+21+n}{5}=19
\]

\[
72+n=95 \Rightarrow n=23
\]

Ordenando os valores, temos \(15, 17, 19, 21, 23\). Como há cinco observações, a mediana é o terceiro valor.

**Resultado informado pelo NotebookLM:** mediana de 19 clientes.

**Exercício 2 — Idades de policiais**

O exercício apresenta uma distribuição de frequências para as idades de 85 policiais.

- **Moda:** 30 anos, a idade com maior frequência.
- **Média:** 31 anos.
- **Mediana:** 30 anos, pois a observação central está na idade de 30 anos.

**Resultados informados pelo NotebookLM:** média de 31 anos, moda de 30 anos e mediana de 30 anos.

**Fonte indicada pelo material:** `estatistica_aula2.pdf`. A captura original com as citações deve ser incluída em `evidencias/` para permitir conferir a fonte indicada pelo NotebookLM.

### 4. Resolução dos exercícios da Aula 3

**Pergunta enviada:**

> Agora faça os exercícios do estatística aula 3.

**Resumo da resposta:**

O NotebookLM apresentou uma resolução dividida em duas partes: exercícios gerais e questões contextualizadas, incluindo questões do ENEM. A captura de tela registra, por exemplo, um exercício sobre remunerações de empresas, no qual a resposta calcula a média e discute o efeito de um valor extremo (*outlier*).

**Fonte:** `estatistica_aula3.pdf`, conforme indicado na resposta do NotebookLM. Os enunciados, resultados completos e citações devem ser conferidos no PDF e nas capturas originais.

## Notebook compartilhado

**Link informado para o NotebookLM:**  
[Estudar Estatística Descritiva no NotebookLM](https://notebook.google.com/notebook/7862cee7-79fe-4cff-8f4b-979a85610c39)

O acesso deve ser testado em uma janela anônima do navegador para confirmar que o avaliador consegue abrir o notebook sem depender da sessão da conta proprietária.

## Estrutura do repositório

A estrutura sugerida para este repositório é:

```text
segundo-cerebro-estatistica-descritiva/
├── README.md
├── fontes/
│   ├── estatistica_aula2.pdf
│   ├── estatistica_aula3.pdf
│   ├── estatistica_4.pdf
│   └── estatistica_5.pdf
├── imagens/
│   └── mapa-mental.png
└── evidencias/
    ├── resumo-dos-pdfs.png
    ├── explicacao-formulas.png
    ├── exercicios-aula2.png
    └── exercicios-aula3.png
```

Os nomes das imagens são sugestões. Ao enviar os arquivos, utilize os nomes reais ou ajuste os caminhos deste README para que todos os links apontem para arquivos existentes.

## Evidências

As capturas de tela devem demonstrar:

- o resumo gerado a partir dos quatro PDFs;
- a explicação dos conceitos e fórmulas;
- as respostas aos exercícios;
- as citações do NotebookLM que permitem identificar as fontes utilizadas.

As citações são importantes para verificar se as respostas estão fundamentadas nos materiais selecionados, em vez de apenas apresentar respostas sem rastreabilidade.

## Considerações finais

Este projeto registra o uso do NotebookLM como ferramenta de apoio aos estudos de Estatística Descritiva. A atividade envolveu a organização de materiais de estudo, a síntese dos conceitos, a explicação de fórmulas e a resolução de exercícios.

A documentação das fontes e das evidências permite revisar as respostas e verificar sua relação com os documentos consultados. O projeto poderá ser ampliado com novos exercícios, materiais e registros de uso da ferramenta.
