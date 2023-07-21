---
title: Ensaio - Há um problema de informação na gestão da segurança da aviação civil?
# subtitle: 
tags:
  - science information
  - aviation
  - information retrieval
  - safety
  - risk management
  - controlled vocabulary
  - taxonomy
  - safety oversight
  - safety management systems
  - SMS
  - FAIR
  - ADREP
author: >-
    Gabriel Santiago Macedo^[Universidade Federal do Rio de
    Janeiro (UFRJ), Instituto Brasileiro de Informação em Ciência e
    Tecnologia (IBICT), Programa de Pós-Gradução em Ciência da 
    Informação (PPGCI), gabrielmacedo@discente.ibict.br, 
    [orcid:0000-0001-8845-7985](https://orcid.org/0000-0001-8845-7985);
    Disciplina - Perspectivas em Ciência da Informação, Docente - 
    Gustavo Henrique de Araújo Freire.]
# author:
#  - name: Gabriel Santiago Macedo
#    email: gabrielmacedo@discente.ibict.br
#    orcid_id: 0000-0001-8845-7985
#    affiliation: 1
# affiliation:
#  - name: 
#      Universidade Federal do Rio de Janeiro (UFRJ), Instituto 
#      Brasileiro de Informação em Ciência e Tecnologia (IBICT), 
#      Programa de Pós-Gradução em Ciência da Informação (PPGCI)
#    index: 1
date: 20/07/2023
abstract: >-
    Ensaio da disciplina "Perspectivas em Ciência da 
    Informação", Docente - Gustavo Henrique de Araújo Freire.
copyright:
  statement: >-
    © 2023 The author. Published under a CC BY-SA 4.0 license.
  year: 2023
  holder: Gabriel Santiago Macedo
license:
  - text: >-
      This work is licensed under a Creative Commons
      Attribution-ShareAlike 4.0 International License.
    type: open-access
    link: 'https://creativecommons.org/licenses/by-sa/4.0/'
  - >-
      The copyright holder grants the IBICT permission to 
      archive and post a copy of this paper in the journal 
      article databases.
bibliography: "https://raw.githubusercontent.com/gabrielmacedo/ci/main/biblioteca.bib"
csl: "https://github.com/gabrielmacedo/ci/raw/main/abnt.csl"
lang: pt-BR
draft: true
---

# Ensaio - Há um problema de informação na gestão da segurança da aviação civil?

1 - Motivações

Este ensaio parte de algumas inquietações enfrentadas durante os quase 10 anos de trabalho desse autor na Agência Nacional de Aviação Civil (ANAC). A partir dessa experiência podemos suscitar algumas questões. 

Há um problema de informação na gestão da segurança da aviação civil? Quais seriam esses problemas? Como a Ciência da Informação (CI), campo interdisciplinar dedicado a compreender o fenômeno informacional, pode contribuir para o entendimento dessas questões?

O objetivo desse ensaio é construir uma linha inicial de argumentação que seja útil para delinear o entendimento do projeto de pesquisa acadêmico e a introdução da dissertação do mestrado em CI no PPGCI, IBICT/UFRJ. 

Desse modo, serão observados os fatores antecedentes que lançam o tema central da pesquisa: a FAIRificação de vocabulários de aviação.

1.1 - Breve evolução da segurança na aviação

A evolução da segurança da aviação civil tem sido um trabalho contínuo que envolve a identificação e avaliação minuciosa dos riscos envolvidos no setor aéreo. 

Ao longo dos anos, a indústria da aviação tem se dedicado a aprimorar seus sistemas e processos para garantir um ambiente cada vez mais seguro. Isso inclui a análise de incidentes passados, a investigação de acidentes, a coleta de dados relevantes e a implementação de recomendações de segurança [@skySO].

Em termos gerais, a evolução da segurança da aviação ocorreu em fases cumulativas, onde a cada etapa subsequente, os estudos de segurança identificaram a necessidade de observar novos conjuntos de fatores para aprimorar os índices de segurança e reduzir acidentes. Ao longo do tempo, essas camadas sucessivas de melhorias foram implementadas para abordar novos desafios e garantir a contínua segurança das operações aéreas. 

Em resumo, no período após a Segunda Guerra Mundial, com a expansão da aviação comercial, e até os anos 1970, o foco dos estudos de segurança estava principalmente relacionados aos _fatores técnicos_, buscando melhorias nos equipamentos para aumentar a segurança das operações. A partir dos anos 1970, surgiu a era dos _fatores humanos_, com maior atenção para os erros cometidos pelas pessoas na operação das aeronaves. Nos anos 1990, a ênfase passou a ser nos _fatores organizacionais_, considerando a gestão das organizações e seu impacto na operação segura. Por volta dos anos 2010, iniciou-se a a chamada _era do sistema total_, com uma abordagem sistêmica e holística, buscando identificar fatores que possam ampliar a capacidade de desempenho de segurança do sistema de aviação como um todo.

A imagem a seguir, retirada do Doc 9859 (2018), ilustra essas etapas:

![A evolução da segurança da aviação [@doc9859, p. 26] (tradução livre).](https://github.com/gabrielmacedo/ci/assets/20596966/b4edf8b3-0a44-4651-9e51-d03433f21607)

Essa evolução demandou, cada vez mais, que os provedores de serviços e as autoridades da aviação civil colaborassem para estabelecer padrões e procedimentos comuns, bem como para promover uma cultura de segurança abrangente, envolvendo toda a cadeia afetada [@doc9866]. Quanto maior o número de fatores que passaram a ser observados, maior a necessidade de cruzar essas informações.

Nessa perspectiva, o ANEXO 19 da Organização da Aviação Civil Internacional (OACI), que orienta sobre o Gerenciamento da Segurança Operacional na aviação civil, indica obrigações e responsabilidades aos Estados nacionais e aos agentes envolvidos nas operações aéreas.

Tanto os provedores de serviços quanto as autoridades da aviação civil têm a responsabilidade de gerenciar os riscos, embora os tipos e abrangência dos perigos possam variar. Por exemplo, enquanto um provedor de serviços pode identificar riscos específicos relacionados à sua organização individual, uma autoridade de aviação civil pode identificar tendências emergentes em todo o sistema de aviação, com base em dados agregados de vários provedores de serviços.

Para possibilitar que os gestores de todas as organizações tomem decisões baseadas em riscos, é fundamental que essas entidades produzam, troquem e analisem dados de segurança para identificar os perigos presentes em seus respectivos sistemas. 

Dessa forma, o uso de terminologia e definições comuns passou a ser observado como essencial para possibilitar agregar e analisar dados entre diferentes agentes. Esse entendimento é materializado nos Programas de Segurança do Estado (_Safety State Program_ - SSP), que representam um conjunto integrado de regulamentos e atividades destinadas a melhorar a segurança, e que, dentre outras obrigações, exige o estabelecimento de mecanismos para _coleta, análise e troca de dados de segurança_ com outros Estados e com provedores de serviços [@doc9859; @skySSP].

Há um consenso entre as autoridades de aviação que o desenvolvimento de terminologias comuns pode facilitar a troca de informações para a gestão de riscos, sendo fundamental para identificar potenciais problemas e implementar medidas preventivas que garantam a integridade do transporte aéreo, solidificando assim a segurança como um pilar da aviação civil moderna.

> Taxonomias e definições comuns estabelecem uma linguagem padrão da indústria, melhorando assim a qualidade da informação e da comunicação. Com essa linguagem comum, a capacidade da comunidade de aviação de se concentrar em questões de segurança é bastante aprimorada [@icaoadrep] (tradução livre).

1.2 - A centralidade do problema de informação

Um dos problemas frequentes na gestão da segurança da aviação civil é o desafio de obter informações abrangentes e precisas sobre incidentes, riscos e tendências relacionados à segurança. 

Existem diversas razões para esse problema:

1) Subnotificação: nem todos os incidentes ou ocorrências de risco são devidamente relatados às autoridades responsáveis. Às vezes, indivíduos ou organizações podem hesitar em divulgar eventos adversos por medo de consequências legais ou impacto na reputação.

2) Cultura de sigilo: algumas companhias aéreas, provedores de serviços ou outros atores do setor podem ter uma cultura de sigilo em torno de questões de segurança. Isso pode dificultar a comunicação aberta e a troca de informações relevantes.

