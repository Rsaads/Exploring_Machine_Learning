# Reconhecimento de Imagens de Cachorros e Gatos

## Descrição do Projeto
Este projeto tem como objetivo a classificação de imagens de cachorros e gatos utilizando diferentes abordagens de aprendizado de máquina. Foram explorados modelos como Árvores de Decisão (Decision Tree), Naive Bayes e Redes Neurais Artificiais (MLP - Multi-Layer Perceptron) para avaliar o desempenho na classificação dos dados.

## Conjuntos de Dados
Os experimentos foram conduzidos utilizando dois conjuntos de imagens de cachorros das raças **Basset Hound** e **York Terrier**, e dois conjuntos de imagens de gatos das raças **Abyssinian** e **Egyptian**. Além disso, foram aplicadas técnicas de extração de características como **Histogram of Oriented Gradients (HOG)** e **Análise de Componentes Principais (PCA)**.

## Metodologia
Para cada conjunto de dados, os modelos foram treinados e avaliados com diferentes proporções de treinamento e teste (70/30, 80/20 e 90/10) e também com validação cruzada de 10 folds.

### Modelos Utilizados
1. **Decision Tree (DT)**: Foram testadas diferentes profundidades da árvore (max_depth de 3 a 10) para verificar seu impacto na acurácia do modelo.
2. **Naive Bayes (GaussianNB)**: Avaliação da acurácia utilizando divisões de treino/teste e validação cruzada.
3. **Multi-Layer Perceptron (MLP)**:
   - Teste de diferentes funções de ativação: `identity`, `logistic`, `tanh`, `relu`.
   - Teste de diferentes números de neurônios ocultos.
   - Avaliação do impacto do número de iterações no treinamento.
   - Testes com diferentes taxas de aprendizado.

## Resultados
Os resultados foram armazenados em arquivos `.csv` e `.xlsx` para posterior análise. Os gráficos foram gerados para visualizar o desempenho dos modelos em diferentes configurações, permitindo identificar quais hiperparâmetros impactam mais a classificação.

## Execução
1. Certifique-se de ter todas as bibliotecas necessárias instaladas:
   ```bash
   pip install pandas numpy matplotlib scikit-learn
   ```
2. Execute os scripts na ordem para realizar os experimentos e gerar os resultados.

## Conclusão
Este projeto permitiu comparar diferentes abordagens para classificação de imagens de cachorros e gatos, destacando a influência de diferentes métodos e hiperparâmetros no desempenho dos modelos de aprendizado de máquina.

