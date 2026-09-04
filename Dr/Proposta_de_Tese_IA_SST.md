# Proposta de Tese de Doutorado em Saúde Pública

## Inteligência artificial explicável para a vigilância preditiva de riscos ocupacionais e a prevenção de agravos relacionados ao trabalho

**Candidato(a):** [Nome do(a) candidato(a)]  
**Programa:** Doutorado em Saúde Pública  
**Instituição:** Christian Business School  
**Linha de pesquisa principal:** Vigilância em saúde  
**Linhas de interface:** Gestão e Políticas públicas de saúde; Educação e saúde  
**Duração estimada:** 48 meses  
**Versão:** Proposta preliminar para discussão com a coordenação e possível orientador(a)

## 1. Resumo

A saúde e segurança do trabalho constitui um campo estratégico da Saúde Pública, pois busca promover a saúde dos trabalhadores, prevenir acidentes e doenças ocupacionais e intervir sobre os determinantes presentes nos processos e ambientes de trabalho. A incorporação de inteligência artificial (IA) pode ampliar a capacidade de vigilância ao identificar padrões de risco, antecipar situações críticas e apoiar a priorização de ações preventivas. Entretanto, modelos algorítmicos aplicados a dados ocupacionais também podem reproduzir desigualdades, produzir classificações pouco transparentes, intensificar a vigilância sobre trabalhadores e expor dados pessoais sensíveis.

Esta tese propõe desenvolver e avaliar um modelo de IA explicável para apoiar a vigilância preditiva de riscos ocupacionais e a prevenção de agravos relacionados ao trabalho. O estudo adotará abordagem de métodos mistos, combinando análise retrospectiva de dados secundários ou institucionais anonimizados, desenvolvimento e validação de modelos preditivos, avaliação de explicabilidade e equidade, além de entrevistas com trabalhadores, profissionais de saúde ocupacional, gestores e representantes de trabalhadores. O produto esperado será um protótipo de apoio à decisão, acompanhado de um protocolo de governança, proteção de dados, participação dos trabalhadores e educação em saúde. A proposta não pretende substituir o julgamento de profissionais nem automatizar decisões disciplinares, médicas ou trabalhistas. Seu objetivo é oferecer evidências para ações coletivas de prevenção, vigilância e gestão em saúde pública.

**Palavras-chave:** inteligência artificial; saúde do trabalhador; segurança do trabalho; vigilância em saúde; aprendizado de máquina; equidade; proteção de dados.

## 2. Delimitação temática e aderência ao programa

O manual do programa apresenta a **Vigilância em saúde** como uma das linhas de pesquisa e inclui componentes curriculares diretamente relacionados a esta proposta, como Epidemiologia, Estatística Aplicada à Saúde, Avaliação de Programas e Serviços de Saúde, Pesquisa Qualitativa e Quantitativa, Políticas Públicas em Saúde e Projetos de Pesquisa I e II [1]. A tese será delimitada ao uso responsável de IA como instrumento de apoio à vigilância de riscos ocupacionais.

Para garantir viabilidade, o estudo deverá selecionar um recorte ocupacional e territorial após o diagnóstico de disponibilidade e qualidade dos dados. A opção preferencial será investigar trabalhadores de um setor com exposição relevante a riscos físicos, ergonômicos, psicossociais ou de acidentes, como saúde, indústria, logística, construção civil ou serviços públicos. O setor definitivo será escolhido em conjunto com a orientação, considerando acesso institucional, qualidade dos registros, relevância epidemiológica e aprovação ética.

## 3. Problema de pesquisa

Os serviços de saúde ocupacional e de vigilância frequentemente dispõem de registros fragmentados sobre acidentes, afastamentos, exposições, condições de trabalho, notificações e medidas preventivas. Essa fragmentação dificulta a identificação precoce de padrões de risco e a priorização de inspeções, ações educativas e intervenções coletivas. Ao mesmo tempo, a simples aplicação de algoritmos pode gerar riscos de discriminação, opacidade e uso indevido de informações individuais.

