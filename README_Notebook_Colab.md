# 📓 Projeto: Esboço de um Notebook Organizado no Google Colab

> Planejar a estrutura de um notebook para que qualquer pessoa, sem conhecer o projeto, consiga entender o caminho da análise do início ao fim.

---

## 📑 Sumário

1. [Sobre o projeto](#-sobre-o-projeto)
2. [Regras do desafio](#-regras-do-desafio)
3. [Prompt](#-prompt)
4. [Exemplo de esboço](#-exemplo-de-esboço)
5. [Como usar](#-como-usar)
6. [Checklist de entrega](#-checklist-de-entrega)

---

## 📌 Sobre o projeto

Imagine que alguém abrirá seu arquivo no Google Colab sem saber nada sobre o seu projeto. Será que essa pessoa conseguirá entender o caminho que você está seguindo?

Um bom notebook é organizado em partes, como uma boa história: tem **começo, meio e fim**. O desafio é pensar em como dividir o notebook para contar a análise em etapas.

> 💡 **Importante:** para realizar este desafio, utilize o link do seu projeto atual.

**Link do meu notebook/projeto:** _______________________________________

---

## 📏 Regras do desafio

| # | Regra |
|---|---|
| 1 | Criar um **esboço com os títulos das seções** do notebook |
| 2 | Pensar em **pelo menos três partes** diferentes que ajudem a guiar quem for ler |
| 3 | A estrutura deve contar a análise como uma história: **começo, meio e fim** |
| 4 | Pensar em um leitor que **não conhece nada** sobre o projeto |
| 5 | Usar o **projeto atual** como base |

---

## 🤖 Prompt

Antes de usar, preencha os campos entre `[colchetes]` com informações do seu projeto. Se o notebook tiver dados pessoais ou sensíveis, não os inclua no prompt.

````text
Atue como um mentor de análise de dados que ensina boas práticas de documentação em notebooks. Quero a sua ajuda para planejar a estrutura do meu notebook no Google Colab.

CONTEXTO
Imagine que alguém abrirá meu notebook no Google Colab sem saber nada sobre o meu projeto. Quero que essa pessoa consiga entender o caminho que estou seguindo. Um bom notebook é organizado em partes, como uma boa história, com começo, meio e fim.

SOBRE O MEU PROJETO
- Tema do projeto: [descreva em 1 ou 2 frases]
- Objetivo / pergunta que quero responder: [ex.: entender quais fatores influenciam as vendas]
- Dados utilizados: [ex.: arquivo CSV de vendas, fonte, período]
- Bibliotecas e ferramentas: [ex.: pandas, matplotlib, seaborn]
- Etapas que já fiz até agora: [ex.: carreguei os dados, limpei valores nulos, fiz alguns gráficos]
- Público que vai ler: [ex.: professor, colegas de turma, recrutadores]

O QUE EU QUERO QUE VOCÊ FAÇA
1. Crie um esboço com os títulos das seções que devo incluir no notebook.
2. Divida o esboço em, pelo menos, três partes diferentes que ajudem a guiar quem for ler (por exemplo: começo, meio e fim).
3. Para cada seção, escreva em uma ou duas frases o que deve ser explicado ou mostrado nela.
4. Indique onde usar células de texto (Markdown) e onde usar células de código.
5. Sugira onde incluir gráficos, tabelas e conclusões parciais.

REQUISITOS
- Pense em um leitor que não conhece nada sobre o projeto.
- Use títulos claros e curtos, numerados, no formato de Markdown (# Título, ## Subtítulo).
- Inclua obrigatoriamente: introdução com o objetivo, descrição dos dados, preparação/limpeza, análise, resultados e conclusão.
- Se alguma informação do meu projeto estiver faltando, faça no máximo 3 perguntas antes de criar o esboço; se for possível, crie o esboço assumindo premissas e me avise quais foram.

FORMATO DA RESPOSTA
1. O esboço do notebook em formato de lista com títulos e subtítulos.
2. Uma breve explicação de como as partes se conectam como uma história (começo, meio e fim).
3. Uma checklist de boas práticas para deixar o notebook fácil de entender (ex.: comentários no código, nomes de variáveis claros, texto explicando cada gráfico).

IMPORTANTE
Use linguagem simples, de forma que um estudante iniciante consiga entender e aplicar. Não inclua dados pessoais nem sensíveis.
````

---

## 🗂️ Exemplo de esboço

Modelo genérico, usando a divisão **começo, meio e fim**. Adapte os títulos ao seu projeto.

```markdown
# 📌 Título do Projeto

## PARTE 1: COMEÇO (Contexto)
### 1. Introdução e objetivo
### 2. Sobre os dados (fonte, período, colunas)
### 3. Importação das bibliotecas e carregamento dos dados

## PARTE 2: MEIO (Desenvolvimento)
### 4. Exploração inicial dos dados
### 5. Limpeza e preparação
### 6. Análise e visualizações
### 7. Principais descobertas parciais

## PARTE 3: FIM (Conclusão)
### 8. Resultados e conclusões
### 9. Limitações e próximos passos
### 10. Referências e fontes
```

**Como as partes se conectam:**

| Parte | Papel na história | Pergunta que responde |
|---|---|---|
| 1. Começo | Apresenta o contexto | "Do que se trata e por que importa?" |
| 2. Meio | Mostra o caminho da análise | "O que foi feito com os dados?" |
| 3. Fim | Fecha a história | "O que descobri e o que fazer agora?" |

---

## ▶️ Como usar

1. Abra o seu projeto atual no Google Colab e copie o link.
2. Preencha os campos `[entre colchetes]` do prompt com as informações do projeto.
3. Cole o prompt na IA de sua preferência e gere o esboço.
4. Crie as seções no notebook com células de texto (Markdown), usando os títulos do esboço.
5. **Revise o esboço**: adapte à realidade do seu projeto. A IA pode errar e não deve ser a única fonte.
6. Peça a um colega que abra o notebook e diga se conseguiu entender o caminho.

---

## ✅ Checklist de entrega

- [ ] Usei o link do meu projeto atual
- [ ] Criei um esboço com os títulos das seções
- [ ] O esboço tem pelo menos 3 partes diferentes
- [ ] A estrutura tem começo, meio e fim
- [ ] Cada seção tem uma explicação do que será mostrado
- [ ] Pensei em alguém que não conhece o projeto
- [ ] Revisei o esboço gerado pela IA e adaptei ao meu projeto
- [ ] Incluí este README no repositório

---

<sub>Projeto do desafio "Organizando um notebook no Google Colab". Bons estudos! 🚀</sub>
