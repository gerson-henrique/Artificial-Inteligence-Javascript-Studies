## Estudos Basicos de IA.

Entrada de dados<br>
processamento de dados <br>
Saida de dados<br>

(Interligadas por pesos)<br>


Entrada * (peso) = Oculta * peso = Saida<br>

neurônio * sinapse = sinal<br>



e¹ -  h¹<br>
   x<br>
e² -  h² <br>

Exemplo de rede<br>

Entrada 1 -> peso 1-1<br>
Entrada 1 -> peso 1-2<br>

Entrada 2 -> peso 2-1<br>
Entrada 2 -> peso 2-2<br>


 (peso 1-1 * entrada 1 )  +  (peso 1-2 * entrada 2) = Oculta 1 <br>
 (peso 2-1 * entrada 1 )  +  (peso 2-2 * entrada 2) = Oculta 2 <br>


Matriciação = <br>

   -pesos-           entrada       oculta<br>
  | p11  p12 |   *  |e1 |      = |p11*e1+p12*e2| <br>
  | p21  p22 |   _  |e2 |      _ |p21*e1+p22*e2| <br>
 
           
