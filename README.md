# Apresentação João Daniel 

## Novidades dos exemplos:

### função text:
### text :: Text -> ActionM ()
- essa função é do Scotty pelo "import Web.Scotty";
- ela serve para enviar uma resposta HTTP simples como texto puro ao cliente;
- a função text não trabalha com String, mas usa a variável Text e para isso precisa do "import Data.Text.Lazy (Text)";
## 
### funções IO( ) e mundo interno/externo
### a parte ( ):
- significa uma ação que faz algo mas não retorna valor útil;
- se parece com o VOID( );
### a parte IO:
