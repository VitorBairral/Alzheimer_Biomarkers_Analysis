## Conclusão
A partir dos testes realizados com os modelos, chegamos às seguintes métricas:

|Modelos|Métricas| |
|:-:|:-:|:-:|
| |F1-score|Acurácia|
| Baseline | 0.00 | 0.73 |
| K-nn |0.10|0.65|
| Naive Bayes |0.51|0.69|
| Random Forest | 0.68 | 0.86 |
| Regressão Logística | 0.62 | 0.80 |
| SVM | 0.72 | 0.88 |

A partir das métricas obtidas, primeiro vale ressaltar que, em métrica de f1, o modelo baseline não apresentou um limiar razoável, uma vez que qualquer modelo que apresente desempenho não nulo é preferível. Entretanto o baseline estabeleceu um limiar satisfatório em termos de acurácia, estabelecendo o mínimo de 73% para os modelos procedentes.
