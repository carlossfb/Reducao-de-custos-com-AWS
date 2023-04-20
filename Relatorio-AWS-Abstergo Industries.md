# RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS

Data: 19 de abril de 2023
Empresa: Abstergo Industries 
Responsável: Carlos Eduardo Freire Batista da Silva.

## Introdução
Este relatório apresenta o processo de implementação de ferramentas na empresa Abstergo Industries , realizado por Carlos Eduardo Freire Batista da Silva. O objetivo do projeto foi elencar 3 serviços AWS, com a finalidade de realizar diminuição de custos imediatos.

## Descrição do Projeto
O projeto de implementação de ferramentas foi dividido em 3 etapas, cada uma com seus objetivos específicos. A seguir, serão descritas as etapas do projeto:

Etapa 1: 
- Elastic Beanstalk
- Permite a implantação de aplicativos suprindo e evitando custos relacionados com criação e manutenção de infraestruturas.
- A aplicação que hoje é mantida por um servidor local para acesso a todas informações referentes a estoque e venda será movida para nuvem, com alta disponibilidade e tolerância a falhas, excluindo a necessidade de manter a manutenção do ambiente on premise.

Etapa 2: 
- Amazon S3 Glacier
- Armazenamento de dados
- Farmácias precisam manter documentações como receituários por um período mínimo, de acordo com os Procedimentos Operacionais Padrão (POPs), para tal, permitindo acesso a baixo custo em documentos que não terão acesso frequente e ainda sim permitindo uma disponibilidade para que possa recuperar os dados, podemos usar o Glacier, assim esses documentos terão alta durabilidade a pouco custo.

Etapa 3: 
- Amazon GuardDuty
- Detecção de inconformidades para promover um ambiente mais seguro usando machine learning mitigando ameaças o mais rápido o possível.
- Ameaças externas podem tentar fazer uso da aplicação através dos seus endopoints, com a ajuda do GuardDuty, todos os comportamentos suspeitos podem ser rapidamente identificados, possibilitando mitigar ameaças.


## Conclusão
A implementação de ferramentas na empresa Abstergo Industries tem como esperado diminuir custos com ambientes on premise, aumentar a tolerância a falhas e segurança dos dados e diminuir o trabalho na gestão dos sistemas, o que aumentará a eficiência e a produtividade da empresa. Recomenda-se a continuidade da utilização das ferramentas implementadas e a busca por novas tecnologias que possam melhorar ainda mais os processos da empresa.

## Anexos

https://aws.amazon.com/pt/elasticbeanstalk/
https://aws.amazon.com/pt/s3/storage-classes/glacier/
https://aws.amazon.com/pt/guardduty/


Assinatura do Responsável pelo Projeto:

Carlos Eduardo Freire Batista da Silva.