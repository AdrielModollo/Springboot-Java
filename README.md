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

