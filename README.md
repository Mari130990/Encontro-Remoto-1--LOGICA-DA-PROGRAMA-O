# Encontro-Remoto-1--LOGICA-DA-PROGRAMA-O
var  lista_pecas  =  [ "Peça 1" ,  "Peça 2" ,  "Peça 3" ,  "Peça 4" ]
var  entrada  =  janela . prompt ( "Digite o nome da peca: " )
var  peso_peca  =  parseFloat ( window . prompt ( "Digite o peso da peca: " ) )

if  ( lista_pecas . comprimento  >  10 )  {
    consola . log ( "Cadastro nao aplicado: limite maximo de pecas atingidas" )
}
senão  {
    if  ( peso_peca  <=  60 ) {
      lista_pecas . empurre ( entrada )
      consola . log ( "Cadastro bem sucedido" )
      consola . log ( lista_pecas )
    }
    senão  {
        consola . log ( "Cadastro nao aplicado: a peca excede o limite de peso" )
    }
}