O problema central desta pesquisa é compreender se e sob quais condições um modelo de IA explicável pode apoiar a identificação antecipada de riscos ocupacionais e melhorar a priorização de ações preventivas, sem violar direitos dos trabalhadores ou transferir decisões de saúde e gestão para um sistema automatizado.

## 4. Pergunta de pesquisa

**Um modelo de inteligência artificial explicável, construído com dados ocupacionais anonimizados e submetido à avaliação de desempenho, equidade, utilidade e governança, pode apoiar a vigilância em saúde do trabalhador e a prevenção de agravos relacionados ao trabalho de modo mais oportuno e responsável do que os procedimentos convencionais de priorização?**

## 5. Hipóteses

A hipótese principal é que um modelo de IA explicável poderá identificar padrões associados a eventos ocupacionais adversos com desempenho discriminativo e calibração suficientes para apoiar a priorização de ações preventivas, desde que seja utilizado como ferramenta de apoio e submetido a supervisão humana.

A segunda hipótese é que a combinação entre desempenho estatístico, explicações compreensíveis e participação de trabalhadores e profissionais produzirá maior aceitabilidade e utilidade prática do que um modelo baseado apenas em acurácia preditiva.

A terceira hipótese é que diferenças de qualidade dos registros e de exposição entre grupos ocupacionais poderão gerar desempenho desigual. Auditorias de equidade, análise de subgrupos e governança participativa serão necessárias para reduzir esse risco.

## 6. Objetivos

### 6.1 Objetivo geral

Desenvolver e avaliar um modelo de inteligência artificial explicável para apoiar a vigilância preditiva de riscos ocupacionais e a prevenção de agravos relacionados ao trabalho, incorporando critérios de validade, equidade, proteção de dados, participação dos trabalhadores e utilidade para a gestão em saúde pública.

### 6.2 Objetivos específicos

1. Mapear evidências científicas e normativas sobre aplicações de IA em saúde e segurança do trabalho, com atenção a benefícios, limitações, riscos éticos e requisitos de governança.
2. Caracterizar os dados disponíveis sobre exposições, acidentes, doenças, afastamentos e medidas preventivas no contexto selecionado.
3. Construir e comparar modelos preditivos para identificar situações ou unidades com maior probabilidade de agravos ocupacionais em horizonte temporal definido.
4. Avaliar desempenho, calibração, robustez, interpretabilidade e equidade do modelo entre grupos ocupacionais e sociodemográficos, quando os dados permitirem essa análise.
5. Investigar a percepção de trabalhadores, profissionais de saúde ocupacional, gestores e representantes laborais sobre utilidade, riscos, transparência e aceitabilidade do sistema.
6. Elaborar um protocolo de implementação responsável, incluindo governança de dados, supervisão humana, comunicação dos resultados, educação em saúde e monitoramento pós-implementação.

## 7. Justificativa

A Organização Internacional do Trabalho destaca que automação, sistemas inteligentes de monitoramento e digitalização podem reduzir exposições perigosas, prevenir lesões e melhorar as condições de trabalho, mas também podem criar novos riscos e lacunas regulatórias [2]. Uma revisão recente sobre IA em saúde e segurança ocupacional identifica aplicações como monitoramento contínuo por sensores e dispositivos vestíveis, ao mesmo tempo em que alerta para preocupações éticas, privacidade e necessidade de políticas e capacitação [3].

A relevância desta tese decorre, portanto, da necessidade de estudar a IA não apenas como tecnologia de previsão, mas como intervenção de Saúde Pública. O valor do sistema deverá ser medido pela sua capacidade de apoiar prevenção coletiva e decisões transparentes, e não somente pela acurácia do algoritmo. A pesquisa também poderá contribuir para a vigilância em saúde do trabalhador ao propor uma forma de integrar dados, gerar alertas interpretáveis e direcionar recursos preventivos para contextos de maior risco.

