# Segurança e Serviços

## Aba de todos os serviços 

* Computação

Acessar serviços em servidores virtuais. Cria servidores virtuais por instância. 

Lambda, oferece serviços computacionais como serveless

Amazon EC2 , permite criar e configurar servidores virtuais de acordo com a necessidade específica.

Com o EC2 , é possível configurar a quantidade de armazenamento, memória, processador e sistema operacional.

Exemplo de aplicativo que  precisa processar grandes volumes de dados. Com o EC2 é possível escalar a quantidade de processamento adicionando ou removendo instâncias de servidores virtuais conforme necessário.


* Armazenamento

Armazena os dados. S3, por exemplo

* Banco de dados

Usado para validar o acesso de um usuário por exemplo.

* Segurança, identidade e conformidade. 

Quem pode acessar ou não, e como vai ser o acesso.


# Gerenciamento de acesso

Dados são sensíveis, segurança compartilhada entre o provedor e cliente.

* Provedor 

Cuida da segurança da infraestrutura, segurança da rede, do servidor físico que armazena o dado. Back up também 

* Cliente

Cuida de quem pode acessar a conta. IAM

Em políticas , é onde permite as permissões. Define os papéis de cada usuário. Conjunto de regra de permissões.

IAM Usuário --> IAM POLÍTICAS --> IAM Grupo de usuários
                    |
IAM Usuário <--    Key  --> AWS Serviços

# Hospedar uma aplicação

Clica no site , manda requisição http e traz uma resposta. Latência mede o tempo de resposta pra solicitação. Maior a latência mais tempo demora pra carregar o site.

É preciso escolher o Data center específico



