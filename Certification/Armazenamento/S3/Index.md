
[Documentação](https://aws.amazon.com/pt/s3/features/?pg=ln&sec=be)
## Principais Tópicos
-  Único objeto pode ter até 5 terabytes.
- Os objetos podem ser acessados por meio dos S3 Access Points ou diretamente pelo hostname do bucket.
-  10 pares de chave-valor chamados **tags de objetos do S3** a cada objeto.
- Inventário do S3.
- Para evitar exclusões acidentais, ative a **Exclusão da Multi-Factor Authentication (MFA)**
- Possui versionado de Objetos
## Classes de armazenamento
#### S3 Intelligent-Tiering
#### S3 Standard
#### S3 Standard-Infrequent Access (S3 Standard-IA)
#### S3 One Zone-Infrequent Access (S3 One Zone-IA)
#### S3 Glacier Instant Retrieval
#### S3 Glacier Flexible Retrieval
#### S3 Glacier Deep Archive e S3 Outposts

## Features

### [Inventário S3](https://docs.aws.amazon.com/pt_br/AmazonS3/latest/userguide/configure-inventory.html) 
- Permite gerar um relatório do conteúdo de um bucket, esse relatório é gerado em um bucket parametrizado, pode ser parametrizado uma execução automática do relatório, inclusive notificando assim que a execução é finalizada.
### S3 Object Lock
- Esse recurso de gerenciamento do S3 bloqueia a exclusão de versão de objetos durante um período de retenção definido pelo usuário para que você possa aplicar políticas de retenção como uma camada adicional de proteção de dados ou para atender a obrigações de conformidade.
### S3 Event Notifications
-  O S3 Event Notifications transcodifica automaticamente os arquivos de mídia à medida que são carregados no S3, processa os arquivos de dados à medida que ficam disponíveis e sincroniza objetos com outros armazenamentos de dados.

### S3 Storage Lens
- Proporciona visibilidade em toda a empresa para o uso do armazenamento de objetos, as tendências da atividade e faz recomendações práticas para baixar os custos e aplicar melhores práticas de proteção de dados.
- Fornece uma visão única do uso do armazenamento de objetos e da atividade em centenas, ou mesmo milhares, de contas em uma empresa, além de oferecer detalhamentos para gerar insights no nível da conta, do bucket ou mesmo do prefixo.
### S3 Storage Class Analysis
- O Amazon S3 Storage Class Analysis analisa os padrões de acesso ao armazenamento para ajudar você a decidir quando fazer a transição dos dados certos para a classe de armazenamento certa.
- É possível configurar a análise da classe de armazenamento para analisar todos os objetos em um bucket.


## Segurança e gerenciamento do acesso
