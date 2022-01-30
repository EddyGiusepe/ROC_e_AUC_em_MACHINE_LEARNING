# ROC e AUC nos modelos de MACHINE LEARNING

![image](https://user-images.githubusercontent.com/69597971/151716461-4363d1e5-d142-4c4e-b11a-945532e11702.png)


Como sabemos, em aprendizagem de máquina, a medição de desempenho é uma tarefa crucial. As métricas ``ROC`` (_Receiver Operating Characteristics_) e ``AUC`` (_Area Under The Curve_) são as mais utilizadas para medir o desempenho de modelos de classificação.



## O que que é ROC e AUC ?

``ROC`` é uma curva de probabilidade. Ela é criada traçando a **_taxa verdadeiro-positivo_** contra a **_taxa de falsos-positivos_**. Ou seja, numero de vezes que o classificador acertou a predição contra o número de vezes que o classificador errou a predição.

O ``AUC`` representa o grau ou medida de separabilidade. Quanto maior o AUC, melhor o modelo está em prever 0s como 0s e 1s como 1s. 

* Por exemplo: quanto maior a AUC, melhor o modelo está em distinguir entre pacientes com doença e pacientes sem doença.


![image](https://user-images.githubusercontent.com/69597971/151716506-ee05ef44-3bbc-4956-bd21-29ec1c2fe2af.png)

Como observamos, acima, o ROC possui dois parâmetros:

## **Taxa de verdadeiro positivo** (True Positive Rate):

que é dado por true positives/(true positives + false negatives). Essa taxa também é conhecida como sensibilidade, recordação ou probabilidade de detecção (sensitivity, recall ou probability of detection)


## **Taxa de falso positivo** (False Positive Rate):

que é dado por false positives/(false positives + true negatives). A taxa de falsos positivos também é conhecida como probabilidade de alarme falso ( fall-out or probability of false alarm) e pode ser calculada como (1 — Specificity). A Specificity (especificidade) também é conhecida como true negative rate. Por exemplo, quantas pessoas sem uma doença (true negative) foi classificadas como sadias.




















