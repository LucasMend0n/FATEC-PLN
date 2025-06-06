## Aula 11 - 02/05

### Introdução — Pipeline de Classificação de Texto

Nesta aula, foi desenvolvido um pipeline completo para a classificação de textos usando técnicas de Processamento de Linguagem Natural (PLN) e Machine Learning. O foco foi criar e treinar um modelo que identifica sentimentos em frases, utilizando pré-processamento textual e avaliação de desempenho.

---

### Tópicos abordados:

1. **Criação da base de dados**  
   - Construção de um dataset manual de frases com rótulos de sentimento positivo e negativo.

2. **Pré-processamento de dados**  
   - Limpeza dos textos: remoção de stopwords, tokenização e lematização utilizando bibliotecas como NLTK e spaCy.

3. **Vetorização dos textos**  
   - Transformação dos textos em representações numéricas usando TF-IDF.

4. **Divisão do dataset**  
   - Separação em conjuntos de treino e teste para validação do modelo.

5. **Treinamento do modelo**  
   - Uso de algoritmos como Naive Bayes para classificação dos textos.

6. **Avaliação do modelo**  
   - Aplicação de métricas como matriz de confusão, precisão, revocação e F1-score para análise de performance.

---

### Objetivo

O objetivo do notebook foi construir um pipeline robusto para a classificação de textos em categorias positivas e negativas, passando por todas as etapas de preparação, modelagem e avaliação de desempenho de modelos preditivos.

---

### Técnicas utilizadas

- Criação manual de dataset rotulado
- Pré-processamento de texto com NLTK e spaCy
- Vetorização TF-IDF
- Divisão treino/teste com Scikit-learn
- Treinamento com Naive Bayes
- Avaliação com matriz de confusão e métricas de desempenho

---

### Observações

A aula forneceu uma abordagem prática e estruturada para o desenvolvimento de pipelines de PLN voltados para tarefas de classificação de textos. O uso integrado de bibliotecas como NLTK, spaCy e Scikit-learn demonstrou a importância de combinar técnicas de pré-processamento e modelagem estatística para alcançar resultados eficazes em análise de sentimentos.