A proposta possui relevância científica, porque articula epidemiologia ocupacional, aprendizado de máquina explicável e avaliação de implementação. Possui relevância social, porque coloca a proteção da saúde e a participação dos trabalhadores no centro da inovação. Possui relevância para políticas públicas, porque pode gerar critérios para adoção segura de ferramentas algorítmicas em serviços de vigilância e gestão da saúde do trabalhador.

## 8. Referencial conceitual resumido

A tese adotará quatro eixos articulados. O primeiro é a **saúde do trabalhador como campo da Saúde Pública**, orientado à promoção, proteção, prevenção, vigilância e intervenção sobre as relações entre trabalho e processo saúde-doença. No Brasil, a Vigilância em Saúde do Trabalhador integra o Sistema Nacional de Vigilância em Saúde e reúne ações de promoção, prevenção, investigação e intervenção sobre riscos e agravos relacionados ao trabalho [4].

O segundo eixo é a **vigilância preditiva**, entendida como uso de dados históricos e atuais para estimar a probabilidade de eventos ou condições de risco e antecipar ações preventivas. A previsão não será interpretada como diagnóstico individual nem como prova de responsabilidade do trabalhador ou do empregador.

O terceiro eixo é a **IA explicável**, isto é, o conjunto de métodos que permite apresentar, em linguagem compreensível, os principais fatores que contribuíram para uma estimativa algorítmica. A explicação deverá servir à investigação e à prevenção, sem expor indevidamente indivíduos ou transformar correlações em relações causais.

O quarto eixo é a **governança responsável de dados e algoritmos**. Dados de saúde são pessoais sensíveis e exigem proteção reforçada no tratamento [5]. As orientações da Organização Mundial da Saúde ressaltam a necessidade de transparência, responsabilidade, inclusão, equidade, segurança e supervisão humana no uso de IA em saúde [6].

## 9. Metodologia

### 9.1 Desenho do estudo

Será realizado um estudo de métodos mistos, em três fases integradas: revisão e mapeamento do problema; desenvolvimento e validação quantitativa do modelo; e avaliação qualitativa e de implementação. O desenho poderá ser ajustado após a definição do campo e a avaliação da disponibilidade dos dados.

### 9.2 Fase 1 — Revisão e diagnóstico do contexto

Será conduzida uma revisão de escopo ou revisão sistematizada da literatura sobre IA aplicada à saúde e segurança do trabalho. A estratégia incluirá bases bibliográficas pertinentes e documentos de organismos oficiais. Serão analisados os tipos de dados utilizados, desfechos, métodos de IA, métricas de desempenho, mecanismos de explicação, impactos sobre trabalhadores e medidas de governança.

Paralelamente, será realizado diagnóstico do fluxo de dados no campo escolhido. Serão examinados os conceitos utilizados, a completude, a consistência, a temporalidade, a duplicidade, a ausência de dados e a possibilidade de vinculação segura entre bases. Essa etapa determinará o desfecho e as variáveis efetivamente elegíveis.

### 9.3 Fase 2 — Desenvolvimento e validação do modelo

O desfecho primário será definido como a ocorrência de um agravo ou condição de risco ocupacional previamente especificada, por exemplo, acidente registrável, afastamento relacionado ao trabalho, doença ocupacional notificada ou conjunto de eventos de segurança. O horizonte de previsão poderá ser mensal, trimestral ou semestral, conforme a frequência e a qualidade dos registros.

Os dados serão previamente minimizados, anonimizados ou pseudonimizados conforme avaliação ética e de proteção de dados. O conjunto de dados será separado temporalmente em treinamento, validação e teste, evitando vazamento de informação entre os períodos. Serão comparados modelos de referência, como regressão logística ou modelos de sobrevivência, com modelos de aprendizado de máquina adequados ao volume e à estrutura dos dados.

