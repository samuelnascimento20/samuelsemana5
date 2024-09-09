# Ponderada Semana 5 - Samuel Lopes

## Sumário 

### 1. O que é um Plano de C?
### 2. Plano de Cutover Microsoft Dynamics 365 e Seus Elementos
### 3. Pontos Postivos
### 4. Pontos Negativos
### 5. Referências

## 1. O que é um Plano de Cutover?

O plano de cutover é uma etapa crucial durante a migração de sistema ERP em uma empresa, o processo deve ser cuidadosamente planejado, pois envolve uma série de atividades que precisam ser executadas em uma janela de tempo reduzida, normalmente em um final de semana, para minimizar o impacto nas operações do negócio.
Durante o cutover, tanto o sistema antigo quanto o novo ficam inacessíveis, o que exige uma coordenação eficiente das equipes envolvidas e uma comunicação clara com todos os stakeholders. A elaboração de um plano de cutover inclui obrigatoriamnete o desenvolvimento de uma estratégia bem definida, a definição de papéis e responsabilidades, a criação de uma lista detalhada de tarefas a serem realizadas, além de um plano de rollback, caso ocorra algum problema. O sucesso desse processo depende de testes repetidos em um ambiente de pré-produção para garantir que o sistema esteja funcionando adequadamente e que todos os problemas sejam resolvidos antes da migração efetiva.

## 2. Plano de Cutover Microsoft Dynamics 365

![image](https://asset.cloudinary.com/davpvmkhd/08c47d883d1a55d54c3be97f1fe960d9)

### 2.1 O plano de Cutover apresentado pela Microsoft Dynamics 365 contém vários elementos que refletem a organização e o controle do processo de transição do ambiente de configuração para a produção. Cada linha corresponde a uma etapa do processo, detalhando as atividades essenciais para garantir que o sistema esteja pronto para o go-live. Aqui estão os principais componentes presentes na tabela:

### 2.2 Cutover Step (Etapa do Cutover): Identifica as tarefas que precisam ser realizadas, como a instalação de customizações, validação de configurações, execução de políticas de compartilhamento de dados, entre outras. Cada etapa é numerada para garantir a sequência correta das atividades.

### 2.3 Area (Área): Indica o contexto ou a área do sistema Dynamics 365 onde a tarefa será realizada. No caso da tabela, as atividades estão na área de implementação (IMP), que se refere à fase de configuração final do ambiente.

### 2.4 Environment (Ambiente): Refere-se ao ambiente onde a tarefa será executada, como "Config" para o ambiente de configuração e "Sandbox" para a fase de testes.

### 2.5 System (Sistema): Define o sistema em que a ação será executada, que, neste caso, é o Microsoft Dynamics.

### 2.6 Countdown (Contagem regressiva): Mostra o número de dias restantes antes do início da tarefa, facilitando o planejamento e execução na ordem correta.

### 2.7 Status: Indica o estado atual da tarefa (neste caso, todas estão planejadas).

### 2.8 Duration (Duração): Especifica a duração estimada de cada tarefa, por exemplo, 1 ou 2 dias.

### 2.9 Estimated Start and End (Início e Fim Estimados): Detalha as datas planejadas para o início e fim de cada etapa. Esse controle de datas garante que todas as atividades sejam realizadas dentro do prazo.

### 2.10 Owner (Responsável): Define as equipes ou membros responsáveis por cada tarefa. Isso ajuda na distribuição clara de responsabilidades durante o cutover.

### 2.11 Validated by (Validado por): Indica quem será responsável por validar o sucesso da tarefa concluída, garantindo que os critérios de qualidade foram atendidos.

### 2.12 Actual Start and End (Início e Fim Real): Espaços reservados para preencher as datas reais de início e término das tarefas. Esses campos são úteis para monitorar se as atividades estão ocorrendo conforme o cronograma.

### 2.13 % Complete (% Concluído): Reflete o progresso de cada tarefa, ajudando a acompanhar o andamento do cutover e identificar possíveis atrasos.

## 3. Pontos Positvos 

### 3.1 Clareza nas Tarefas e Responsabilidades: O plano de cutover define claramente cada tarefa, o responsável e o validador, facilitando a comunicação e a coordenação entre as equipes. Isso garante que cada membro saiba exatamente o que deve ser feito e por quem será validado.

### 3.2 Cronograma Detalhado: As colunas de data estimada de início e término, juntamente com a duração de cada tarefa, permitem um planejamento rigoroso do tempo necessário para o cutover. Isso ajuda a mitigar riscos relacionados a atrasos e garantir que as atividades sigam uma sequência lógica.

### 3.3 Foco em Validação e Controle de Qualidade: A presença de um validador para cada etapa assegura que as tarefas sejam revisadas antes de avançar para a próxima fase, promovendo um maior controle de qualidade durante o cutover.

### 3.4 Preparação para UAT (Testes de Aceitação de Usuário): O plano inclui etapas críticas, como mover o sistema para o ambiente de sandbox e aplicar o backup para testes (UAT), assegurando que o ambiente esteja devidamente preparado para validação antes do go-live.

## 4. Pontos Negativos

### 4.1 Falta de Indicadores de Riscos ou Contingências: O plano não menciona explicitamente como lidar com imprevistos ou possíveis falhas nas etapas do cutover. A ausência de um plano de rollback ou de indicadores de risco pode ser problemática caso algo dê errado.

### 4.2 Dependências Não Especificadas: O plano não detalha as dependências entre as tarefas. Algumas atividades, como a validação das configurações, podem ser afetadas por atrasos em tarefas anteriores, mas o impacto dessas dependências não é explicitamente tratado no plano.

## 5. Referências

Microsoft Dynamics 365. Transition to new solutions successfully with the cutover process. Disponível em:  https://learn.microsoft.com/en-us/dynamics365/guidance/implementation-guide/prepare-go-live-cutover-strategy. Acesso em: 03 set. 2024.




