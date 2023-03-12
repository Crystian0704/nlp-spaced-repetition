# Aprendizado espaçado com NLP

## Objetivo

O objetivo deste projeto é criar um sistema de aprendizado espaçado com Processamento de Linguagem Natural ou Natural Language Processing (NLP) em CLI para auxiliar o tempo ideial de recuperação de informações e consolidação do conhecimento.

## Como funciona

O sistema funciona da seguinte forma:

1. O usuário entra com uma pergunta e a resposta dessa pergunta de forma textual.
2. É adicionado no banco de dados a data de criação da pergunta e a resposta.
3. Depois de um dia programado a pergunta é apresentada ao usuário.
4. A resposta oferecida é comparada com a resposta gravada no banco de dados.
5. Se a resposta for correta, ou similar semânticamente, a pergunta é recalculada para outro dia com base na note de similaridade.
6. Para essa comparação serão usados algoritmos de similaridade de cosseno e modelos treinados no Hugging Face com transformadores.

## 

## Próximos passos

1. Atualização do algoritmo para incluir outras variáveis como: Tamanho da resposta, tempo de resposta, complexidade da pergunta, quantidade de perguntas respondidas, etc.

2. Criação de um dashboard para visualização dos dados estatísticos.

3. Treinamendo do modelo com respostas respondidas pelos usuários.

4. Criação de UI para o projeto.