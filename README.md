# lakeflow
🧩 Por que aprender Lakeflow Jobs?
Muitas empresas usam orquestradores externos como Airflow, Prefect ou Dagster. Apesar de populares, eles criam desafios sérios:

❌ São difíceis de usar e manter;
❌ Aumentam o custo operacional e reduzem a confiabilidade;
❌ Não são integrados nativamente ao Lakehouse, gerando silos e problemas de integração.
O Lakeflow Jobs resolve esses problemas ao oferecer uma orquestração totalmente integrada ao Databricks — conectando ingestão, transformação, governança e machine learning em um só fluxo.

🧱 Arquitetura do Lakeflow Jobs
O Lakeflow Jobs é composto por quatro blocos principais:

Triggers (gatilhos)

Executa jobs de forma agendada, contínua, por chegada de arquivo ou atualização de tabela.
Control Flow (fluxo de controle)

Gerencia dependências e condições de execução entre tarefas dentro do workflow.
Observability (observabilidade)

Monitora execuções, falhas e métricas para depuração e confiabilidade.
Compute (processamento)

Executa workloads em clusters otimizados de acordo com o tipo de tarefa: ETL, ML/AI, ou Analytics/BI.
⚙️ Lakeflow Jobs dentro da Plataforma Databricks
O Lakeflow unifica toda a engenharia de dados dentro da Data Intelligence Platform, conectando:

Camada	Função
Connect	Conectores eficientes de ingestão
Declarative Pipelines (DLT)	Desenvolvimento acelerado de ETL
Jobs (Workflows)	Orquestração confiável para analytics e IA
Processing Engine (Photon)	Execução de alto desempenho
Governança (Unity Catalog)	Controle de segurança e lineage
Storage (Delta Lake, Parquet, Iceberg)	Camada de armazenamento otimizada
🚀 Benefícios principais
Autorias simples → Crie e gerencie workflows em minutos
Insights acionáveis → Monitore execuções e dependências facilmente
Confiabilidade comprovada → Execução nativa, segura e resiliente
🧠 O que você vai aprender
Entender o papel do Lakeflow Jobs na arquitetura Databricks.
Projetar workloads usando DAGs (Directed Acyclic Graphs).
Configurar gatilhos de execução (manual, agendado, file arrival, contínuo).
Implementar dependências condicionais e execuções automáticas.
Aplicar boas práticas de orquestração e tratamento de erros em produção.
🧪 Prática da Aula
Criar um workflow completo com múltiplas tarefas (notebook + SQL).
Configurar dependências e triggers entre elas.
Monitorar execução e logs diretamente no Lakeflow.
Simular falhas e executar repair runs para garantir tolerância a erros.
📦 Resultado Esperado
Ao final da aula, você será capaz de:

Criar e agendar pipelines no Databricks usando Lakeflow Jobs;
Integrar diferentes tipos de workloads (SQL, ETL, ML, dashboards);
Aplicar fluxos de controle e observabilidade em pipelines reais;
Entender como o Lakeflow substitui orquestradores externos, simplificando a arquitetura de dados.