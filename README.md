# Apresentação João Daniel 

## Novidades dos exemplos:

### função text:
### text :: Text -> ActionM ()
- essa função é do Scotty pelo "import Web.Scotty";
- ela serve para enviar uma resposta HTTP simples como texto puro ao cliente;
- a função text não trabalha com String, mas usa a variável Text e para isso precisa do "import Data.Text.Lazy (Text)"
