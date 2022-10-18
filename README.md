# Springboot-Java

### O que são webservices?

Aplicação interoperável que é hospedada e pode ser acessada através de um protocolo HTTP.

### SOAP X REST

- SOAP 

``` 
  1. Protocolo de troca de mensagens em XML
  2. Usa WSDL na comunicação entre cliente e servidor
  3. Invoca serviços através de chamadas RPC
  4. Não retorna um resultado facilmente legível para humanos
  5. Comunicação feita por HTTP mas pode usar outros protocolos como SMTP, FTP etc.
  6. Javascript pode invocar serviço SOAP, mas a implementação é complexa.
  7. Comparado com Rest sua performance não é das melhores
```

- REST

``` 
  1. Um estilo arquitetural
  2. Usa XML, JSON etc... Para enviar e receber dados
  3. Simplesmente chama serviços via URL PATH
  4. Resultado legível por humandos já que é simplesmente JSON ou XML por exemplo
  5. Comunicação feita unicamente com HTTP
  6. Fácil de invocar via Javascript
  7. Arquivos menores, e consomem menos processamento, obtendo uma melhor performance.
```

### REST (Estado representacional de transferência)

- REST é baseado em um conjunto de constraints

```
  1. Cliente-servidor (Clientes e servidores separados).
  2. Stateless server (Não deve guardar o estado do cliente)
  3. Cacheable (Cliente deve informar as propriedades cache)
  4. Interface uniforme
    4.1. Identificação de recursos (URI)
    4.2. Manipulação de recursos a partir de suas representações
    4.3. Mensagens auto descritivas
    4.4. Hypermedia as the engine of application state - HATEQAS
  5. Sistema em camadas(Suporta balanceamento de carga, proxies, firewalls)
  6. Código sob demanda (opcional)
```

### Vantagens REST

- Suporta: xml, pdf, imagens, binário, texto, json, etc...

- RESTful é um padrão arquitetura basicamente leve por natureza. Então quando você tiver limitações de banda prefira web services REST.

- Desenvolvimento fácil e rápido;

- Aplicativos mobile tem ganhado cada vez mais espaço e precisam interagir rapidamente com os servidores e o padrão REST é mais rápido no processamento de dados das requests e responses. 


### Request e Response 

```
      HTTP REQUEST
      ------------>
User       WWW      REST SERVER
      <-----------
      HTTP RESPONSE
```

### Params

```
-Params
-QueryParams
-Headers
-Body
```

### Status code

- 1xx informacionais
- 2xx Sucesso
- 3xx Redirecionamento
- 4xx Erro de client
- 5xx Erro de server

https://http.cat/

### Métodos de requisição

- GET: recupera os dados 
- POST: Criação de dados
- DELETE: Deleção de dados
- PATCH: Geralmente utilizado para atualizar dados específicos
- PUT: Geralmente utilizado para atualizado todos os dados (Idempotente)

### HATEOAS

Prove informações que permite navegar entre os endpoints de forma dinâmica. 




