# Desafio Microsserviços

## Cenário
Uma companhia de telecomunicações quer modernizar sua aplicação de CRM, um monilítico desenvolvido em casa.

Neste cenário *brownfield*, o cliente deseja priorizar o desenvolvimento de registro de interações com a empresa.

Essa funcionalidade é utilizada por todos os canais (web, app móvel, unidade de resposta audível - ura e sistemas de parceiros).

Para o MVP, o cliente escolheu duas funções:

- **Fornecer protocolo**: Gera um código único, mas legível pelo usuário, utilizado como identificador de um atendimento. Todos as solicitações, reclamações, elogíos, etc., realizadas pelo o usuário, serão *marcados* esse código.
- **Registrar manifestações do cliente**: Registro simples de manifestações do cliente, tais como: elogíos, reclamações e sugestões. Esses registros são utilizados por algumas áreas internas da empresa.

## Restrições

- O custo deve ser considerado nas decisões arquiteturais;
- Todo o software deve ser *open source*.

## Requisitos não funcionais
- A escalabilidade de ser preferencialmente horizontal;
- Os serviços devem ser reativos;

## Explique suas decisões
- Explique suas decisões arquiteturas;
- Justifique suas escolhas de produtos.

## Seu código
- Seu código-fonte deve ser disponibilizado no github;
- Seus binários devem ser executáveis como imagem docker;
- Todas as dependências devem ser fornecidas e preferencialmente públicas.

## Critério de pronto
- Cenário atendido;
- Arquivo texto com descrição das decisões de projeto (entidades, objetos de valor, agregados, arquitetura, etc.);
- Instruções para execução do software;
- Software funcionando;
- Todos os artefatos devem estar no github;
- Entrega do link para o repositório do github;

## Dúvidas
Caso tenha questionamentos, favor registrar neste repositório (seção *Issue*).

Solicite permissão para contribuir com esse repositório.