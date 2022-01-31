# Minecraft Bedrock Json-Schema
Esse é um Json-Schema ainda em desenvolvimento, para validação do complemento do Minecraft Bedrock.

## Arquivos principais
Atualmente à (dois) arquivos principais, que são eles:

- ### main.schema.json5:
    ainda não á arquivos de validação para a parte "client" dos add-on, e para grande parte dos arquivos da parte "server", mas aqui esta a pequena lista de arquivos que já tem a validação:
<b>
1. arquivos de criação de behavior de ‘items’
2. arquivos de criação de behavior de ‘blocks’
3. arquivos de criação de behavior de ’entities’
</b> 
    
- ### manifest.schema.json5
    esse arquivo é responsável por validar o manifest.json do add-on, tanto para "client" quanto para "server".
    
> Algumas propriedades no arquivo ainda não estão completas.

## Formato json5
Essa primeira versão do Json-Schema foi escrita em json5, mas também tera uma versão escrita no Json convencional. Estarei criando em ‘software’ que tera a função de validar os código dos objetos json, que sera validado usando a versão do json-schema no formato json5.

IDEs como pycharm podem usar schemas-json como para a validação de código através de intellisense para validação, e tem suportam o formato Json5.
