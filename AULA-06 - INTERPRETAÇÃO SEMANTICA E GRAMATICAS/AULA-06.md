## Aula 06 - 21/03

### Introdução — Interpretação Semântica e Uso de Gramáticas

Nesta aula, trabalhamos conceitos de interpretação semântica e estruturas gramaticais, aplicando técnicas de Processamento de Linguagem Natural (PLN) com Python. A proposta foi entender como a semântica pode ser extraída e estruturada a partir de um texto, utilizando recursos como NLTK e gramáticas formais.

---

### Tópicos abordados:

1. **Criação de gramáticas com NLTK**  
   - Definição de gramáticas livres de contexto para analisar sentenças em português.  
   - Uso da ferramenta `CFG` (Context-Free Grammar) da NLTK.

2. **Parsing de frases com `ChartParser`**  
   - Interpretação estrutural de frases com base em uma gramática definida.  
   - Construção e visualização de árvores sintáticas.

3. **Semântica computacional**  
   - Introdução à construção de significado em frases.  
   - Uso da classe `DrtExpression` da biblioteca NLTK para modelagem semântica.

4. **Tradução de sentenças para expressões semânticas**  
   - Conversão de estruturas gramaticais em representações lógicas de significado.  
   - Aplicação de lambda calculus para interpretação de frases.

5. **Construção de árvores de análise**  
   - Geração e visualização de árvores sintáticas e semânticas.  
   - Manipulação de árvores com `Tree` do NLTK.

---

### Objetivo

O notebook tem como objetivo demonstrar como frases simples em linguagem natural podem ser analisadas gramatical e semanticamente usando ferramentas da NLTK. Com isso, é possível iniciar a modelagem de significado de sentenças, um passo importante para tarefas mais avançadas de PLN.

---

### Técnicas utilizadas

- Definição de gramáticas livres de contexto (CFG)  
- Análise sintática com `ChartParser`  
- Visualização de árvores com `Tree`  
- Representação semântica com `DrtExpression` e `DrtParser`  
- Aplicação de lambda calculus na modelagem de significado

---

### Observações

Foi utilizado um conjunto pequeno de sentenças como base, com o propósito de mostrar o funcionamento das ferramentas de análise sintática e semântica. O conteúdo prepara o terreno para o uso de gramáticas formais mais complexas e interpretações semânticas aplicadas em contextos reais.
