
# Demonstração do Resultado do Exercício (DRE) para Condomínios

Este relatório do Power BI oferece uma análise abrangente das demonstrações financeiras históricas (DRE) de vários shoppings centers, além de rastrear outras despesas relacionadas. As principais funcionalidades do relatório incluem:

1) Análise de Receita: Desdobramento detalhado das fontes de renda dos shoppings centers.
2) Rastreamento de Despesas: Categorização e análise de várias despesas, incluindo custos operacionais, manutenção e despesas administrativas.
3) Visão Geral de Lucros e Perdas: Dados históricos mostrando as tendências de lucro e perda ao longo do tempo para cada shopping center.
4) Análise Comparativa: Métricas de desempenho comparativas entre diferentes shopping centers para identificar os melhores e piores desempenhos.
5) Outras Despesas: Rastreamento e análise de despesas adicionais , proporcionando uma visão holística da saúde financeira.

Este relatório auxilia na tomada de decisões financeiras informadas, na otimização da eficiência operacional e na melhoria da saúde financeira geral dos shopping centers e entidades associadas.

### Link do Dashboard: https://app.powerbi.com/view?r=eyJrIjoiYWQzM2NiMjAtM2FhNS00OTU2LTkzNzMtMzJjYTYwM2FhMzExIiwidCI6IjdkYzY0N2U1LTYyODgtNDk2ZS05YzUyLTcwNDY3NDkyZWJmMyJ9

## Problema a ser Resolvido

Gerenciar o desempenho financeiro e as despesas de vários shoppings centers apresenta desafios significativos, como consolidar dados financeiros dispersos, rastrear e categorizar despesas com precisão e comparar o desempenho de diferentes centros. Essas dificuldades complicam a identificação de tendências, a previsão de desempenho futuro e a tomadas de decisões estratégicas informadas. Além disso, uma visão abrangente de todas as despesas relacionadas, não apenas aquelas específicas dos shoppings centers, é necessária para uma visão financeira completa.

O objetivo é desenvolver um relatório no Power BI que aborde esses problemas, fornecendo uma plataforma unificada para consolidação de dados, rastreamento de despesas, análise comparativa e insights históricos, melhorando, assim, a gestão financeira e a tomada de decisão.


### Passo a Passo

1) Coleta de Dados: Recolher dados financeiros de várias fontes, como sistemas de contabilidade, sistemas ERP e planilhas Excel. Esses dados incluem demonstrações de resultados, relatórios de despesas e outros documentos financeiros relevantes.

2) Importação de Dados: Importar os dados coletados para o Power BI. Neste caso específico, foi utilizado um arquivo CSV e vários Excel.

3) Transformação e Limpeza de Dados:

* Formatação de Dados: Padronizar o formato de todos os dados importados para garantir consistência. Isso inclui formatar datas, números e campos de texto uniformemente em todos os conjuntos de dados.
* Tratamento de Valores Faltantes: Identificar e corrigir dados ausentes ou incompletos, preenchendo lacunas, usando médias ou outros métodos de imputação, ou excluindo registros incompletos quando necessário.
* Validação de Dados: Garantir que os dados sejam precisos e confiáveis, cruzando-os com documentos de origem e corrigindo quaisquer discrepâncias.

4) Mesclagem de Dados:

* Mesclagem de Tabelas: Combinar tabelas de diferentes fontes que contenham informações relacionadas. Por exemplo, mesclar demonstrações de resultados com relatórios de despesas correspondentes para criar um conjunto de dados financeiro unificado.
* Consolidação de Arquivos: Se múltiplos arquivos em uma pasta contiverem dados relacionados (por exemplo, relatórios anuais), consolidar esses arquivos em um único conjunto de dados abrangente. Isso pode ser automatizado usando a funcionalidade “Combinar Arquivos” do Power BI.

5) Transformação de Dados no Power Query:

* Normalização: Normalizar os dados para garantir que informações semelhantes sejam categorizadas consistentemente em diferentes tabelas.
* Colunas Calculadas e Medidas: Criar colunas calculadas e medidas para derivar métricas financeiras chaves, como margens de lucro, taxas de crescimento e índices de despesas.
* Enriquecimento de Dados: Melhorar os conjuntos de dados com informações adicionais, como adicionar períodos financeiros, categorizar despesas ou integrar dados externos como benchmarks de mercado.

6) Modelagem de Dados:

* Mapeamento de Relacionamentos: Definir relacionamentos entre tabelas para criar um modelo de dados robusto que reflita com precisão as conexões entre diferentes conjuntos de dados.
* Hierarquias: Criar hierarquias (por exemplo, por período de tempo, departamento ou categoria de despesa) para permitir análises detalhadas.

