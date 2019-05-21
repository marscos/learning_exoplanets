# Aprendizado de Máquina - TP1
# Classificação de Exoplanetas

O trabalho tem como objetivo a prática de conceitos aprendidos na disciplina, adquirindo experiência no uso de métodos de classificação, na avaliação de modelos, e na interpretação e apresentação de resultados de experimentos. Para isso, utilizaremos e compararemos diferentes métodos para solucionar um problema de classificação binária.  

O problema abordado é o da classificação de exoplanetas identificados pela sonda espacial *Kepler* entre **confirmados** e **falsos positivos**. Os possíveis exoplanetas são chamados **Kepler Object of Interest (KOI)**, e cada observação do conjunto de dados corresponde a um KOI e suas características estimadas.

Serão explorados os seguintes métodos de classificação:
- [x] **Naive Bayes**
    - [x] Apenas um experimento, para servir de baseline.
- [x] **Decision Tree**
    - [x] Variação de altura máxima da árvore, incluindo ilimitada
    - [x] Visualização gráfica dos resultados
- [x] **SVM**
    - [x] Avaliação dos Kernels
        - [x] Linear
        - [x] Sigmoid
        - [x] Polinomial
        - [x] RBF
- [x] **k-NN**
    - [x] Variação do número de vizinhos *k*
    - [x] Visualização gráfica dos resultados
- [ ] **Random Forest**
    - [ ] Variação do número de árvores
    - [ ] Visualização gráfica dos resultados
- [ ] **Gradient Tree Boosting**
    - [ ] Variação do número de iterações
    - [ ] Visualização gráfica dos resultados