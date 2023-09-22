# 🕹️ GAME


![MIT License](https://www.netfontes.com.br/clogo.php?txt=PAR%20OU%20IMPAR&ttf=wargames/wargames.ttf&cort=FFCC00&corb=000033&tamanho=100)
![MIT License](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTCV5gf42PE1y3vnqfLV3qLCpuB9FCB6BRexg&usqp=CAU)

# 💻 Maquina x Jogador 🧔🏻

## ▶️ Inicio

    programa {
       inclua biblioteca Util --> u
       funcao inicio() {
       inteiro  num, numComp, soma, resto
       caracter parImpar

    escreva("este é um jogo de par ou impar contra o computador. \n")
    escreva("se você deseja impar digite (I). Se deseja par digite (P). \n")
       leia(parImpar)

    se(parImpar == 'I'){
       escreva("Boa Sorte, você digitou um numero impar! \n")
    }
    senao se(parImpar == 'P'){
       escreva("Boa Sorte, você digitou um numero par! \n")
    }
    senao{
       escreva("Recomeçe! Voçe digitou um numero invalida! verifique se digitou corretamente. Use maiúsculas. \n")
    }

    escreva("esclolha um valor de 1 a 5! \n")
       leia(num)

    se(num <= 5){
       numComp = u.sorteia(1,5)
       escreva("O computador jogou: ", numComp, ".\n")
       soma = num + numComp
       resto = soma % 2
       se((resto == 0)e(parImpar == 'P')){
       escreva("você jogou par, com o valor: ", num, " o computador jogou impar, com o valor: ", numComp, ". você venceu! \nA soma foi ", soma,". \n")
    }
    senao se((resto == 1)e(parImpar == 'I')){
        escreva("Você jogou impar, com o valor: ", num, "o computador jogou par, com o valor: ", numComp, ". Você venceu! \nA soma foi ", soma,". \n")
    
    
    }
    senao{
        escreva("Você perdeu!")
    }
    }

  }
}


# Referência 

## Portugol-Webstudio
- https://dgadelha.github.io/Portugol-Webstudio/#share=f6pjnmt)
