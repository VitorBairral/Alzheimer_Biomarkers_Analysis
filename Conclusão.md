## Conclusão
A partir dos testes realizados com os modelos, chegamos às seguintes métricas:

|Modelos|Métricas| |
|:-:|:-:|:-:|
| | F1-score | Acurácia |
| Baseline | 0.00 | 0.73 |
| K-nn | 0.10 | 0.65 |
| Naive Bayes | 0.51 | 0.69 |
| Random Forest | 0.68 | 0.86 |
| Regressão Logística | 0.62 | 0.80 |
| SVM | 0.72 | 0.88 |

A partir das métricas obtidas, primeiro vale ressaltar que, em termos de F1-score, o modelo baseline não apresentou um limiar razoável, uma vez que qualquer modelo que apresente desempenho não nulo é preferível. Entretanto, este estabeleceu um limiar satisfatório em termos de acurácia, estipulando o mínimo de 73% para os modelos procedentes.

O modelo que apresentou melhor desempenho tanto em F1-score como em acurácia foi o SVM (Suport Vector Machine). Com valores significativamente maiores que aqueles apresentados pelo baseline, esse modelo utiliza de noções de espaço vetorial para cálculos de distância. Comparativamente, o outro modelo baseado em distância, mais simples, testado no dataset escolhido - K-nn - apresentou o pior desempenho em ambas as métricas.

Dos modelos representados neste repositório, considerou-se que, aqueles razoáveis para aplicações iniciais em detecção de risco de doeças cognitivas - em especial o alzheimer - são Regressão Logística, Random Forest e SVM, uma vez que, no mínimo, ultrapassam o limiar estabelecido pelo modelo base. Como comentado, por apresentar melhor desempenho dentre os modelos explorados, o algoritmo mais recomendado para aplicação daqueles investigados é o Suport Vector Machine.

Em aplicações reais na área da saúde, vale pontuar que é coerente aumentar o limite mínimo de desempenho de modelos para que esses sejam validados para emprego.
Sendo assim, torna-se relevante repensar as considerações de aplicabilidade de modelos muito simples de *maneira muito simples* e resultados apenas suficientemente melhores que o mínimo para problemas que impactam diretamente a vida das pessoas.