3) Falta de padrões e de sistemas integrados: a falta de padrões unificados e sistemas integrados de gerenciamento de segurança pode ocasionar a fragmentação dos dados. Isso dificulta a compilação e análise de informações em nível global e sistêmico.

4) Dificuldades na análise de dados: os sistemas de gestão da segurança da aviação civil podem não ter capacidade para acompanhar a quantidade crescente de dados disponíveis. A falta de recursos adequados ou tecnologias eficientes para analisar esses dados pode tornar difícil a identificação de padrões e tendências relevantes para mitigação de ocorrências.

5) Cooperação e compartilhamento limitados: algumas organizações podem hesitar em compartilhar informações de segurança com outras partes interessadas, como concorrentes ou reguladores, devido a segredos comerciais ou preocupações com a confidencialidade dos dados.

6) Dependência de trajetória tecnológica pelo meio de suporte da informação: a dependência de trajetória tecnológica baseada em sistemas criados para funcionar tendo o papel como meio de suporte e comunicação podem ser limitados em termos de eficiência, precisão e capacidade de coleta e análise de dados. Sistemas baseados em papel exigem processos manuais, o que pode ser lento e propenso a erros. Isso pode resultar em atrasos na comunicação de informações críticas. O armazenamento físico de dados em papel dificulta o compartilhamento rápido e abrangente de informações entre diferentes partes interessadas. Sistemas em papel tornam difícil lidar com grandes volumes de dados, dificultando a identificação de tendências e padrões.

