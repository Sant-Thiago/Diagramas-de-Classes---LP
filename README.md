## Diagramas-de-Classes---LP

<br>

> ### Classe SerVivo
>   - Método comer deve aumentar a porcentagem de vida. Tenha como base que a porcetagem de vida é igual ao peso mais um número aleatório vezes altura dividido por cem, se a porcentagem de vida for maior que 100, deve-se aumentar a sanidade com os pontos restantes.
>     
>   - Método queimar deve diminuir a porcentagem da sanidade em 3,33% se for um Fungo que não brilha ou que não é maléfico, caso contrario diminui a 80% do valor atual da sanidade e tira toda a porcentagem vital depois de 3 segundos. Em contra partida se for uma planta e for cannabis diminui a sanidade 42,0% da sanidade atual, se não, a sanidade diminui 33,4% e 10,6% da porcentagem vital.
>
>   - Método beber deve diminuir a porcentagem da sanidade em 25,0% idenpendente das diferença dos organismos, entretando, se o organismo for maléfico ou brilhante deve tirar toda a porcentagem de vida.
>
>   - Enlouquecer deve diminuir a porcentagem da sanidade inteira, aumentar o peso, diminuir porcentagem de vida aleatóriamente, sortear o genero e aumentar o peso aleatoriamente.
>
>   - Estudar a importancia mostra e retornar todas as importancias do organismo.
>   ``` javascript
>   const vitalidade = peso + random * altura / 100
>   ``` 

<br> <br>

> ### Classe Organismo
>   - Método nascer tem que dar 100% de vida.
>  
>   - Método morrer tem que zerar a vida mas acrecentar uma porcentagem aleatório de 0 a 10.
>
>   - Método aumentar vitalidade deve aumentar a vitalidade do organismo com base no número indicado no parâmetro. Enquanto o método de diminuir vitalidade o contrário;
>   ``` javascript
>   dica.forEach(metodo => metodo.isCorreto(resposta.isPensada));
>   ``` 

<br> <br>

> ### Classe Fungo
>   - Método decompor deve tirar a vitalidade de outros Organismos, deve-se tirar a porcentagem vital com porcentagens aleátorias a cada 2 segundos por 5 vezes.
>  
>   - Método fazer simbiose do organismo aumenta sua vitalidade e ao mesmo tempo tirar a mesma quantidade de porcetagem vital do organismo parasitado.
>
>   - Método infectar deve tirar 30% de vitalidade do organismo infectado, transformar o maleficio e reserva carboidrato em verdadeiro, aumentar a vitalidade do fungo em 10% e fazer o fungo brilhar;
>
>   - Método brilhar deve transformar a bioluminescencia em true e mostrar uma mensagem de "brilhando..".
>
>   - Deve-se também ter a capacidade de tirar toda a vida do ser vivo, quando a método contaminar() da interface for chamada.
>
>   - Método alimentar da interface deve aumentar a porcentagem de vida em 10% e o peso em 3kg caso não seja maléfico, se não, tire a 99% da porcentagem de vida do ser vivo e zere sua sanidade.
>
>   - Método curar se não for maléfico aumenta a altura em 3cm, atribui à porcentagem de vida 99% e sanidade uma porcentagem aleatória, caso o fungo for maléfico, diminua o peso em um número aleatório, tira uma porcentagem aleatória da porcentagem da vida e atribui à sanidade 6.659%.
>
>   - Alucinar deixa a sanidade do ser vivo em 2% a 10%, aumenta o peso em 3kg e muda o nome.
>   ``` javascript
>   while(metodoAleatorizar.exist) { showMessage("Chance de dar certo:: {100%}") }
>   ```

<br> <br>

> ### Classe Planta
> # darFruto
>   - Método deve tirar fruto(s) da planta, o número de frutos deve ser uma número aleatório de 3 até o número indicado no parâmetro.
>  
>   - Enquanto o método tira fruto(s) da planta, também deve ser um número aleatório de 0 até o valor colocado no parâmetro.
>
>   - 



>   - Deve-se também ter a capacidade de tirar toda a vida do ser vivo, quando a método contaminar() da interface for chamada.
>
>   - Método alimentar da interface deve aumentar a porcentagem de vida em 10% e o peso em 3kg caso não seja maléfico, se não, tire a 99% da porcentagem de vida do ser vivo e zere sua sanidade.
>
>   - Método curar se não for maléfico aumenta a altura em 3cm, atribui à porcentagem de vida 99% e sanidade uma porcentagem aleatória, caso o fungo for maléfico, diminua o peso em um número aleatório, tira uma porcentagem aleatória da porcentagem da vida e atribui à sanidade 6.659%.
>
>   - Alucinar deixa a sanidade do ser vivo em 2% a 10%, aumenta o peso em 3kg e muda o nome.


mata = contaminar


// programação web com java
// estrutura de dados
// engenharia de software
// programação web mobble e kotlin
// estrutura na nuvem, balanciamento de carga

