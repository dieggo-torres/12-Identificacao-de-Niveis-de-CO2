# [Intermediário] Identificação de Níveis de CO2
Este programa recebe um dicionário no qual cada uma de suas chaves representa um estado brasileiro. Os valores desse dicionário são listas, as quais
armazenam cinco valores cada com as leituras de cinco sensores de CO2.

Neste caso, o nível máximo de CO2 para dizer que a situção é "NORMAL" é 450. Se a média dos valores das leituras dos sensores for maior que 450, a situação
será "ALERTA".

Para identificar a situação de cada estado, o programa percorre o referido dicionário, calculando a média de CO2 para cada estado. Ao término de sua execução,
o programa exibe um relatório com a situação de cada estado.