A avaliação incluirá área sob a curva ROC ou precisão-revocação, sensibilidade, especificidade, valor preditivo positivo, calibração, análise de decisão e desempenho em subgrupos. A escolha das métricas será compatível com a finalidade preventiva e com o custo relativo de falsos negativos e falsos positivos. Também serão avaliadas estabilidade temporal, robustez a dados ausentes e explicações locais e globais.

O modelo não será utilizado para classificar pessoas como “inseguras”, prever produtividade, recomendar sanções, decidir contratação ou demissão, negar atendimento ou substituir avaliação clínica e profissional. A unidade preferencial de previsão será a exposição, atividade, setor ou unidade de trabalho, pois o objetivo é orientar medidas coletivas de prevenção.

### 9.4 Fase 3 — Avaliação qualitativa e de implementação

Serão realizadas entrevistas semiestruturadas ou grupos focais com participantes selecionados por amostragem intencional. O estudo buscará incluir trabalhadores de diferentes funções, profissionais de segurança e saúde do trabalho, gestores, profissionais de vigilância e representantes sindicais ou de comissões internas, quando disponíveis.

A análise temática investigará compreensão das explicações, confiança, receio de vigilância, percepção de justiça, utilidade para prevenção, barreiras de implementação e condições necessárias para o uso responsável. Os resultados qualitativos serão triangulados com os achados quantitativos e utilizados para revisar o protótipo e o protocolo de governança.

### 9.5 População, campo e critérios

A população e o campo serão definidos após a análise de viabilidade. A seleção deverá privilegiar um contexto com relevância epidemiológica, registros suficientes, parceria institucional formal e possibilidade de participação dos trabalhadores. Serão incluídos registros referentes ao período definido no protocolo e participantes adultos que possam consentir livremente.

Serão excluídos dados sem base legal ou autorização institucional, registros cuja utilização não possa ser adequadamente protegida e informações desnecessárias para o objetivo da pesquisa. Nenhuma decisão individual de saúde, emprego, remuneração ou disciplina será tomada com base no modelo.

### 9.6 Aspectos éticos e de proteção de dados

O projeto será submetido ao sistema de avaliação ética aplicável antes da coleta ou utilização de dados identificáveis. Serão observados consentimento ou hipótese legal adequada, minimização de dados, controle de acesso, registro de operações, segregação de identificadores, criptografia, plano de retenção e descarte, avaliação de riscos e comunicação transparente aos participantes.

A governança incluirá definição de responsabilidades, documentação do ciclo de vida do modelo, auditorias periódicas, mecanismo para contestação de resultados, revisão humana obrigatória e procedimento para suspender o uso quando houver evidência de dano, erro sistemático ou desempenho inadequado. As explicações serão apresentadas como apoio à investigação, não como causalidade comprovada.

## 10. Resultados e produtos esperados

Espera-se produzir uma revisão de evidências sobre IA e SST; um diagnóstico da qualidade e governança dos dados ocupacionais; um modelo preditivo validado internamente e acompanhado de análise de equidade; um protótipo de painel ou relatório de apoio à vigilância; um protocolo de implementação responsável; materiais educativos para profissionais e trabalhadores; e artigos científicos compatíveis com as exigências de publicação do programa.

O principal resultado aplicado será uma estrutura de decisão que permita transformar sinais de risco em ações preventivas verificáveis, como inspeção técnica, adequação de processo, treinamento, reorganização do trabalho, melhoria de equipamentos ou encaminhamento para vigilância. O modelo não será considerado bem-sucedido se apenas gerar alertas; será necessário demonstrar que os alertas são compreensíveis, acionáveis e compatíveis com os direitos dos trabalhadores.

## 11. Contribuições esperadas