7) Design do Relatório:

* Criação de Visualizações: Desenvolver visualizações, como gráficos de barras, linhas, cartões e tabelas para representar visualmente os dados financeiros. Cada visualização deve ser projetada para fornecer insights claros sobre aspectos específicos dos dados.
* Desenvolvimento de Dashboards: Montar visualizações em dashboards interativos que permitam aos usuários explorar os dados dinamicamente. Garantir que os dashboards sejam fáceis de usar e forneçam insights significativos à primeira vista.
* Interatividade: Implementar filtros, segmentações e ações de drill-through para permitir que os usuários interajam com os dados e se concentrem em áreas específicas de interesse.

8) Validação e Teste:

* Precisão dos Dados: Verificar se os dados exibidos no relatório são precisos e correspondem aos dados de origem.
* Teste de Desempenho: Garantir que o relatório tenha um bom desempenho, mesmo com grandes conjuntos de dados, otimizando modelos de dados e visualizações.

9) Implantação e Compartilhamento:

* Publicação: Publicar o relatório no Power BI Service ou em um Power BI Report Server local.
* Gerenciamento de Acesso: Configurar papéis de usuário e permissões para controlar o acesso ao relatório e garantir a segurança dos dados.
* Treinamento de Usuários: Fornecer treinamento aos usuários finais sobre como navegar e utilizar o relatório de forma eficaz.

Seguindo esses passos, o relatório do Power BI proporcionará uma visão abrangente, precisa e perspicaz do desempenho financeiro e das despesas de vários shopping centers, permitindo uma melhor gestão financeira e tomada de decisões estratégicas.

# Segurança em Nível de Linha (RLS)

A Segurança em Nível de Linha (RLS) é um recurso crucial no Power BI que controla o acesso aos dados em um nível granular. Implementando RLS, as organizações podem restringir a visibilidade dos dados para os usuários com base em seus papéis e permissões, garantindo que os indivíduos vejam apenas os dados pertinentes às suas responsabilidades. Isso melhora a segurança dos dados, mantém a confidencialidade e cumpre os requisitos regulamentares. Além disso, o RLS promove uma experiência personalizada ao apresentar dados relevantes, o que melhora a eficiência na tomada de decisões e a integridade operacional geral.

### Configurando o acesso

