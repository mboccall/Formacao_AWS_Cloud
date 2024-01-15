# RELATÓRIO DE IMPLEMENTAÇÃO DE MEDIDAS DE SEGURANÇA NA AWS

Data: 15/01/2024
Empresa: Abstergo Industries
Responsável: Marcio Boccalletti

# Introdução
Este relatório visa detalhar o processo de implementação de três medidas de segurança na infraestrutura da Abstergo Industries, utilizando os serviços da Amazon Web Services (AWS). O projeto foi liderado por Marcio Boccalletti com o objetivo de fortalecer a postura de segurança dos ativos da empresa na nuvem.

Descrição do Projeto

## Medida 1: Configuração de Grupos de Segurança

Descrição do Caso de Uso:
Configuração de grupos de segurança na AWS para restringir o tráfego de entrada e saída.
Definição de regras específicas para permitir apenas o tráfego necessário para as instâncias relevantes.
Utilização de identificadores únicos para referenciar grupos de segurança e facilitar a manutenção.

Procedimentos:
Acesso ao Console AWS e navegação até o serviço EC2.
Criação de grupos de segurança para instâncias específicas.
Definição de regras de ingresso e egresso baseadas nos requisitos de segurança.

## Medida 2: Implementação de AWS IAM (Identity and Access Management)

Descrição do Caso de Uso:
Configuração de políticas de IAM para controlar o acesso aos recursos da AWS.
Atribuição de funções específicas a usuários, garantindo o princípio do menor privilégio.
Monitoramento contínuo de atividades por meio de registros de auditoria.

Procedimentos:
Acesso ao Console AWS e navegação até o serviço IAM.
Criação de políticas personalizadas para diferentes funções.
Associação de políticas a usuários de acordo com suas responsabilidades.

## Medida 3: Implementação de Monitoramento Avançado com AWS CloudWatch

Descrição do Caso de Uso:
Configuração de alertas proativos para atividades suspeitas ou eventos críticos.
Utilização de métricas do CloudWatch para monitorar o desempenho das instâncias.
Integração com outros serviços para resposta rápida a incidentes.

Procedimentos:
Acesso ao Console AWS e navegação até o serviço CloudWatch.
Configuração de painéis personalizados para visualização contínua.
Estabelecimento de alertas baseados em métricas específicas.

# Conclusão
A implementação dessas medidas de segurança na AWS visa fortalecer a postura de segurança da Abstergo Industries, garantindo um controle mais efetivo sobre o acesso e monitoramento proativo. O próximo passo é avaliar os resultados obtidos para verificar a eficácia das medidas implementadas.

Assinatura do Responsável pelo Projeto:

Marcio Boccalletti





