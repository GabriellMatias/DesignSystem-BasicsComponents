# Ignite lab [figma]
  >Atalhos
    >T >texto
    >ctrl +K Ajusta tamanho do icone sem mudar componentes em sua volta
    >R > cria um retangulo
    >A > para iniciar escolhendo o tipo de tela vc vai criar


  >da pra usar o auto layout como se fosse um display flex
  > usa um retangulo como div e coloca elementos nele, depois utiliza o auto layout como se fosse um display flex
  > colocar padding, gap etc

  >Tokens
    >seleciona a pagina e observe as cores
    >nomeie cada cor e sua tonalidade ex: gray/500
    >depois usa o plugin COLOR STYLEGUIDE [ele vai fazer um resumo de todas as cores utilizadas, sesu hexda decimais, suas categorias etc]

# React
  >storyBooks
    >ajuda a ver a aplicacao em seus mais diversoss estados
    >ver listas que nao onsegue fazer no desenvolvimento etc
    >como se fosse uma central pra entender padroes e saber quais componentes colocar em cada tela
    >documentar hisotry systems

    > Cria arq manager.js dentro de .storybooks
      >importa addons e themes da blibioteca

      SO PRA DEIXAR O STORYBOOK COM TEMA DARK, NAO A APLICACAO!!!
      import {addons} from '@storybook/addons' 
      import {themes} from '@storybook/theming'

      addons.setConfig({
        theme: themes.dark
      })

      > DEPOIS VAI EM PREVIEW.CMS
        >passa docs:{
          theme: themes.dark
        }

# CLSX
  >Criar classes do css condicionais 
  >chama a clsx no classname e passa os styles padrao como primeiro paramentro, no segundo paramentro passa um objeto com o que voce quer mudar, caso alguma variavel seja modificada etc


# Radix-UI Slot
  >

# UI/CI