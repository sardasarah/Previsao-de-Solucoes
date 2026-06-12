# Previsão de defeitos constatados
Sistema Inteligente de Recomendação de Soluções para Defeitos Técnicos

# # Alunos:
Sarah Costa | 2041365
Amanda Villar Moura | 2023278
Murilo Basilio Côrtes | 2066677
Felipe Ribeiro Silva |  2028059

Descrição

Este projeto consiste em um sistema de recomendação baseado em Inteligência Artificial capaz de sugerir soluções para defeitos técnicos em produtos da linha branca, como refrigeradores, lavadoras e freezers.

A partir da descrição de um defeito fornecida pelo usuário, o sistema realiza uma busca por registros semelhantes em uma base histórica de atendimentos técnicos e retorna as três soluções mais relevantes encontradas.

A solução utiliza técnicas de Processamento de Linguagem Natural (PLN), embeddings textuais e cálculo de similaridade semântica para identificar problemas semelhantes, mesmo quando descritos com palavras diferentes.

---

Objetivo

O principal objetivo deste projeto é auxiliar técnicos e profissionais de manutenção na identificação rápida de possíveis soluções para defeitos reportados por clientes, reduzindo o tempo de diagnóstico e aumentando a eficiência do atendimento.

---

Tecnologias Utilizadas

- Python
- Pandas
- NumPy
- Scikit-Learn
- Sentence Transformers
- Google Colab
- VS Code

---

Funcionamento

O fluxo do sistema ocorre da seguinte forma:

1. O usuário informa a descrição de um defeito.
2. O texto é convertido em um embedding.
3. O sistema compara o embedding informado com os embeddings dos registros da base histórica.
4. É calculada a similaridade entre os vetores.
5. Os registros mais semelhantes são identificados.
6. As três soluções mais relevantes são retornadas ao usuário.

---

Estrutura da Base de Dados

A base de dados contém registros históricos de atendimentos técnicos.

Exemplo:

Defeito| Solução
Refrigerador não gela| Substituição do termostato
Motor não liga| Troca do capacitor
Vazamento de água| Limpeza da tubulação

# Como utilizar esse projeto em sua máquina
- Garanta a instalação de todas as bibliotecas conforme or equirements
- Baixe o arquivo app.py
- Cole em algum leitor de código
- Execute o código
- Escreva "streamlit run app.py" caso esteja no VSCode no terminal
- O aplicativo será aberto em uma nova guia
