# `protocol` 

Documentação e definição do protocolo de autenticação utilizado pelos servidores do bloco vermelho

> [!WARNING]
> Essa versão do protocolo ainda está sendo desenvolvida.

> [!INFO]
> Status: Idealização. Nenhum servidor utiliza este protocolo ainda.

## Sobre o Protocolo v2

O protocolo atual (V1) é baseado em `JSON-RPC over HTTP/2` (o que comumente é chamado de API RESTFUL)
sem ter nenhuma garantia que a API do servidor é estável, tendo em vista que só o mod de login em uma versão
para um unico servidor a consome.

Esse repositório irá conter a especificação da API, como vários arquivos `.proto`, já que o protocolo migrará para o gRPC.
