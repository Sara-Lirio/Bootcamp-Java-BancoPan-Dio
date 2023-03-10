<h1>Collections</h1>

<img src="../../assets/Collections.png" align="right" />

<p>Collections Framework é um conjunto bem definido de interfaces e classes para 
representar e tratar grupos de dados como uma única unidade, que pode ser chamada 
coleção, ou collection.</p>


<h2>Interfaces</h2>

<p>Interfaces são tipos abstratos que representam as coleções. Permitem que coleções 
sejam manipuladas tendo como base o conceito “Programar para interfaces e não para 
implementações”, desde que o acesso aos objetos se restrinja apenas ao uso de métodos
definidos nas interfaces.</p>

<h3>Set</h3> 
<p>Interface que define uma coleção que não permite elementos duplicados.</p>

<h3>List</h3>
<p>Define uma coleção ordenada, podendo conter elementos duplicados. 
Em geral, o usuário tem controle total sobre a posição onde cada elemento 
é inserido e pode recuperá-los através de seus índices. Prefira esta interface 
quando precisar de acesso aleatório, através do índice do elemento.</p>

<h3>Queue</h3> 
<p>Um tipo de coleção para manter uma lista de prioridades, onde a ordem dos seus 
elementos, definida pela implementação de Comparable ou Comparator, determina essa 
prioridade. Com a interface fila pode-se criar filas e pilhas.</p>

<h3>Map</h3> 
<p>Mapeia chaves para valores. Cada elemento tem na verdade dois objetos: uma
chave e um valor.</p>