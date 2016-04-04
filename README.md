#Android Study Jam Salvador
##Just Java
Android Study Jam realizado em Salvador no primeiro semestre de 2016.

Aplicativo de exercício da segunda fase do curso Android Development for Beginners

##Alterações

###Operadores
Uso do Operador de Incremento:

    //quantity = quantity + 1;
    quantity++;

Uso do Operador de Decremento:

    //quantity = quantity - 1;
    quantity--;

###Correção com condicional
Inserida condicional para que o valor da quantidade somente seja reduzido se a valor atual for maior que 0.

    public void decrement(View view){
        if(quantity >0) {
            quantity--;
            display(quantity);
        }
    }
---

