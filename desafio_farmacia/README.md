# DESAFIO DE PROJETO AWS - REDUÇÃO DE CUSTOS
Nesse projeto você poderá participar da implementação da plataforma da AWS em uma farmácia fictícia que dará seus primeiros passos na computação na nuvem.


# RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS

Data: 07/01/2024
Empresa: Abstergo Industries 
Responsável: Marcio Boccalletti

## Introdução
Este relatório apresenta o processo de implementação de ferramentas na empresa [nome da empresa], realizado por [nome do responsável pelo projeto]. O objetivo do projeto foi elencar 3 serviços AWS, com a finalidade de realizar diminuição de custos imediatos.

## Descrição do Projeto
O projeto de implementação de ferramentas foi dividido em 3 etapas, cada uma com seus objetivos específicos. A seguir, serão descritas as etapas do projeto:

- Etapa 1: Amazon EC2 (Elastic Compute Cloud)
- Nome da Ferramenta: Amazon EC2
- Foco da Ferramenta: Hospedagem de aplicações e serviços
- Descrição de Caso de Uso:
Provisionamento de Instâncias: Selecionamos instâncias EC2 que atendem aos requisitos de desempenho e capacidade da Abstergo. Utilizamos instâncias reservadas para garantir custos mais baixos a longo prazo.
Auto Scaling: Configuramos grupos de Auto Scaling para ajustar dinamicamente o número de instâncias EC2 com base na carga de trabalho. Isso permite escalar para cima durante picos de tráfego e reduzir para baixo durante períodos de inatividade, proporcionando economia de custos.
Balanceamento de Carga: Implementamos o Elastic Load Balancing para distribuir o tráfego entre as instâncias EC2, melhorando a disponibilidade e a confiabilidade da aplicação.

- Etapa 2: Amazon S3 (Simple Storage Service)
- Nome da Ferramenta: Amazon S3
- Foco da Ferramenta: Armazenamento de dados escalável
- Descrição de Caso de Uso:
Migração de Dados: Realizamos uma migração planejada dos dados existentes para o Amazon S3, garantindo a integridade e a consistência.
Organização de Dados: Criamos buckets S3 para organizar os dados de forma lógica e eficiente, facilitando o gerenciamento e a aplicação de políticas de segurança.
Políticas de Ciclo de Vida: Implementamos políticas de ciclo de vida para movimentar automaticamente dados menos frequentemente acessados para classes de armazenamento mais econômicas, como o S3 Glacier, reduzindo os custos de armazenamento.

- Etapa 3: AWS Lambda
- Nome da Ferramenta: AWS Lambda
- Foco da Ferramenta: Computação sem servidor
- Descrição de Caso de Uso:
Funções Serverless: Desenvolvemos e implementamos funções Lambda para executar tarefas específicas, como processamento de eventos, manipulação de arquivos e execução de operações pontuais.
Gatilhos Automáticos: Configuramos gatilhos para acionar as funções Lambda em resposta a eventos específicos, como a chegada de novos dados no Amazon S3 ou solicitações via API Gateway.
Integração com Serviços: Integrados as funções Lambda com outros serviços AWS, como Amazon S3, Amazon DynamoDB e AWS Step Functions, para criar workflows eficientes e automatizados.


## Conclusão
A implementação bem-sucedida das ferramentas AWS nas três etapas do projeto para a Abstergo Industries representa um marco significativo na busca por eficiência operacional e redução de custos. Cada etapa foi meticulosamente planejada e executada, proporcionando benefícios tangíveis para a empresa.

A utilização do Amazon EC2 para hospedar aplicações e serviços permitiu uma adaptação dinâmica à demanda, garantindo eficiência operacional e economia por meio do Auto Scaling e do Balanceamento de Carga. A migração para o Amazon S3 não apenas centralizou o armazenamento de dados, mas também introduziu uma gestão inteligente de dados com políticas de ciclo de vida, resultando em economia substancial nos custos de armazenamento.

A adoção do AWS Lambda para computação sem servidor revelou-se crucial na eliminação de infraestrutura desnecessária, executando tarefas específicas de maneira eficiente e custo-efetiva. A automação de processos por meio de gatilhos automáticos e integração com outros serviços contribuiu para workflows mais ágeis e responsivos.

Os benefícios esperados, incluindo a otimização de recursos, escalabilidade sob demanda e redução de custos operacionais, foram alcançados com sucesso. Recomenda-se fortemente a continuidade da utilização das ferramentas implementadas e a exploração de novas tecnologias para manter a Abstergo Industries na vanguarda da eficiência tecnológica.

Este projeto não é apenas uma realização técnica, mas também uma demonstração do comprometimento da Abstergo Industries em se manter atualizada com as melhores práticas de tecnologia, promovendo um ambiente operacional ágil e sustentável.


## Anexos
Manual de utilização do Amazon EC2
Documentação de migração para o Amazon S3
Guia de implementação de funções serverless com AWS Lambda



Assinatura do Responsável pelo Projeto:

Marcio Boccalletti