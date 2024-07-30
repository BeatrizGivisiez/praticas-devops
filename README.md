# **Desafio: Implementação de Práticas DevOps em um Ambiente Empresarial Fictício**

## Introdução

Nesse desafio, você irá simular a implementação de práticas DevOps num ambiente empresarial fictício. Utilizará os conceitos de CALMS e as Três Maneiras do DevOps para identificar oportunidades para aprimorar os processos existentes e propor soluções que cultivem uma cultura de colaboração, automação e aprendizado contínuo.

## Etapas do Projeto

1. Diagnóstico Cultural (C de CALMS):
    - Identifique um processo na empresa fictícia que poderia se beneficiar da implementação das práticas DevOps.
    - Descreva o processo atual, destacando possíveis pontos de atrito entre as equipes e oportunidades de melhoria.
2. Automação (A de CALMS):
    - Proponha uma solução de automação para otimizar o processo identificado na etapa anterior.
    - Elabore um plano para implementar a automação de forma eficiente e minimizar possíveis resistências.
3. Mensuração e Compartilhamento de Conhecimento (M e S de CALMS):
    - Estabeleça métricas relevantes para avaliar o impacto da automação na eficiência e qualidade do processo.
    - Elabore um plano para disseminar o conhecimento acerca das melhorias implementadas e cultivar uma cultura de colaboração e aprendizado.
4. Três Maneiras:
    - Primeira Maneira (Acelerar o Fluxo): Identifique oportunidades para simplificar o processo e acelerar a entrega de valor aos clientes.
    - Segunda Maneira (Ampliar o Feedback): Estabeleça um mecanismo para coletar feedback periodicamente e integrá-lo ao ciclo de desenvolvimento.
    - Terceira Maneira (Experimentar e Aprender): Incentive uma cultura de experimentação e aprendizado, onde falhas são vistas como oportunidades de melhoria.

## Descrição da empresa

A **Tech** é uma empresa fictícia especializada em desenvolvimento de software, que oferece soluções inovadoras para clientes de diversos setores. Sua missão é simplificar a vida das pessoas através da tecnologia.

### Equipe:

- Desenvolvimento: 14 desenvolvedores com experiência em Java, C# e JavaScript. Apenas um profissional tem conhecimento em Delphi, a linguagem do sistema legado.
- Operações: A equipe de operações, composta por 4 profissionais, enfrenta desafios para manter a infraestrutura de TI e os sistemas em funcionamento eficiente, frequentemente lidando com problemas de escalabilidade e desempenho.

### Projetos em andamento

1. Sistema de Gestão de Vendas (LEGADO): Um aplicativo para gerenciamento de vendas que inclui controle de estoque, emissão de notas fiscais e relatórios de vendas.
2. Plataforma de E-commerce: uma plataforma de e-commerce escalável para clientes do setor varejista.

### Descrição dos processos atuais da empresa

1. **Entrega de Código:** Após a conclusão do desenvolvimento de um novo recurso, os desenvolvedores preparam um pacote de implantação e o encaminham à equipe de operações.
2. **Deploy:** O deploy é realizado manualmente no ambiente de produção, sem seguir um procedimento padronizado ou utilizar automação.
3. **Testes:** A equipe de operações conduz testes manuais no ambiente para verificar a funcionalidade e a integridade do código após o deploy em produção.
4. **Monitoramento:** Após o deploy, a equipe de operações monitora manualmente o sistema de logs do servidor, para identificar problemas ou falhas que possam surgir.

### Dados de desempenho:

- Tempo médio entre a entrega do código e o deploy: 2 dias.
- Taxa de sucesso dos deploys manuais: 80%.
- Número de incidentes após o deploy: média de 2 por semana.
- Tempo médio de recuperação (MTTR) de incidentes: 4 horas.

## Resultados Esperados

Ao final do desafio, terá elaborado um plano abrangente para implementar práticas DevOps num ambiente empresarial fictício. Este plano incluirá sugestões de automação, métricas de avaliação e estratégias para compartilhamento de conhecimento, refletindo uma compreensão prática dos conceitos teóricos apresentados neste módulo. Este desafio te preparará para aplicar esses princípios em ambientes de trabalho reais e cultivar uma cultura de colaboração e inovação.

## Entrega

Após concluir o desafio, você deve enviar a URL do notion (ou outro documento) em que elaborou o plano de implementação.

Além disso, que tal fazer um post no LinkedIn compartilhando o seu aprendizado e contando como foi a experiência? É uma excelente forma de demonstrar seus conhecimentos e atrair novas oportunidades!

Feito com 💜 por Rocketseat 👋


_________________________________________________________________________________
Resposta: 
 # Plano de Implementação de Práticas DevOps na Empresa Fictícia "Tech"

## 1. Diagnóstico Cultural (C de CALMS)

### Processo Identificado:
**Entrega de Código e Deploy**

