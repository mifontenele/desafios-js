# desafios-js


### Desafio: Crie um código que peça ao usuário para inserir os comprimentos dos três lados do triângulo e, em seguida, se é o triângulo é Equilátero, Isósceles ou Escaleno. Utilize html e JavaScript
![](/assets/triangulos_img.png)

#### Resolução: Na criação do código será necessário testar as condições abaixo:


1. Utilizar o IF para verificar se as medidas dos lados são maiores que zero e formam um triângulo

Condição   | Validação | Resultado Esperado 
:--------- | :------ | :------:
01 | lado1 > 0 && lado2 > 0 && lado3 > 0 | True
02 |( lado1 + lado2) > lado3 | True
03 |( lado2 + lado3) > lado1 | True
04 | (lado3 + lado1) > lado2 | True

2. Caso a condição do IF sejam atendidas, Utilizar o ELSE IF para identificar o tipo de triângulo, através da validação abaixo:

Tipo de Triângulo   | Validação | Resultado Esperado 
:--------- | :------ | :------:
Equilátero | lado1 === lado2 && lado2 === lado3 | True
Isóceles | lado1 === lado2 ou lado1 === lado3 ou lado2 === lado3 | True
Escaleno | se condições anteriores serem falsas | True

3. Caso a condição do IF inicial não seja atendida, não será possível formar um triângulo