Superar esses desafios requer esforços contínuos para promover uma cultura de segurança aberta e transparente, incentivar a comunicação e cooperação entre os agentes do setor, estabelecer padrões e sistemas integrados de coleta e análise de dados e garantir a confidencialidade necessária para proteger as partes envolvidas.

1.3 - A Ciência da Informação e o fenômeno informacional

De forma generalizada, podemos considerar que o fenômeno informacional, que compreende a criação, disseminação e uso da informações, tem se tornado cada vez mais complexo à medida que a quantidade de dados disponíveis aumenta exponencialmente com o avanço da internet e do uso de computadores pela sociedade.

Em razão dessa complexidade e considerando que a gestão da segurança da aviação civil depende do acesso e compartilhamento adequado de informações, como a CI pode contribuir para lidar com essas necessidades informacionais cada vez mais ubíquas?

Muito antes dessa difusão generalizada de informações, autores pioneiros na CI, como Paul Otlet [-@otlet1934] e Vannevar Bush [-@bush1945], já haviam se dedicado, respectivamente, ao estudo do fenômeno da organização do acesso à informação e à explosão informacional. Seus trabalhos vislumbravam formas de construir uma comunicação eficiente entre seres humanos, além de abordar a crescente necessidade de cuidar da informação mediada por máquinas. Eles foram visionários em idealizar estruturas e tecnologias pra facilitar o acesso e o compartilhamento de informações, contribuindo para a consolidação da CI como campo de estudo e pesquisa.

É interessante resgatar que o vínculo entre a CI e a aviação é bastante antigo. As experiências em torno do projeto Cranfield I e II e no desenvolvimento do sistema SMART, nos quais são propostos os conceitos de taxa de revocação (_recall ratio_) e de taxa de precisão (_precision ratio_), elaborados por Aitchison [-@aitchison1963], Cleverdon [-@cleverdon1967] e Salton [-@salton1965], já visavam identificar melhores abordagens para o problema de recuperar conteúdos, tendo como objeto a área de aviação e engenharia.

1.4 A necessária interdisciplinaridade do problema de informação

Quanto à caracterização de um problema de informação, salientamos a visão de interdisciplinaridade apresentada por Tefko Saracevic [-@saracevic1995], ao indicar que não devemos estudar propriamente assuntos na Ciência da Informação, mas sim problemas.

A abordagem centrada em problemas atinge diferentes temas e disciplinas, não respeitando o estabelecimento de fronteiras rígidas. A área de RI, para o autor, é tomada como o espaço de consolidação maior dessa interdisciplinaridade.

Assim, compreender o problema de informação na gestão da segurança da aviação civil requer, à área de RI, o entendimento sobre os avanços tecnológicos na comunicação e no processamento da linguagem. Tomamos aqui as indagações de Tefko Saracevic (1995) e buscaremos aplicá-las à aviação civil: quais métodos e técnicas que possibilitem a recuperação precisa e relevante de informações? Como se deu a organização intelectual da informação, a sua recuperação, interação e quais sistemas e técnicas foram usadas nesse processo?

A evolução tecnológica tem transformado significativamente a maneira como as pessoas se comunicam e interagem com a linguagem, apresentando oportunidades e demandas para aprimorar as abordagens existentes e desenvolver soluções que atendam às necessidades da sociedade.

A gestão da segurança da aviação é uma área complexa, na qual é necessário considerar o fenômeno informacional de forma abrangente e interdisciplinar. A coleta e análise de informações são elementos essenciais para garantir a segurança das operações aéreas, e a interdisciplinaridade desempenha um papel fundamental nesse processo. 

Reunir conhecimentos e perspectivas de diversas áreas relacionadas à aviação, como engenharia aeronáutica, psicologia, ciência da informação, direito aeronáutico e outros, é uma ação importante para compreender as complexidades do sistema de aviação, identificar riscos potenciais e propor soluções.

