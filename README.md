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
> #### nascer()
>   - Método nascer tem que dar 100% de vida.
>
> #### morrer()
>   - Método morrer tem que zerar a vida mas acrecentar uma porcentagem aleatório de 0 a 10.
>
> #### aumentarVitalidade(Double) / diminurVitalidade(Double)
>   - Método aumentar vitalidade deve aumentar a vitalidade do organismo com base no número indicado no parâmetro. Enquanto o método de diminuir vitalidade o contrário;
>   ``` javascript
>   dica.forEach(metodo => metodo.isCorreto(resposta.isPensada));
>   ``` 

<br> <br>

> ### Classe Fungo
> #### decompor(Organismo)
>   - Método decompor deve tirar a vitalidade de outros Organismos, deve-se tirar a porcentagem vital com porcentagens aleátorias a cada 2 segundos por 5 vezes.
>
> #### fazerSimbiose(Organismo)
>   - Método fazer simbiose do organismo aumenta sua vitalidade e ao mesmo tempo tirar a mesma quantidade de porcetagem vital do organismo parasitado.
>
> #### infectar(Organismo)
>   - Método infectar deve tirar 30% de vitalidade do organismo infectado, transformar o maleficio e reserva carboidrato em verdadeiro, aumentar a vitalidade do fungo em 10% e fazer o fungo brilhar;
>
> #### brilhar()
>   - Método brilhar deve transformar a bioluminescencia em true e mostrar uma mensagem de "brilhando..".
>
> ##### atribuirImportancia(IMPORTANCIA) 
>   - Esse método adiciona importância para a lista de importância.
>
> #### contaminar()
>   - Deve-se também ter a capacidade de tirar toda a vida do ser vivo, quando a método contaminar() da interface for chamada.
>
> #### alimentar()
>   - Método alimentar da interface deve aumentar a porcentagem de vida em 10% e o peso em 3kg caso não seja maléfico, se não, tire a 99% da porcentagem de vida do ser vivo e zere sua sanidade.
>
> #### curar()
>   - Método curar se não for maléfico aumenta a altura em 3cm, atribui à porcentagem de vida 99% e diminui a sanidade em uma porcentagem aleatória, caso o fungo for maléfico, diminua o peso em um número aleatório, tira uma porcentagem aleatória da porcentagem da vida e atribui à sanidade 6.659%.
>
> #### alucinar()
>   - Alucinar deixa a sanidade do ser vivo em 2% a 10%, aumenta o peso em 3kg e muda o nome.
>   ``` javascript
>   while(metodoAleatorizar.exist) { showMessage("Chance de dar certo:: {100%}") }
>   ```

<br> <br>

> ### Classe Planta
> ##### darFruto(Integer)
>   - Método deve tirar fruto(s) da planta, o número de frutos deve ser uma número aleatório de 3 até o número indicado no parâmetro.
>
> ##### tirarFruto(Integer) 
>   - O método tira fruto(s) da planta, também deve ser um número aleatório de 0 até o valor colocado no parâmetro.
> 
> ##### atribuirImportancia(IMPORTANCIA) 
>   - Esse método adiciona importância para a lista de importância.

<br> <br>

> ### Classe Cannabis
> #### calcularDuracao()
>   - Calcular duração deve multiplicar a quantidade de gramas por floração pela porcentagem de cannabidiol, divido por 30 esse valor é a duração em dias, no entanto, caso a porcentagem de tetrahydrocannabinol seja maior que o cannabidiol deve ser divido por 60 ao invés de 30.
>
>   - Método alimentar da interface deve aumentar a porcentagem de vida em 10% e o peso em 3kg caso não seja maléfico, se não, tire a 99% da porcentagem de vida do ser vivo e zere sua sanidade.
>
>   - Método curar se não for maléfico aumenta a altura em 3cm, atribui à porcentagem de vida 99% e sanidade uma porcentagem aleatória, caso o fungo for maléfico, diminua o peso em um número aleatório, tira uma porcentagem aleatória da porcentagem da vida e atribui à sanidade 6.659%.
>
> #### contaminar()
>   - Muda o estado mental do ser vivo, ou seja, tira um número aleatório de porcentagem da sanidade do serviço, caso o peso seja maior que 35, tira do peso 17 kg, caso contrário tire um número aleatório e diminua 8% da porcentagem de vida do ser vivo.
>
> #### alimentar()
>   - Método alimentar deve aumentar a porcentagem de vida em 7% e o peso em 13kg, além de diminuir 23% da sanidade.
>
> #### curar()
>   - Método curar aumenta a altura em 4cm, atribui à porcentagem de vida 99% e diminui a sanidade aleatóriamente.
>
> #### alucinar()
>   - Alucinar deixa a sanidade do ser vivo em 2% a 4,20%, aumenta o peso em 17kg, aumenta a porcentagem da vida em 5% e muda o nome.


>   ``` javascript
>   obs() {
       if (porcentagem.atual > 100) porcentagem.atual - porcentagem.restante;
       else if (porcentagem.atual < 0) porcentagem.atual + porcentagem.restante; 
}
>   // porcentagem.restante é o valor que diminuiu mais do que zero ou que passou de 109
>   ```

mata = contaminar


// programação web com java
// estrutura de dados
// engenharia de software
// programação web mobble e kotlin
// estrutura na nuvem, balanciamento de carga

