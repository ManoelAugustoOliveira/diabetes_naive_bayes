# Previsão de diabetes utilizando o algoritmo de Naive Bayes.

O classificador Naive Bayes é um algoritmo que se baseia nas descobertas de Thomas Bayes para realizar predições em aprendizagem de máquina. A palavra "naive" (ingênuo) refere-se à suposição de que todas as variáveis preditivas são independentes umas das outras, ou seja, a presença de uma característica em particular não está relacionada com a presença de outra característica. Embora essa suposição raramente seja verdadeira no mundo real, o algoritmo ainda funciona bem em muitas aplicações.

Abaixo o teorema de Bayes:

*P (A |B) = P (B | A) x P (A) / P (B)*

Onde:

- P(B|A) significa a probabilidade de B acontecer já que o evento A se confirmou  
- P(A) é a probabilidade de A acontecer
- P(B) é a probabilidade de B acontecer

**Objetivo**: A tarefa de previsão é determinar se um determinado paciente está com diabetes baseado nos seus níveis de glicose e pressão arterial.
**Resultados**: O modelo estimado apresentou uma recall de 89% na identificação de pacientes com diabetes com uma precisão de 94%.