No campo científico, a tese poderá integrar métodos de epidemiologia, ciência de dados e pesquisa qualitativa em uma avaliação de IA orientada à saúde coletiva. No campo institucional, poderá oferecer critérios para selecionar dados, avaliar modelos e acompanhar impactos. No campo social, poderá fortalecer a prevenção e a participação dos trabalhadores, reduzindo o risco de uso punitivo ou meramente fiscalizatório da tecnologia.

A tese também poderá contribuir para a formulação de políticas públicas ao propor requisitos mínimos de transparência, supervisão humana, auditoria de equidade, segurança da informação, educação em saúde e avaliação contínua para sistemas de IA aplicados à saúde e segurança do trabalho.

## 12. Limitações previstas

A disponibilidade e a qualidade dos dados poderão limitar a precisão e a generalização do modelo. Registros administrativos podem conter subnotificação, mudanças de classificação e desigualdades de acesso aos serviços. A validação em uma única instituição ou setor poderá reduzir a transferência dos resultados para outros contextos. Além disso, uma associação preditiva não comprova causalidade. Essas limitações serão explicitadas e consideradas na interpretação e na decisão sobre eventual implementação.

## 13. Cronograma preliminar — 48 meses

| Etapa | Meses | Produto principal |
|---|---:|---|
| Revisão bibliográfica, refinamento do problema e plano analítico | 1–6 | Protocolo de revisão e versão consolidada do projeto |
| Qualificação, parcerias e diagnóstico de dados | 7–12 | Relatório de viabilidade e dicionário de dados |
| Aprovação ética e preparação dos dados | 13–18 | Plano de governança e base analítica protegida |
| Desenvolvimento dos modelos | 19–26 | Modelos candidatos e relatório de desempenho |
| Validação, explicabilidade e análise de equidade | 27–32 | Modelo avaliado e relatório técnico |
| Entrevistas, grupos focais e avaliação de implementação | 33–37 | Resultados qualitativos e matriz de requisitos |
| Integração dos resultados e elaboração dos produtos | 38–42 | Protocolo de implementação e manuscritos |
| Redação, submissão de artigos e defesa | 43–48 | Tese final, artigos e apresentação de defesa |

## 14. Considerações finais

A proposta posiciona a IA como instrumento de fortalecimento da vigilância em saúde do trabalhador, e não como substituta da responsabilidade institucional, da avaliação profissional ou da participação social. O foco em explicabilidade, equidade, proteção de dados e prevenção coletiva busca responder simultaneamente à oportunidade tecnológica e aos riscos associados à digitalização do trabalho.

Antes da versão definitiva, recomenda-se ajustar o recorte ocupacional, a instituição parceira, o desfecho primário e a estratégia de acesso aos dados em diálogo com a coordenação e o(a) possível orientador(a). Esses ajustes não alteram o núcleo da proposta, mas serão decisivos para sua viabilidade metodológica e ética.

## Referências

[1]: file:///home/ubuntu/upload/DoutoradoemSaúdePúblicaChristianBusinessSchool.pdf "Doutorado em Saúde Pública: Manual do Estudante"

[2]: https://www.ilo.org/publications/revolutionizing-health-and-safety-role-ai-and-digitalization-work "Revolutionizing health and safety: The role of AI and digitalization at work"

[3]: https://pmc.ncbi.nlm.nih.gov/articles/PMC11181216/ "Artificial Intelligence and Occupational Health and Safety, Benefits and Drawbacks"

[4]: https://www.gov.br/saude/pt-br/composicao/svsa/saude-do-trabalhador/vigilancia-em-saude-do-trabalhador-vigisat "Vigilância em Saúde do Trabalhador — Ministério da Saúde"

[5]: https://www.gov.br/mcti/pt-br/acesso-a-informacao/lei-geral-de-protecao-de-dados-pessoais-lgpd "Lei Geral de Proteção de Dados Pessoais — Ministério da Ciência, Tecnologia e Inovação"

[6]: https://www.who.int/publications/i/item/9789240029200 "Ethics and governance of artificial intelligence for health: WHO guidance"