### Descrição do Processo Atual:
- **Entrega de Código:** Os desenvolvedores preparam um pacote de implantação após concluir o desenvolvimento de um novo recurso e encaminham para a equipe de operações.
- **Deploy:** A equipe de operações realiza o deploy manualmente no ambiente de produção, sem seguir um procedimento padronizado ou utilizar automação.
- **Testes:** Testes manuais são conduzidos pela equipe de operações para verificar a funcionalidade e integridade do código após o deploy.
- **Monitoramento:** A equipe de operações monitora manualmente o sistema de logs do servidor para identificar problemas ou falhas após o deploy.

### Pontos de Atrito e Oportunidades de Melhoria:
- **Tempo de entrega prolongado:** A falta de automação e padronização no processo de deploy resulta em um tempo médio de 2 dias entre a entrega do código e o deploy.
- **Alta taxa de falhas:** A taxa de sucesso dos deploys manuais é de apenas 80%, resultando em incidentes frequentes (média de 2 por semana).
- **Recuperação lenta:** O tempo médio de recuperação (MTTR) de incidentes é de 4 horas, o que impacta negativamente a disponibilidade do sistema.
- **Dependência de um único especialista:** Apenas um desenvolvedor possui conhecimento em Delphi, a linguagem do sistema legado, criando um ponto único de falha.

## 2. Automação (A de CALMS)

### Solução Proposta:
**Automação do Processo de Deploy**

### Plano de Implementação:
1. **Escolha da Ferramenta:** Utilizar ferramentas de CI/CD (Continuous Integration/Continuous Deployment), como Jenkins ou GitLab CI, para automatizar o processo de deploy.
2. **Pipeline de Deploy:** Criar pipelines automatizados que incluam etapas de build, testes automatizados e deploy.
3. **Testes Automatizados:** Desenvolver testes automatizados que cubram as principais funcionalidades do sistema para garantir a integridade do código antes do deploy.
4. **Infraestrutura como Código (IaC):** Implementar o uso de ferramentas como Terraform ou Ansible para gerenciar a infraestrutura de TI de forma automatizada e padronizada.
5. **Treinamento e Envolvimento:** Treinar a equipe de operações e desenvolvedores no uso das novas ferramentas e práticas de automação para garantir a adesão e minimizar resistências.

## 3. Mensuração e Compartilhamento de Conhecimento (M e S de CALMS)

### Métricas Relevantes:
- **Tempo de Deploy:** Medir o tempo desde a entrega do código até o deploy em produção.
- **Taxa de Sucesso dos Deploys:** Monitorar a taxa de sucesso dos deploys automatizados.
- **Número de Incidentes:** Rastrear o número de incidentes após os deploys.
- **MTTR:** Medir o tempo médio de recuperação de incidentes.

### Plano de Disseminação do Conhecimento:
1. **Documentação:** Criar uma documentação detalhada sobre os novos processos e ferramentas implementadas.
2. **Workshops e Treinamentos:** Realizar workshops e sessões de treinamento regulares para a equipe de operações e desenvolvedores.
3. **Comunicação:** Utilizar plataformas de comunicação internas, como Slack ou Microsoft Teams, para compartilhar atualizações, boas práticas e lições aprendidas.
4. **Reuniões de Retrospectiva:** Conduzir reuniões de retrospectiva após cada ciclo de deploy para discutir o que funcionou bem e o que pode ser melhorado.

## 4. Três Maneiras do DevOps

### Primeira Maneira (Acelerar o Fluxo):
- **Simplificação do Processo:** Automatizar o pipeline de deploy para reduzir o tempo de entrega e padronizar o processo, eliminando a variabilidade dos deploys manuais.

### Segunda Maneira (Ampliar o Feedback):
- **Feedback Contínuo:** Implementar ferramentas de monitoramento e logging automatizados que forneçam feedback contínuo sobre o desempenho e a integridade do sistema em produção.
- **Ciclo de Feedback Curto:** Realizar reuniões de feedback frequentes entre as equipes de desenvolvimento e operações para discutir melhorias contínuas.

### Terceira Maneira (Experimentar e Aprender):
- **Cultura de Experimentação:** Incentivar a equipe a realizar experimentos controlados com novas ferramentas e práticas de automação, documentando os resultados e compartilhando as lições aprendidas.
- **Ambiente de Aprendizado:** Criar um ambiente seguro onde falhas são vistas como oportunidades de aprendizado e melhoria contínua.

## Resultados Esperados
- **Redução do Tempo de Deploy:** Espera-se uma redução significativa no tempo de deploy, de 2 dias para poucas horas ou minutos.
- **Aumento na Taxa de Sucesso dos Deploys:** Com a automação, a taxa de sucesso dos deploys deve aumentar para mais de 95%.
- **Redução de Incidentes:** A introdução de testes automatizados e monitoramento contínuo deve reduzir o número de incidentes pós-deploy.
- **Melhoria no MTTR:** A padronização e automação dos processos devem reduzir o tempo médio de recuperação de incidentes.

Este plano visa transformar a cultura e os processos da Tech, promovendo uma maior colaboração entre as equipes, automação eficiente, e um ciclo contínuo de aprendizado e melhoria.
