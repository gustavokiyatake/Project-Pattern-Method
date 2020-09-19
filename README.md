# Method Pattern
## Objetivo
Definir o esqueleto de um algoritmo dentro de um método, transferindo alguns de seus passos para as subclasses. O Template Method permite que as subclasses redefinam certos passos de um algoritmo sem alterar a estrutura do próprio algoritmo.
## Morivação
Oferece um método que define um algoritmo (uma sequência de passos) que pode, por sua vez, ser definido como abstrato para posteriormente ser implementado por uma subclasse. Pode-se notar que a estrutura do algoritmo fica inalterada mesmo com as subclasses fazendo parte da implementação.
