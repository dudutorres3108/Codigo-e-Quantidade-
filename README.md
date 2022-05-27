Uma lanchonete está disponibilizando para seus clientes um terminal por meio do qual poderão fazer os pedidos. Para que isso aconteça, o terminal deve exibir o menu de itens disponíveis conforme se vê a seguir:

*** Cardápio ***

100 – Hambúrguer – R$5,50

101 – Cachorro-quente – R$4,50

102 – Milkshake – R$7,00

103 – Pizza brotinho – R$8,00

104 - Cheeseburguer – R$8,50

Informe o código do seu pedido:

Uma vez que o cliente informe o código do item desejado, o terminal deverá perguntar a quantidade de itens que ele deseja pedir. Ao final, o usuário deverá informar o pedido do cliente e o valor a pagar. (CÓDIGO ABAIXO)
_______________________________________________________________________________________________________________________________________________________________________

programa

{

  funcao inicio()

  {

    inteiro codigo, qtde

    real valor=0

    cadeia item=""

    escreva("*** Cardápio ***\n")

    escreva("100 – Hambúrguer – R$5,50\n")

    escreva("101 – Cachorro-quente – R$4,50\n")

    escreva("102 – Milkshake – R$7,00\n")

    escreva("103 – Pizza brotinho – R$8,00\n")

    escreva("104 - Cheeseburguer – R$8,50\n")

    escreva("Informe o código do seu pedido: ")

    leia(codigo)

    escreva("Informe a quantidade desejada: ")

    leia(qtde)

    escolha (codigo)

    {

      caso 100:

        item="Hambúrguer"

        valor = qtde * 5.50

        pare

      caso 101:

        item="Cachorro-quente"

        valor = qtde * 4.50

        pare

      caso 102:

        item="Milkshake"

        valor = qtde * 7.00

        pare

      caso 103:

        item="Pizza brotinho"

        valor = qtde * 8.00

        pare

      caso 104:

        item="Cheeseburguer"

        valor = qtde * 8.50

        pare

      caso contrario:

        escreva("Pedido inválido!")

      }

    escreva(qtde, " x ", item, " = ", valor)

  }

}