O desenvolvimento contínuo das tecnologias da informação e comunicação trouxe consigo uma transformação na maneira como as pessoas se comunicam e como interagem com a linguagem. Essa evolução tecnológica exige uma compreensão aprofundada dos avanços emergentes e das alternativas disponíveis para a recuperação de informações.

1.5 - A adoção dos princípios FAIR como resposta interdisciplinar

Os princípios FAIR surgiram como uma resposta ao desafio de localizar, reutilizar e processar dados por máquinas em diversas áreas da ciência. "FAIR" é um acrônimo para "Findable" (Encontrável), "Accessible" (Acessível), "Interoperable" (Interoperável) e "Reusable" (Reutilizável) [@wilkinson2016].

Esses princípios foram desenvolvidos em 2016 por um grupo de especialistas, de diferentes áreas, com o objetivo de estabelecer diretrizes para tornar os dados científicos mais úteis em diferentes contextos.

Em síntese, o conjunto de princípios FAIR foi proposto para permitir uma infraestrutura para a reutilização segura de dados [@henning2019]. Nos parece que esse arcabouço pode ser adotado na aviação civil, especialmente para os dados de interesse da gestão da segurança, visando mitigar alguns dos problemas enfrentados e apresentados nesse ensaio.

A aplicação dos princípios FAIR pode trazer benefícios para a gestão da segurança da aviação, que incluem:

1) Encontrabilidade: tornar os dados de segurança da aviação facilmente encontráveis para facilitar uma análise abrangente e e a identificação de tendências e padrões que possam contribuir para o aprimoramento da segurança. Ao garantir que os dados estejam adequadamente descritos e indexados, pesquisadores e profissionais da aviação podem localizar e acessar informações relevantes com mais facilidade.

2) Acessibilidade: a disponibilização de dados em formatos abertos e compreensíveis, sem restrições indevidas, permite que os envolvidos na gestão da segurança da aviação tenham acesso aos dados necessários para tomar decisões mais bem informadas.

3) Interoperabilidade: a aplicação dos princípios de interoperabilidade pode permitir a combinação de dados de diferentes fontes, como provedores de serviços de aviação, autoridades reguladoras e órgãos de investigação, para análises mais abrangentes e abordagens colaborativas. Dados estruturados e padronizados facilitam a integração e análise conjunta, auxiliando na identificação de problemas e na implementação de medidas preventivas.

4) Reutilizabilidade: a reutilização de dados de segurança da aviação é importante para garantir a aprendizagem e aprimoramento contínuo dos processos de gestão de segurança. A disponibilização de dados com licenças claras e adequadas permite que outros pesquisadores e profissionais possam reutilizar os dados para validação de resultados, estudos comparativos e pesquisas adicionais.

Portanto, aplicar os princípios FAIR aos dados de interesse da gestão da segurança da aviação civil pode promover maior transparência, colaboração e avanço na identificação de riscos e na implementação de medidas efetivas de segurança.

Considerando que a necessidade de uso de dados para a gestão da segurança na aviação se assemelha ao ambiente de compartilhamento de dados científicos, quais boas práticas de aplicação dos princípios FAIR são pertinentes e podem ser aproveitadas? 

1.6 - O uso de vocabulários FAIR

Ao investigar os requisitos para tornar os dados FAIR, um dos pontos críticos é a disponibilidade de vocabulários que também atendam aos princípios FAIR. Os vocabulários FAIR são conjuntos de termos padronizados e bem definidos que permitem uma comunicação eficiente e consistente entre diferentes sistemas e fontes de dados [@cox2021].

Ou seja, a disponibilidade de um conjunto de metadados que possa ser vinculado aos dados e adequadamente referenciado, seguindo as boas práticas de publicação, está na raiz da possibilidade de tornar dados interoperáveis e legíveis por máquinas. Eles são essenciais para garantir que os dados sejam compreensíveis e interpretados corretamente, independentemente do contexto em que serão usados.

Algumas características sobre os vocabulários FAIR:

1) Padronização: os vocabulários FAIR seguem padrões definidos que são aceitos e utilizados em um determinado campo. Isso permite que os termos usados para descrever os dados sejam consistentes, evitando ambiguidades na interpretação.

2) Compartilhamento e integração de dados: o uso de vocabulários FAIR facilitar a integração entre diferentes fontes de dados e sistemas, permitindo que os usuários combinem e analisem dados de modo mais abrangente.

