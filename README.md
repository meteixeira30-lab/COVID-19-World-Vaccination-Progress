# Análise Global de Vacinação: Healthcare & Occupational Analytics

Este projeto utiliza Big Data real para investigar o progresso da imunização contra a COVID-19 em escala global, com um foco analítico e crítico no cenário brasileiro, na eficiência do SUS (Sistema Único de Saúde) e no impacto das decisões de gestão pública na saúde coletiva.

---

## Abordagem Multidisciplinar Única

O diferencial deste trabalho é a convergência entre a **Ciência de Dados** e a minha fundamentação em **Terapia Ocupacional** e **Epidemiologia**. Os números aqui representam não apenas registros matemáticos, mas sim demarcadores de realidades sociais:

* **Epidemiologia & Gestão Pública:** Análise de curvas normalizadas (taxas por milhão) e médias móveis para auditar a velocidade de resposta do Programa Nacional de Imunizações (PNI). Investigação do nexo de causalidade entre os atrasos diplomáticos/políticos na aquisição de insumos (IFA) no início de 2021 e o subsequente colapso hospitalar causado pela variante Gama (P.1).
* **Terapia Ocupacional:** Interpretação do ritmo vacinal sob a ótica dos **Determinantes Sociais da Saúde (DSS)**. O atraso na imunização é analisado como um vetor de **Injustiça Ocupacional**, privando populações vulneráveis do engajamento seguro em suas rotinas, provocando rupturas cotidianas violentas pelo luto e gerando uma demanda em massa por reabilitação funcional no SUS (Síndrome Pós-COVID).

---

## Embasamento Teórico e Análise de Governança (SUS & TO)

Para garantir o rigor científico e afastar vieses político-partidários, o comportamento das séries temporais de vacinação neste projeto é analisado sob a ótica da **avaliação de políticas públicas, governança institucional e impactos no cotidiano**.

### 1. Matriz de Impacto das Políticas de Saúde (PNS & APS)

| Dimensão Analítica | Fato Político / Normativo | Impacto Observado nos Dados (`df`) | Referência Científica Base |
| :--- | :--- | :--- | :--- |
| **Financiamento da APS** | Transição para o *Programa Previne Brasil* (Portaria nº 2.979/2019), alterando os critérios de repasse financeiro municipal. | Oscilações e assimetrias na prontidão vacinal inicial entre municípios de pequeno e grande porte. | GIOVANELLA, L. et al. *A Atenção Primária à Saúde na pandemia de COVID-19: resiliência e retrocessos*. Cadernos de Saúde Pública, 2021. |
| **Coordenação da PNS** | Fragmentação regulatória e falta de sincronia nas diretrizes tripartites entre Ministério da Saúde, CONASS e CONASEMS. | Gargalos na cadeia de suprimentos e platôs prolongados na taxa `daily_vaccinations` por falta de calendário unificado. | CAMPOS, G. W. S. *O SUS virado pelo avesso: a gestão da pandemia*. Ciência & Saúde Coletiva, 2021. |
| **Resiliência da ESF** | Histórico de capilaridade e territorialização da Estratégia Saúde da Família e do Programa Nacional de Imunizações (PNI). | Crescimento exponencial vertical da curva `total_vaccinations_per_hundred` assim que os insumos foram disponibilizados. | PAIM, J. S. *O Sistema Único de Saúde (SUS) aos 30 anos*. Revista de Saúde Pública, 2018. |

### 2. Fundamentação na Terapia Ocupacional Coletiva

* **Injustiça e Privação Ocupacional:** O atraso na aquisição de lotes de vacinas e insumos (IFA) no início de 2021 expôs assimetricamente a população dependente de transporte público e do trabalho informal. A falta de proteção vacinal rápida atuou como um vetor de privação, retirando do sujeito a autonomia sobre o engajamento seguro em suas Atividades de Vida Diária (AVDs) e participação social.
  * *Referência:* MALFITANO, A. P. S. et al. *Terapia Ocupacional Social: desdobramentos conceituais e territoriais*. Cadernos de Terapia Ocupacional da UFSCar, 2019.
* **Ruptura de Cotidianos e Luto Coletivo:** O estouro da curva de letalidade antes da consolidação da barreira vacinal desestruturou dinâmicas familiares, interrompeu papéis ocupacionais (perda de provedores e cuidadores) e gerou quadros de desorganização da rotina diária das comunidades.
  * *Referência:* BENETTON, J. *O cotidiano como foco da atenção em Terapia Ocupacional*. Revista de Terapia Ocupacional da USP, 2010.
* **Reabilitação Funcional no SUS (Pós-COVID):** O volume acumulado de casos graves traduziu-se na sobrecarga direta das equipes de TO na média e alta complexidade, exigindo intervenções focadas na conservação de energia, treino de AVDs e reorganização de rotinas de sobreviventes da intubação.
  * *Referência:* NOTA TÉCNICA ATOB/RENASTO. *Diretrizes para atuação da Terapia Ocupacional na reabilitação pós-COVID-19*, 2021.

---

## Tecnologias e Metodologia

* **Python (Pandas, Seaborn, Matplotlib):** Pipeline completo de Engenharia e Análise Exploratória de Dados (EDA).
* **Análise de Séries Temporais:** Tratamento de dados temporais e aplicação de técnicas de suavização (Média Móvel de 7 dias) para eliminar ruídos de subnotificação aos finais de semana.
* **Ambiente de Desenvolvimento:** Inicializado no Kaggle e otimizado no **Google Colab** para garantir reprodutibilidade e gerenciamento eficiente de memória.

---

##  Principais Visualizações e Insights

1.  **Velocidade de Cobertura Vacinal (Média Móvel):** Gráficos de linha comparativos que expõem matematicamente a perda da "janela de oportunidade" do Brasil no fim de 2020 e a velocidade de recuperação da curva devido à capilaridade da Atenção Primária à Saúde (APS).
2.  **Sazonalidade e Gargalos Logísticos:** Análise do volume de aplicações por dia da semana, comprovando estatisticamente as barreiras de acesso e operação dos sistemas de saúde aos sábados e domingos.
3.  **Portfólio de Imunizantes:** Mapeamento da diversificação de vacinas (mRNA vs. Vetor Viral/Inativadas) e como decisões de saúde pública estratégica impactam a equidade na distribuição geográfica de insumos.

---

##  Como Visualizar o Projeto

O notebook completo, contendo todo o código documentado, gráficos interativos e as discussões teóricas aprofundadas, pode ser acessado através dos links abaixo:

* **Repositório de Desenvolvimento no GitHub:** [Aba do Projeto no GitHub](https://github.com/meteixeira30-lab/COVID-19-World-Vaccination-Progress)
