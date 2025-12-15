# Contexto
Queremos criar um aplicativo chamado **CadÚnico Flow IA**, voltado para equipes municipais do CadÚnico.
O aplicativo tem como objetivo organizar, priorizar e apoiar a correção de inconsistências que retornam do processamento federal após o envio dos dados da prefeitura para Brasília.

A ideia é reduzir retrabalho e tempo gasto em correções repetitivas, utilizando uma abordagem conversacional e assistiva com IA, mantendo o humano no controle.

**Conceptual workflow of CadÚnico Flow IA.**  
Illustration representing the end-to-end process of data ingestion, automated validation, human review, and structured reporting to support the correction of inconsistencies returned from federal processing.

![CadÚnico Flow IA – Conceptual Workflow](./app_cadunico_dio_01.png)

# Problema
Após o envio dos cadastros ao Governo Federal, os dados retornam com inconsistências (ex.: bairro, endereço, CEP, logradouro).
Hoje, técnicos gastam horas corrigindo manualmente erros recorrentes, sem priorização clara, sem explicações padronizadas e com risco de inconsistência adicional.

Queremos resolver isso com um aplicativo que organize essas tarefas de forma simples, explicável e orientada a fluxo.

# Público-Alvo
- Técnicos do CadÚnico
- Supervisores e coordenação
- Departamento de Tecnologia da Informação e Análise de dados da prefeitura de Hortolândia

# Funcionalidades-Chave (MVP)
1. Importar lote de dados enviados e lote de dados retornados (CSV/Excel).
2. Detectar automaticamente divergências campo a campo.
3. Classificar inconsistências por tipo (endereço, bairro, CEP etc.).
4. Priorizar correções por impacto, recorrência e tempo em aberto.
5. Sugerir correções baseadas em regras explícitas e padronização.
6. Utilizar IA de forma assistiva para explicar sugestões e gerar justificativas.
7. Manter uma fila de revisão humana obrigatória antes de qualquer correção.
8. Exportar relatórios e planilhas finais para envio e auditoria.

**Conceptual dashboard view.**  
High-level visualization of a centralized workspace where municipal teams review, prioritize, and validate suggested corrections with AI assistance and full human control.

![CadÚnico Flow IA – Conceptual Dashboard](./app_cadunico_dio_02.png)

# Entregável da IA
Gerar um plano de MVP com:
- descrição do fluxo de uso,
- principais telas conceituais,
- comportamento do agente assistivo,
- critérios de validação do MVP.

Usar tom educativo, linguagem clara e foco em organização de processos, não em automação total.

