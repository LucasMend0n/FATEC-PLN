## Aula 04 — 07/03 

### Extração de Características em Texto

Nesta aula, exploramos diferentes técnicas para representar textos de forma numérica, possibilitando sua utilização em algoritmos de aprendizado de máquina. O foco foi na **extração de características** (features) a partir de textos.

---

### Tópicos abordados:

1. **Bag of Words (BoW)**  
   - Representação dos documentos com base na frequência de palavras.  
   - Uso da classe `CountVectorizer` do `scikit-learn`.

2. **TF-IDF (Term Frequency - Inverse Document Frequency)**  
   - Ponderação das palavras de acordo com sua importância no corpus.  
   - Utilização da classe `TfidfVectorizer`.

3. **Word Embedding com Word2Vec**  
   - Geração de vetores semânticos para palavras.  
   - Uso da biblioteca `gensim` para treinar modelos `Word2Vec` com corpus simples.

---

### Objetivo

O notebook tem como objetivo demonstrar como transformar texto bruto em representações vetoriais que possam ser utilizadas em modelos de classificação, agrupamento ou outras tarefas de PLN.

---

### Bibliotecas utilizadas

- `scikit-learn` (`CountVectorizer`, `TfidfVectorizer`)  
- `gensim` (`Word2Vec`)

---

### Observações

Durante a aula, os alunos criaram corpus simples e visualizaram como cada técnica transforma o texto em vetores, destacando as vantagens e limitações de cada abordagem.
