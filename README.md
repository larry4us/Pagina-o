# Pagina-o
Algoritmos implementados para a matéria de Sistemas Operacionais. Cada algoritmo é um tipo de técnica para substituição de páginas em uma memória hipotética de X frames.

Estes foram implementados usando orientação a objetos:
- Todos os algoritmos (exceto os dois de lista encadeada) são herdados da superclasse abstrata "Algoritmos".
- o FIFO é a classe base para a implementação dos outros dois, logo LRU e SegundaChance são herdados diretamente dela.
- Uma classe de lista encadeada (LinkedList.py) foi necessária para implementar LRU da maneira mais eficiente.
- Da mesma forma, uma classe de lista encadeada circular (CircularLinkedList.py) foi necessária para implementar o algoritmo de segunda chance da forma mais eficiente também.
