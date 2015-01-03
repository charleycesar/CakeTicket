#CakeTicket - Webdesk

Esse projeto foi idealizado por participantes do grupo CakePHP Brasil no Facebook (https://www.facebook.com/groups/cakebrasil) e seu principal objetivo é o estudo e desenvolvimento de uma aplicação web utilizando o framework CakePHP na versão 3.0.0.


## Principais Funcionalidades
Podemos nos basear nos seguintes pilares:
- Customização
- Integração
- Atendimento
- Gerenciamento e Controle


## Customização

### Campos customizados
Permitir a escolha de quais serão os campos na criação de tickets customizando a ferramenta para atender as necessidades de diversas áreas.

### Customização do cadastro de clientes
Permitir a escolha de quais campos cadastrais o perfil do seu cliente precisa ter, como telefone, endereço, site e outros campos personalizados.
Após cadastramento do usuário, o mesmo deverá receber um email para confirmar o seu cadastro validando o endereço de email.

### Controle de Acesso
Administradores podem criar novos e/ou converter usuários em agentes e também bloqueá-los. Os agentes nunca poderão ser excluídos do sistema a fim de manter o histórico das interações com os chamados.

### Acesso diferenciado por perfil
Cada perfil possui um nível de acesso:  Enquanto agentes apenas interagem nos tickets, administradores podem também gerenciar e customizar a ferramenta.

A customização da ferramenta é um ponto crítico por diversos motivos:
Muitas ferramentas para abertura de chamados são específicas de acordo com a regra de negócio de cada empresa, portanto, neste caso teremos que definir alguns perfis onde cada perfil tem a sua propria regra de negócio.
Exemplo A:
Se uma empresa deseja utilizar o sistema para registrar ocorrências de service desk (muito comum no mercado) podemos criar um perfil para empresa onde problemas comuns já estão pré definidos no sistema.
Exemplo B:
Se uma empresa utiliza o sistema para registrar ocorrências para problemas relacionados a serviços de terceiros, teremos um perfil com essas ocorrências já predefinidas.


### Atribuição de Categorias por agente
Possibilidade de categorizar os agentes e os agentes podem ser responsáveis por categorias específicas.
Os administradores terão acesso à todas as áreas do sistema, inclusive criação/manutenção dos perfis e regras de negócio.

### Personalização
Customize a ferramenta com o logo da sua empresa e com a paleta de cores que preferir.

## Integração
Permitir a importação e exportação de dados por meio de xml, csv entre outros.
É importante definir que tipo de integração será feita através do sistema.

## Atendimento
Agentes e administradores podem deixar comentários internos, que não são visualizados pelos que solicitaram o atendimento.

### Agentes por categoria
Os tickets devem ser encaminhados apenas para os agentes responsáveis por determinadas categorias.
Neste caso os agentes deverão ser agrupados por "equipe"", exemplo: desenvolvimento, suporte em campo, suporte por telefone, suporte para Telecom e suporte de terceiros (assistência técnica e outros).

### Notificações por email
O sistema deve enviar uma notificação por e-mail  sempre que um novo ticket for criado ou tiver uma nova resposta.
Cada novo usuário cadastrado no sistema deverá confirmar o proprio endereço de email através do email recebido com código para validar o email.


##Gerenciamento e Controle
### Prazos e prioridades para os tickets
Para cada ticket o agente pode atribuir uma prioridade e também uma data final para ele ser concluído. 
Essa característica deverá ser implementada definindo o SLA (Service Level Agreement) para cada tipo de chamado e também por cliente, onde cada cliente (empresa) pode definir o tempo de atendimento e criticidade do chamado aberto.


### Visão Geral (Dasboard)
Ao acessar o sistema, tenha uma visão geral do que está acontecendo, com gráficos e acessos rápidos, além de status dos tickets por agente.
A visão geral do sistema deverá ser separada entre visão para agentes, administradores e visão do próprio usuário.

### Controle dos tickets por status
Permitir acompanhamento quando um ticket foi respondido pelo cliente e aguarda nova resposta de um agente.

### Relatórios
Permitir acompanhamento do desempenho de seus tickets em relatórios completos: tickets por categoria, cliente e empresa.
 - Relatórios individuais para os usuários, neste caso o usuário pode consultar o histórico dos chamados abertos e já solucionados pelo suporte. Essa funcionalidade pode resuzir o número de abertura de chamados orientando o usuário a consultar o histórico para conhecer a solução do suporte. Neste caso também é possível criar uma base de conhecimento para facilitar a resolução de problemas por parte do usuário.



