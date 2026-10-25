# Segundo Cérebro com NotebookLM — Desafio DIO

## Sobre o projeto

Este projeto foi desenvolvido como parte de um desafio da [DIO](https://www.dio.me/) para explorar o conceito de **segundo cérebro com inteligência artificial generativa**, utilizando o NotebookLM.

A proposta é organizar fontes de informação, interagir com a IA para sintetizar conteúdos, consultar informações com base nos materiais fornecidos e documentar os resultados obtidos.

Para demonstrar a ferramenta, escolhi **Estatística Descritiva** como tema de experimentação, pois já possuía materiais e interações anteriores com o NotebookLM. Portanto, esse assunto é o contexto utilizado no experimento, e não o objetivo principal do desafio.

## Objetivo

Demonstrar como o NotebookLM pode apoiar a organização e a consulta de conhecimento, reunindo fontes, perguntas, respostas e evidências em um repositório documentado.

## Ferramenta utilizada

- **NotebookLM:** utilizado para consultar os materiais enviados, produzir resumos, explicar conceitos e fórmulas, auxiliar na resolução de exercícios e indicar as fontes relacionadas às respostas.

## Tema utilizado na experimentação

**Estudando Estatística Descritiva.**

O tema foi escolhido livremente para demonstrar o uso da ferramenta, aproveitando materiais acadêmicos que já estavam disponíveis.

A frase acima foi definida durante a documentação do projeto, pois não havia sido registrada uma frase inicial no começo da atividade.

## Fontes utilizadas

Foram utilizados quatro arquivos PDF relacionados ao conteúdo de Estatística Descritiva.

| Arquivo | Conteúdo abordado |
|---|---|
| `estatistica_aula2.pdf` | Medidas de tendência central: média, moda e mediana; propriedades das medidas; somatório e produtório. |
| `estatistica_aula3.pdf` | Exercícios sobre medidas de tendência central e questões contextualizadas. |
| `estatistica_4.pdf` | Moda para dados agrupados em classes e medidas de dispersão, como variância, desvio padrão e coeficiente de variação. |
| `estatistica_5.pdf` | Medidas separatrizes, incluindo quartis, decis e percentis. |

### Por que essas fontes foram escolhidas?

Os PDFs já estavam disponíveis e apresentavam conteúdo organizado, adequado para testar as funcionalidades do NotebookLM.

Os materiais serviram como base para observar como a ferramenta resume documentos, explica conceitos e auxilia na resolução de exercícios. A autoria e a origem institucional devem ser verificadas nos próprios arquivos.

## Diretrizes utilizadas com o NotebookLM

Durante as interações, a ferramenta foi orientada a:

1. Resumir os conteúdos dos PDFs, identificando os principais temas.
2. Explicar conceitos e apresentar fórmulas relacionadas aos assuntos abordados.
3. Ajudar na resolução dos exercícios presentes nos materiais.
4. Utilizar os documentos fornecidos como referência e permitir a consulta das fontes indicadas nas respostas.

## Perguntas realizadas e resultados obtidos

### 1. Resumo dos PDFs

**Pergunta enviada:**

> Quero que você faça um resumo sobre os temas dos PDFs que mandei, indo da estatistica_aula2 até estatistica_5.

**Resultado:**

O NotebookLM organizou os conteúdos por assunto, identificando medidas de tendência central, exercícios de fixação, medidas de dispersão e medidas separatrizes.

**Fontes relacionadas:** `estatistica_aula2.pdf`, `estatistica_aula3.pdf`, `estatistica_4.pdf` e `estatistica_5.pdf`, conforme a organização apresentada na resposta. As citações específicas devem ser consultadas nas respostas originais e nas evidências disponíveis.

### 2. Explicação de conceitos e fórmulas

**Pergunta enviada:**

> Agora me explique sobre os temas, mostrando fórmulas.

**Resultado:**

A ferramenta explicou conceitos estatísticos e apresentou fórmulas, incluindo média aritmética simples e média ponderada.

**Média aritmética simples:**

$$
\bar{x}=\frac{\sum x_i}{n}
$$

**Média ponderada:**

$$
\bar{x}=\frac{\sum x_iw_i}{\sum w_i}
$$

Nessas expressões, \(x_i\) representa cada valor observado, \(n\) é a quantidade de observações e \(w_i\) representa o peso atribuído a cada valor.

Essas fórmulas são apresentadas como exemplos matemáticos dos conceitos abordados. A associação exata entre cada explicação e os PDFs deve ser conferida nas citações originais do NotebookLM.

### 3. Resolução dos exercícios da Aula 2

**Pergunta enviada:**

> Quero fazer os exercícios dos slides de estatistica_aula2.

**Resultado:**

O NotebookLM auxiliou na resolução de exercícios envolvendo média, mediana e distribuição de frequências.

**Exemplo — Atendimento bancário**

O enunciado utilizado na documentação informa que foram atendidos 19, 15, 17 e 21 clientes nos quatro primeiros dias, com média de 19 atendimentos ao longo de cinco dias.

Para calcular o número de atendimentos do quinto dia:

$$
\frac{19+15+17+21+n}{5}=19
$$

$$
72+n=95
$$

$$
n=23
$$

Os valores ordenados são 15, 17, 19, 21 e 23. Como há cinco observações, a mediana é o terceiro valor: **19 clientes**.

**Outro exemplo — Idades de policiais**

A resposta registrada pelo NotebookLM informou os seguintes resultados para a distribuição de idades apresentada no exercício:

- **Média:** 31 anos.
- **Moda:** 30 anos.
- **Mediana:** 30 anos.

Esses resultados devem ser conferidos no enunciado original e na resposta citada antes de serem tratados como verificados independentemente.

**Fonte relacionada:** `fontes/estatistica_aula2.pdf`.

### 4. Resolução dos exercícios da Aula 3

**Pergunta enviada:**

> Agora faça os exercícios do estatística aula 3.

**Resultado:**

O NotebookLM apresentou resoluções de exercícios gerais e questões contextualizadas. Entre os exemplos registrados estava um problema sobre remunerações em empresas, envolvendo o cálculo da média e a influência de um valor extremo (*outlier*).

**Fonte relacionada:** `fontes/estatistica_aula3.pdf`. Os enunciados, resultados completos e citações devem ser conferidos no PDF e nas respostas originais.

## Notebook compartilhado

O notebook utilizado durante a experimentação pode ser acessado pelo link abaixo:

[**Abrir o notebook no NotebookLM**](https://notebook.google.com/notebook/7862cee7-79fe-4cff-8f4b-979a85610c39)

O acesso deve ser testado em uma janela anônima para verificar se outras pessoas conseguem consultar o notebook.

## Estrutura do repositório

A estrutura publicada no GitHub inclui:

```text
NotebookLM_exerc-cio_DIO/
├── README.md
├── fontes/
│   ├── estatistica_aula2.pdf
│   ├── estatistica_aula3.pdf
│   ├── estatistica_4.pdf
│   └── estatistica_5.pdf
├── imagens/
│   └── NotebookLM Mind Map.png
└── evidencias/
    ├── print-ex3.png
    ├── print-resumo-1.png
    └── print-resumo-2.png
```

Os nomes acima correspondem aos arquivos encontrados no repositório durante a conferência.

## Evidências documentadas

A pasta `evidencias/` reúne capturas de tela das interações com o NotebookLM. A pasta `imagens/` contém o mapa mental, e a pasta `fontes/` reúne os quatro PDFs utilizados na experimentação.

Esses materiais permitem documentar o processo de interação com a ferramenta. Para facilitar a avaliação, é importante que as capturas mostrem as perguntas, as respostas e, quando disponíveis, as citações que identificam as fontes utilizadas.

## Considerações finais

O projeto permitiu explorar o NotebookLM como ferramenta de organização e consulta de conhecimento, utilizando documentos fornecidos como base para resumir informações, explicar conceitos e responder a perguntas.

A organização das fontes, o registro das interações e a documentação das evidências demonstram uma aplicação prática do conceito de segundo cérebro com IA generativa.

Embora Estatística Descritiva tenha sido o tema escolhido para a experimentação, a proposta central do projeto é documentar o processo de utilização da ferramenta e a organização do conhecimento com apoio da inteligência artificial.