![aaa](https://github.com/filipegoncmartins/Income-Statement-DRE-for-Condominiums/assets/148718210/1c596c9f-3ed9-4284-b571-02cab2b7352d)

### Inclusão de usuários

![aaa](https://github.com/filipegoncmartins/Income-Statement-DRE-for-Condominiums/assets/148718210/a4cef744-ef8d-4b25-8f07-33ab3491dbcf)


### Capa

A página inicial serve como o centro principal para os usuários, oferecendo acesso a várias abas e recursos. Dependendo das configurações de Segurança em Nível de Linha (RLS), os usuários podem ver e interagir com diferentes relatórios, dashboards e conjuntos de dados adaptados às suas permissões específicas. Isso garante que cada usuário acesse apenas os dados relevantes para sua função, aprimorando a segurança dos dados e a experiência personalizada do usuário.

![pic1](https://github.com/filipegoncmartins/Income-Statement-DRE-for-Condominiums/assets/148718210/94ed5e0e-3b93-40da-965c-1715f242cf63)

### DRE Geral 

A página dois do relatório do Power BI exibe valores gerais com um gráfico mensal mostrando o total acumulado. As abas podem ser alternadas usando a navegação na parte inferior da visualização, permitindo um uso mais eficiente do espaço e uma apresentação mais clara dos dados. Esse layout melhora a capacidade do usuário de se concentrar nas métricas principais, maximizando a área visual disponível para análise detalhada.

![pic1](https://github.com/filipegoncmartins/Income-Statement-DRE-for-Condominiums/assets/148718210/63c5bc7e-03cf-46a8-bf56-fce2e6a0f46d)

### KPI's

Na próxima página, os KPIs são explicados ao longo do tempo, destacando suas tendências e métricas de desempenho. Esta página é projetada para fornecer aos usuários uma visão abrangente dos principais indicadores de desempenho, mostrando seu progresso e variações ao longo de períodos específicos. Essa análise temporal ajuda a entender a trajetória e a eficácia de várias iniciativas e estratégias.

![pic1](https://github.com/filipegoncmartins/Income-Statement-DRE-for-Condominiums/assets/148718210/f0ec0402-7e1d-403c-99ed-1e44a092bb6d)

### Comparação Mensal
Na próxima página, uma comparação mensal dos valores reais versus orçados é exibida ao lado do mesmo mês de um ano anterior selecionado pelo usuário. À direita, os principais KPIs são apresentados para análise aprofundada. Esta configuração permite aos usuários avaliar o desempenho em relação às metas e aos dados históricos, fornecendo insights sobre tendências e variações.

![pic1](https://github.com/filipegoncmartins/Income-Statement-DRE-for-Condominiums/assets/148718210/833b1fb0-63ac-41c3-803a-8080e6055b05)

### Comparação Acumulada

Na próxima página, uma comparação dos valores reais acumulados até o mês selecionado pelo usuário é exibida em relação ao orçamento para o mesmo período e aos valores reais de um ano anterior escolhido pelo usuário. À direita, os principais KPIs são apresentados para análise detalhada. Esse layout permite que os usuários avaliem o desempenho ao longo do período especificado, fornecendo insights sobre como os resultados atuais se comparam com as metas e o desempenho histórico.

![pic1](https://github.com/filipegoncmartins/Income-Statement-DRE-for-Condominiums/assets/148718210/3518fdfd-518c-4a57-adf3-e471cc95bd20)

### Previsão Anual

Nesta página, uma previsão dos valores reais até o final do período anual é mostrada. Esta análise preditiva ajuda os usuários a antecipar os resultados de fim de ano com base nas tendências e dados de desempenho atuais, permitindo uma tomada de decisões e planejamento estratégico mais informados.

![pic1](https://github.com/filipegoncmartins/Income-Statement-DRE-for-Condominiums/assets/148718210/d687c43f-54a5-4127-8136-2783a3b31e19)


### Segmentação dos Shoppings

Nesta página, as receitas e despesas de todos os shoppings centers são exibidas lado a lado. O usuário tem a opção de visualizar tanto o mês selecionado quanto os valores acumulados através de um botão de alternância. Esse recurso permite uma comparação flexível e detalhada do desempenho financeiro em diferentes períodos, facilitando uma melhor compreensão do desempenho individual e geral dos shoppings centers.

![pic1](https://github.com/filipegoncmartins/Income-Statement-DRE-for-Condominiums/assets/148718210/df6e548e-b62f-4dd0-9b76-a6177249ca28)

### Consumo de Água e Eletricidade

Nesta visualização, o consumo histórico de água e eletricidade é detalhado, com uma comparação anual no mesmo gráfico, livremente escolhida pelo usuário. Ao lado, o consumo total é comparado com outros shoppings centers. Essa configuração oferece uma perspectiva clara sobre as tendências de uso de utilidades ao longo do tempo e como o consumo de cada shopping center se compara com os demais, auxiliando na gestão de recursos e análise de eficiência.

![pic1](https://github.com/filipegoncmartins/Income-Statement-DRE-for-Condominiums/assets/148718210/be2be4b8-ed6d-4ccb-8dac-ce3cf53c75d8)

# Insights

O arquivo publicado foi modificado para excluir nomes e valores sensíveis para visualização pública. No entanto, aqui estão os principais insights obtidos do arquivo original:

### [1] Tendências de Desempenho:

Os KPIs detalhados ao longo do tempo destacaram tendências significativas de desempenho, revelando quais áreas estão se destacando e quais precisam de melhorias. O arquivo original continha os nomes e despesas de todos os fornecedores, possibilitando uma análise rápida de quais fornecedores oferecem melhor custo-benefício.

### [2] Orçamento vs. Realizado:

Comparações mensais e acumuladas dos valores realizados versus orçados ajudaram a identificar variações e avaliar a saúde financeira. Isso ajudou a gestão a saber onde economizar para não ultrapassar o orçamento.

### [3] Previsões:

Previsões de fim de ano forneceram valiosas predições, auxiliando no planejamento estratégico e na alocação de recursos.

### [4] Consumo de Utilidades:

Dados históricos sobre o consumo de água e eletricidade, com comparações anuais, esclareceram a eficiência do uso de recursos e oportunidades potenciais de economia de custos. Esta visualização foi muito importante para identificar um problema estrutural no Shopping 2, observando o mês e ano em que a despesa aumentou e identificando a reforma que causou esse problema.

### [5] Comparações entre Shopping Centers:

Análise financeira lado a lado de todos os shoppings centers, tanto para meses selecionados quanto para períodos acumulados, facilitou o benchmarking e a avaliação de desempenho.

### [6] Proteção de Dados Sensíveis:

Garantir a proteção dos dados sensíveis enquanto ainda entrega insights significativos demonstrou um compromisso com a privacidade e segurança dos dados.
