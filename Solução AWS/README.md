# RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS
Data: 09 de janeiro de 2026

Empresa: Abstergo Industries

Responsável: Emerson Glauber
- Este relatório foi desenvolvido com auxílio do Gemini

## Introdução
Este relatório apresenta o plano estratégico de implementação de serviços de nuvem na Abstergo Industries, focado em transformar a infraestrutura legada em um ecossistema orientado a dados. O objetivo central é elencar 3 serviços AWS que permitam a redução imediata de custos operacionais, garantindo escalabilidade para análises preditivas e maior agilidade no atendimento às demandas do setor farmacêutico.

### Descrição do Projeto
O projeto foi estruturado para integrar fundamentos de marketing (entendimento da jornada do paciente), ciência de dados (processamento de grandes volumes) e computação em nuvem (otimização de custos). As etapas são:

#### Etapa 1: Otimização de Armazenamento e Data Lake
- Nome da ferramenta: Amazon S3 (Simple Storage Service)

Foco da ferramenta: Redução de custos de infraestrutura física e centralização de dados.

Descrição de caso de uso: Substituição de servidores locais caros por um Data Lake centralizado. A Abstergo pode armazenar anos de registros de vendas, logs de distribuição e dados demográficos de pacientes com alta durabilidade. Ao utilizar classes de armazenamento como o S3 Intelligent-Tiering, o sistema move automaticamente dados pouco acessados para camadas mais baratas, reduzindo custos de armazenamento em até 70% sem perder a disponibilidade para análises históricas.

#### Etapa 2: Processamento de Dados Escalável e Efêmero
- Nome da ferramenta: AWS Glue

Foco da ferramenta: ETL (Extração, Transformação e Carga) Serverless para preparação de dados.

Descrição de caso de uso: Em vez de manter servidores de processamento ligados 24/7, o Glue é acionado apenas quando necessário para limpar e organizar os dados brutos do S3. Isso permite que a equipe de Ciência de Dados prepare bases prontas para modelos de Machine Learning (como previsão de demanda de medicamentos por região) pagando apenas pelo tempo de execução, eliminando o custo de ociosidade de máquinas físicas.

#### Etapa 3: Inteligência de Negócio e Visualização de Baixo Custo
- Nome da ferramenta: Amazon QuickSight

Foco da ferramenta: Dashboards interativos e insights de marketing baseados em ML.

Descrição de caso de uso: Implementação de painéis que conectam diretamente ao Data Lake para monitorar KPIs de vendas e comportamento do cliente. O QuickSight utiliza um modelo de preços de "pagamento por sessão", o que é ideal para a Abstergo Industries expandir o acesso a dados para gestores regionais sem a necessidade de licenças individuais caras. Isso gera vantagem competitiva ao permitir ajustes rápidos em campanhas de marketing baseados em dados reais de estoque e consumo.

## Conclusão
A implementação das ferramentas AWS na empresa Abstergo Industries tem como esperado a drástica redução de despesas com manutenção de hardware, a democratização do acesso aos dados e o ganho de agilidade na tomada de decisão estratégica, o que aumentará a eficiência operacional e a produtividade da empresa. Com uma infraestrutura elástica, a farmacêutica deixa de gastar com "TI de sustentação" e passa a investir em "TI de inovação". Recomenda-se a continuidade da utilização das ferramentas implementadas e a exploração futura de serviços de IA preditiva, como o Amazon SageMaker, para antecipar tendências de mercado.

### Anexos
Arquitetura de Dados: Diagrama de fluxo de dados do S3 para o QuickSight.

Planilha de Estimativa de Custos: Comparativo TCO (Total Cost of Ownership) On-premise vs AWS.

Guia de Governança: Políticas de privacidade de dados (LGPD) aplicadas ao ambiente Cloud.

#### Assinatura do Responsável pelo Projeto:

Emerson Glauber