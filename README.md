# Method Pattern
## Objetivo
Definir o esqueleto de um algoritmo dentro de um método, transferindo alguns de seus passos para as subclasses. O Template Method permite que as subclasses redefinam certos passos de um algoritmo sem alterar a estrutura do próprio algoritmo.
## Motivação
Oferece um método que define um algoritmo (uma sequência de passos) que pode, por sua vez, ser definido como abstrato para posteriormente ser implementado por uma subclasse. Pode-se notar que a estrutura do algoritmo fica inalterada mesmo com as subclasses fazendo parte da implementação.
## Aplicabilidade
Utilize o padrão Template Method quando você quer deixar os clientes estender apenas etapas particulares de um algoritmo, mas não todo o algoritmo e sua estrutura.
Utilize o padrão quando você tem várias classes que contém algoritmos quase idênticos com algumas diferenças menores. Como resultado, você pode querer modificar todas as classes quando o algoritmo muda.
## Estrutura
![structure](https://user-images.githubusercontent.com/43156684/93686632-d63ee400-fa8d-11ea-86af-0896ab5e886e.png)
## Participantes
#### Classe Abstrata 
Declara métodos que agem como etapas de um algoritmo, bem como o próprio método padrão que chama esses métodos em uma ordem específica. Os passos podem ser declarados como abstratos ou ter alguma implementação padrão.
#### Classes Concretas 
Podem sobrescrever todas as etapas, mas não o próprio método padrão.
# Exemplo de Implementação
https://github.com/gustavokiyatake/Project-Pattern-Method/tree/master/Method/src
