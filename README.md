# Segundo Cérebro com NotebookLM — Desafio DIO

## Sobre o projeto

Este projeto foi desenvolvido como parte de um desafio da [DIO](https://www.dio.me/), com o objetivo de explorar o conceito de **segundo cérebro utilizando inteligência artificial generativa**, por meio do NotebookLM.

A proposta consiste em organizar fontes de informação, interagir com a IA para sintetizar conteúdos, consultar informações com base nos materiais fornecidos e documentar os resultados obtidos.

Para colocar a proposta em prática, escolhi **Estatística Descritiva** como tema de experimentação, pois já possuía materiais e interações anteriores com o NotebookLM. Portanto, o conteúdo de Estatística Descritiva é o contexto utilizado para demonstrar a ferramenta, e não o objetivo principal do desafio.

## Objetivo

Demonstrar, na prática, como o NotebookLM pode ser utilizado como uma ferramenta de apoio à organização e à consulta de conhecimento, reunindo fontes, perguntas, respostas e evidências em um repositório documentado.

## Ferramenta utilizada

- **NotebookLM:** ferramenta utilizada para consultar os materiais enviados, produzir resumos, explicar conceitos e fórmulas, auxiliar na resolução de exercícios e identificar as fontes relacionadas às respostas.

## Tema utilizado na experimentação

**Estudando Estatística Descritiva.**

Esse tema foi escolhido livremente para demonstrar o uso da ferramenta, aproveitando materiais acadêmicos que já estavam disponíveis.

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

Os PDFs foram selecionados por já estarem disponíveis e apresentarem conteúdo organizado, adequado para testar as funcionalidades do NotebookLM.

Por serem materiais didáticos relacionados à disciplina estudada, serviram como base para observar como a ferramenta resume documentos, explica conceitos e auxilia na resolução de exercícios.

A autoria e a origem institucional devem ser verificadas nos próprios documentos. As respostas da IA não foram tratadas como fontes independentes: os materiais enviados constituíram a base documental da experimentação.

## Diretrizes utilizadas com o NotebookLM

Durante a interação, a ferramenta foi orientada a:

1. Resumir os conteúdos dos PDFs, identificando os principais temas.
2. Explicar os conceitos e apresentar as fórmulas relacionadas aos assuntos abordados.
3. Ajudar na resolução dos exercícios presentes nos materiais.
4. Utilizar os documentos fornecidos como referência para as respostas, permitindo consultar as fontes indicadas pelo NotebookLM.

Essas instruções permitiram explorar diferentes formas de interação com os documentos e registrar os resultados no repositório.

## Perguntas realizadas e resultados obtidos

### 1. Resumo dos PDFs

**Pergunta enviada:**

> Quero que você faça um resumo sobre os temas dos PDFs que mandei, indo da estatistica_aula2 até estatistica_5.

**Resultado:**

O NotebookLM organizou os conteúdos dos documentos por assunto, identificando medidas de tendência central, exercícios de fixação, medidas de dispersão e medidas separatrizes.

**Fontes utilizadas:** `estatistica_aula2.pdf`, `estatistica_aula3.pdf`, `estatistica_4.pdf` e `estatistica_5.pdf`, conforme a organização apresentada na resposta. As citações individuais podem ser verificadas nas evidências registradas no repositório.

### 2. Explicação de conceitos e fórmulas

**Pergunta enviada:**

> Agora me explique sobre os temas, mostrando fórmulas.

**Resultado:**

A ferramenta explicou conceitos estatísticos e apresentou fórmulas, incluindo média aritmética simples, média ponderada e mediana para dados agrupados em intervalos de classe.

Exemplos das fórmulas registradas na resposta:

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

A resposta também abordou a moda para dados agrupados em classes e propriedades da média.

**Fontes:** os PDFs enviados ao NotebookLM. A correspondência entre cada explicação e sua fonte deve ser conferida nas citações originais e nas capturas de tela.

### 3. Resolução dos exercícios da Aula 2

**Pergunta enviada:**

> Quero fazer os exercícios dos slides de estatistica_aula2.

**Resultado:**

A ferramenta auxiliou na resolução de exercícios presentes no material, incluindo problemas envolvendo média, mediana e distribuição de frequências.

**Exemplo — Atendimento bancário**

O enunciado informa que foram atendidos 19, 15, 17 e 21 clientes nos quatro primeiros dias, com média de 19 atendimentos ao longo de cinco dias.

Para calcular o número de atendimentos do quinto dia:

\[
\frac{19+15+17+21+n}{5}=19
\]

\[
72+n=95 \Rightarrow n=23
\]

Os valores ordenados são \(15,17,19,21,23\), resultando em mediana igual a 19.

**Outro exemplo — Idades de policiais**

Na distribuição apresentada no exercício, a resposta registrada pelo NotebookLM informou:

- **Média:** 31 anos.
- **Moda:** 30 anos.
- **Mediana:** 30 anos.

**Fonte indicada:** `estatistica_aula2.pdf`. Os resultados devem ser conferidos no material original e nas evidências das respostas.

### 4. Resolução dos exercícios da Aula 3

**Pergunta enviada:**

> Agora faça os exercícios do estatística aula 3.

**Resultado:**

O NotebookLM apresentou resoluções de exercícios gerais e questões contextualizadas. Entre os exemplos registrados estava um problema sobre remunerações em empresas, envolvendo o cálculo da média e a influência de um valor extremo (*outlier*).

**Fonte indicada:** `estatistica_aula3.pdf`, conforme a resposta registrada pelo NotebookLM. As capturas de tela documentam a interação e permitem consultar as citações originais.

## Notebook compartilhado

O notebook utilizado durante a experimentação pode ser acessado pelo link abaixo:

[**Abrir o notebook no NotebookLM**](https://notebook.google.com/notebook/7862cee7-79fe-4cff-8f4b-979a85610c39)

O acesso deve ser testado em uma janela anônima para verificar se o compartilhamento permite que outras pessoas consultem o notebook.

## Estrutura do repositório

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

Os nomes apresentados são exemplos de organização. Os caminhos devem corresponder aos nomes reais dos arquivos publicados no repositório.

## Evidências documentadas

A pasta `evidencias/` reúne capturas de tela das interações com o NotebookLM, incluindo:

- resumo dos documentos enviados;
- explicações de conceitos e fórmulas;
- resolução de exercícios;
- citações que permitem identificar as fontes utilizadas nas respostas.

A pasta `imagens/` contém o mapa mental utilizado como material complementar, enquanto a pasta `fontes/` reúne os documentos empregados na experimentação.

Esses registros permitem acompanhar o processo e verificar a relação entre as perguntas realizadas, as respostas obtidas e os materiais consultados.

## Considerações finais

O projeto permitiu explorar o NotebookLM como ferramenta de organização e consulta de conhecimento, utilizando documentos fornecidos pelo usuário como base para resumir informações, explicar conceitos e responder a perguntas.

A organização das fontes, o registro das interações e a documentação das evidências demonstram uma aplicação prática do conceito de segundo cérebro com IA generativa.

Embora Estatística Descritiva tenha sido o tema escolhido para a experimentação, a proposta central do projeto é documentar o processo de utilização da ferramenta e a organização do conhecimento com apoio da inteligência artificial.
