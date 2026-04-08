# Apresentação João Daniel 

## Elementos conhecidos:
### Listas:
- no arquivo "randomAdviceServices";
- "advices :: [Text]" é uma função que não faz nada, apenas dá o nome para uma lista de Text
## 
### Função Lenght:
- no arquivo "randomAdviceServices";
- "index <- randomRIO (0, length advices - 1)": aqui o lenght está dando o tamanho da lista advices -1 pois a pesquisa é por ID e está começando em 0;

## 
## Novidades dos exemplos:

### função text:
### text :: Text -> ActionM ()
- essa função é do Scotty pelo "import Web.Scotty";
- ela serve para enviar uma resposta HTTP simples como texto puro ao cliente;
- a função text não trabalha com String, mas usa a variável Text e para isso precisa do "import Data.Text.Lazy (Text)";
-  https://github.com/elc117/apresentacao-bim1-2026a-Oropoc/edit/main/README.md
## 
### funções IO( ) e mundo puro/real
### a parte ( ):
- chamado unit, não tem valor relevante para retorno;
- significa uma ação que faz algo mas não retorna valor útil;
- se parece com o VOID( );
### a parte IO:
- significa que vai executar ações no mundo real;
- as funções puras do Haskell não podem ler o mundo externo
  (teclado, escrever na tela, acessar internet), e para isso que serve o IO;
- sintaxe do IO para fazer uma função pura usar o ambiente externo:
- IO coleta dados → função pura processa → IO mostra resultado;
- https://github.com/elc117/apresentacao-bim1-2026a-Oropoc/edit/main/README.md