3) Reutilização: o uso de vocabulários FAIR facilita a reutilização de dados por terceiros, pois os dados são apresentados de forma bem documentada, contribuindo para os usuários entenderem e o reaproveitarem em seus próprios trabalhos.

4) Descoberta de dados: vocabulários FAIR também são importantes para tornar os dados encontráveis, pois facilitam a indexação e recuperação de informações por meio de sistemas de busca e catálogos. Isso é crucial para a localização eficiente de dados relevantes em meio a um grande volume de informações disponíveis.

1.7 - Como estão disponibilizados os vocabulários para informações de segurança da aviação?

Profissionais da aviação têm enfatizado a importância da compatibilização de termos e a criação de um vocabulário comum para marcar os dados relevantes à gestão da segurança no setor. Essa necessidade de padronização é crucial para garantir a eficácia e a precisão na coleta, análise e compartilhamento de informações relacionadas à segurança da aviação.

Ao estabelecer um vocabulário padronizado, os profissionais podem aprimorar a comunicação e a compreensão dos dados, promovendo uma gestão mais abrangente e colaborativa dos aspectos de segurança na indústria aérea.

Diversas iniciativas foram encampadas ao longo dos últimos anos na produção de terminologias comuns para o setor aéreo. Grupos de trabalho internacionais foram montados em torno de dados de metereológicos, dados de navegação, dados de infraestrutura e outros. 

Um esforço foi empreendido para criar uma taxonomia comum, ou seja, um vocabulário controlado de tipo hierárquico, destinado a eventos de segurança no setor da aviação. Esse conjunto de documentos, amplamente conhecido como taxonomia ADREP (acrônimo para _Accident/Incident Data Reporting_), foi disponibilizado em formato PDF e engloba uma compilação abrangente de atributos e valores relacionados a eventos de segurança [@icaoadrep].

A última versão da taxonomia ADREP, datada do ano de 2013, divulgado pela Organização da Aviação Civil Internacional (OACI), ente das Nações Unidas esponsável pela promoção do desenvolvimento seguro e ordenado da aviação civil mundial, representa um importante avanço na padronização de informações relevantes em relação à segurança. Foram padronizadas informações sobre: categorias de aeronaves, operações, danos sofridos, fatores descritivos, fatores explicativos, eventos e outros. 

Diferente de outras iniciativas do setor aéreo que já contam com um vocabulário publicado seguindo alguns princípios FAIR, a taxonomia ADREP é um conjunto de documentos em PDF, em formato tabular, não legível por máquina. Não diferindo muito de um dado que fosse disponibilizado em papel.

É essa lacuna que o nosso trabalho de pesquisa pretende explorar. Por que tornar FAIR os dados de aviação? Quais os desafios e benefícios de disponibilizar dados de aviação seguindo os princípios FAIR? Como tornar FAIR um vocabulário controlado de gestão da segurança de aviação? 

2 - Considerações finais

É comum encontrar documentos, orientações e dados técnicos relacionados à segurança da aviação em formatos não padronizados e não legíveis por máquinas. Isso resulta em uma integração ineficiente dessas informações, especialmente quando consideramos o estado atual do desenvolvimento de tecnologias voltadas para a interoperabilidade. 

A falta de padronização e acessibilidade desses dados dificulta a sua integração em sistemas automatizados e a colaboração entre diferentes agentes da indústria. Em um cenário em que as tecnologias estão cada vez mais orientadas à interoperabilidade, a adoção de formatos mais adequados para divulgar informações de segurança da aviação é crucial para promover uma gestão mais eficiente e segura em toda a indústria.

Diante desses indícios, percebe-se a pertinência de avaliar a aplicação e a utilidade dos princípios FAIR para os dados de interesse da gestão da segurança da aviação. Com isso, se buscará com a pesquisa responder:

1) Qual a importâncias da adoção dos princípios FAIR para dados de segurança de aviação?
2) Como FAIRificar (derivado do termo usal em inglês _FAIRification_) um vocabulário controlado de aviação?

O setor aéreo é um sistema complexo intensivo em informações. Descobrir lacunas de conhecimento relacionadas aos problemas específicos de informação dessa indústria nos parece uma atividade significativa e possível de ser realizada no PPGCI IBICT/UFRJ.

Aprofundar o entendimento sobre os arranjos que envolvem o compartilhamento de informações possibilitará uma avaliação crítica das limitações e das contribuições dos princípios FAIR, além de ampliar a capacidade de identificar áreas não exploradas, desafios sem soluções e suscitar perguntas que demandem investigações mais aprofundadas.

## Referências
