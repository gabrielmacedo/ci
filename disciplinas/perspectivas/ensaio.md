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

Este ensaio parte de algumas inquietações enfrentadas durante os quase 10 anos de trabalho desse autor na agência reguladora de aviação civil no Brasil. A partir dessa experiência podemos suscitar algumas questões. Há um problema de informação na gestão da segurança da aviação civil? Quais seriam esses problemas? Como a Ciência da Informação (CI), campo interdisciplinar dedicado a compreender o fenômeno informacional, pode contribuir para a compreensão dessas questões?

Tópicos:

- É comum a divulgação de documentos, padrões, orientações e dados técnicos relacionados à segurança da aviação em formatos não legíveis por máquinas, tornando a integração dessas informações ineficiente em contraste ao estado atual do desenvolvimento de tecnologias pensadas para a interoperabilidade.

- O estudo das fragilidades do sistema de segurança de aviação permite agir em relação a problemas sistêmicos e à gestão de riscos, promovendo recomendações práticas aos agentes do setor aéreo. É a ação sistemática de investigar e aplicar recomendações que assegura a aprendizagem e auxilia na prevenção de futuras ocorrências.

- Dentre as propostas de adoção e massificação do uso das tecnologias da web para o tratamento de dados, os princípios FAIR (acrônimo para _Findable, Accessible, Interoperable and Reusable_) reúnem boas práticas e recomendações para a localização, acessibilidade, interoperabilidade e reutilização de dados.

- O conjunto de princípios FAIR foi proposto para permitir uma infraestrutura para a reutilização de dados acadêmicos. Contudo, a experiência de utilização das tecnologias da web vai além do mundo acadêmico e nos leva a entender que esse arcabouço pode ser adotado em outros campos, como na aviação civil, especialmente para os dados de interesse da segurança da aviação.

- Ao investigar os requisitos para tornar os dados FAIR, um dos pontos críticos é a disponibilidade de vocabulários que também atendam aos princípios FAIR. Ou seja, a disponibilidade de um conjunto de metadados que possa ser referenciado seguindo as boas práticas de publicação está na raiz da possibilidade de tornar dados interoperáveis e legíveis por máquinas.

- A área de _Recuperação da Informação_ (RI) na CI tem se voltado ao entendimento de como o fenômeno informacional ocorre e como ele pode ser trabalhado para possibilitar a correta comunicação diretamente entre homens e homens e entre homens e homens mediados por máquinas.

1.1 - Breve evolução da segurança na aviação

A evolução da segurança da aviação civil tem sido um trabalho contínuo que envolve a identificação e avaliação minuciosa dos riscos envolvidos no setor aéreo. Ao longo dos anos, a indústria da aviação tem se dedicado a aprimorar seus sistemas e processos para garantir um ambiente cada vez mais seguro. Isso inclui a análise de incidentes passados, a investigação de acidentes, a coleta de dados relevantes e a implementação de recomendações de segurança.

Além disso, os provedores de serviços e as autoridades da aviação civil devem colaborar para estabelecer padrões e procedimentos comuns, bem como para promover uma cultura de segurança abrangente.

Tanto os provedores de serviços quanto as autoridades da aviação civil têm a responsabilidade de gerenciar os riscos, embora os tipos e abrangência dos perigos possam variar. Por exemplo, enquanto um provedor de serviços pode identificar riscos específicos relacionados à sua organização individual, uma autoridade de aviação civil pode identificar tendências emergentes em todo o sistema de aviação, com base em dados agregados de vários provedores de serviços.

Para possibilitar que os gestores de todas as organizações tomem decisões baseadas em riscos, é fundamental que essas entidades possuam e analisem dados de segurança para identificar os perigos presentes em seus respectivos sistemas. Dessa forma, o uso de terminologia e definições comuns torna-se essencial para agregar e comparar dados de maneira eficiente.

Há um consenso entre as autoridades de aviação que o desenvolvimento de terminologias comuns pode facilitar a troca de informações para a gestão de riscos, sendo fundamental para identificar potenciais problemas e implementar medidas preventivas que salvaguardem a integridade de passageiros, tripulações e aeronaves, solidificando assim a segurança como um pilar da aviação civil moderna.

1.2 - A centralidade do problema de informação

Um dos problemas frequentes na gestão da segurança da aviação civil é o desafio de obter informações abrangentes e precisas sobre incidentes, riscos e tendências relacionados à segurança. 

Existem diversas razões para esse problema:

1) Subnotificação: nem todos os incidentes ou ocorrências de risco são devidamente relatados às autoridades responsáveis. Às vezes, indivíduos ou organizações podem hesitar em divulgar eventos adversos por medo de consequências legais ou impacto na reputação.

2) Cultura de sigilo: algumas companhias aéreas, provedores de serviços ou outros atores do setor podem ter uma cultura de sigilo em torno de questões de segurança. Isso pode dificultar a comunicação aberta e a troca de informações relevantes.

3) Falta de padrões e de sistemas integrados: a falta de padrões unificados e sistemas integrados de gerenciamento de segurança pode ocasionar a fragmentação dos dados. Isso dificulta a compilação e análise de informações em nível global e sistêmico.

4) Dificuldades na análise de dados: os sistemas de gestão da segurança da aviação civil podem não ter capacidade para acompanhar a quantidade crescente de dados disponíveis. A falta de recursos adequados ou tecnologias eficientes para analisar esses dados pode tornar difícil a identificação de padrões e tendências relevantes para mitigação de ocorrências.

5) Cooperação e compartilhamento limitados: algumas organizações podem hesitar em compartilhar informações de segurança com outras partes interessadas, como concorrentes ou reguladores, devido a segredos comerciais ou preocupações com a confidencialidade dos dados.

6) Dependência de trajetória tecnológica pelo meio de suporte da informação: a dependência de trajetória tecnológica baseada em sistemas criados para funcionar tendo o papel como meio de suporte e comunicação podem ser limitados em termos de eficiência, precisão e capacidade de coleta e análise de dados. Sistemas baseados em papel exigem processos manuais, o que pode ser lento e propenso a erros. Isso pode resultar em atrasos na comunicação de informações críticas. O armazenamento físico de dados em papel dificulta o compartilhamento rápido e abrangente de informações entre diferentes partes interessadas. Sistemas em papel tornam difícil lidar com grandes volumes de dados, dificultando a identificação de tendências e padrões.

Superar esses desafios requer esforços contínuos para promover uma cultura de segurança aberta e transparente, incentivar a comunicação e cooperação entre os atores do setor, estabelecer padrões e sistemas integrados de coleta e análise de dados e garantir a confidencialidade necessária para proteger as partes envolvidas.

1.3 - A Ciência da Informação e fenômeno informacional

O fenômeno informacional, que abrange a criação, disseminação e uso da informação, tem se tornado cada vez mais complexo à medida que a quantidade de dados disponíveis aumenta exponencialmente com o avanço da internet e do uso de computadores.

Considerando que a gestão eficaz da segurança da aviação civil depende do acesso e compartilhamento adequado de informações para identificar riscos e implementar medidas preventivas de forma proativa, como a CI pode contribuir para elucidar essas questões?

Autores pioneiros na CI como Paul Otlet (1934) e Vannevar Bush (1945) já haviam se debruçado sobre o fenômeno da explosão informacional com vistas a promover uma comunicação eficiente entre seres humanos e a necessidade crescente de interações mediadas por máquinas.

É interessante notar que o vínculo entre a CI e a aviação é antigo. As experiências em torno do projeto Cranfield I e II e no desenvolvimento do sistema SMART, nos quais são propostos os conceitos de taxa de revocação (_recall ratio_) e de taxa de precisão (_precision ratio_), elaborados por Aitchison [-@aitchison1963], Cleverdon [-@cleverdon1967] e Salton [-@salton1965], já visavam identificar melhores abordagens para o problema de recuperar conteúdos, tendo como objeto a área de aviação e engenharia.

1.4 A necessária interdisciplinaridade do problema de informação

Quanto à caracterização de um problema de informação, salientamos a visão de interdisciplinaridade apresentada por Tefko Saracevic [-@saracevic1995], ao indicar que não devemos estudar propriamente assuntos na Ciência da Informação, mas sim problemas.

A abordagem centrada em problemas atinge diferentes temas e disciplinas, não respeitando o estabelecimento de fronteiras rígidas. A área de RI, para o autor, é tomada como o espaço de consolidação maior dessa interdisciplinaridade.

Assim, compreender o problema de informação na gestão da segurança da aviação civil requer, à área de RI, o entendimento sobre os avanços tecnológicos na comunicação e no processamento da linguagem. Tomamos aqui as indagações de Tefko Saracevic (1995) e buscaremos aplicá-las à aviação civil: quais métodos e técnicas que possibilitem a recuperação precisa e relevante de informações? Como se deu a organização intelectual da informação, a sua recuperação, interação e quais sistemas e técnicas foram usadas nesse processo?

A evolução tecnológica tem transformado significativamente a maneira como as pessoas se comunicam e interagem com a linguagem, apresentando oportunidades e demandas para aprimorar as abordagens existentes e desenvolver soluções que atendam às necessidades da sociedade.

A gestão da segurança da aviação é uma área complexa, na qual é necessário considerar o fenômeno informacional de forma abrangente e interdisciplinar. A coleta e análise de informações são elementos essenciais para garantir a segurança das operações aéreas, e a interdisciplinaridade desempenha um papel fundamental nesse processo. 

Reunir conhecimentos e perspectivas de diversas áreas relacionadas à aviação, como engenharia aeronáutica, psicologia, ciência da informação, direito aeronáutico e outros, é uma ação importante para compreender as complexidades do sistema de aviação, identificar riscos potenciais e propor soluções.

O desenvolvimento contínuo das tecnologias da informação e comunicação trouxe consigo uma transformação na maneira como as pessoas se comunicam e interagem com a linguagem. Essa evolução tecnológica exige uma compreensão aprofundada dos avanços emergentes e das alternativas disponíveis para a recuperação de informações.

1.5 - A adoção dos princípios FAIR como resposta interdisciplinar ao problema informacional

Os princípios FAIR surgiram como uma resposta ao desafio da fragmentação e falta de interoperabilidade de dados em diversas áreas da ciência. "FAIR" é um acrônimo para "Findable" (Encontrável), "Accessible" (Acessível), "Interoperable" (Interoperável) e "Reusable" (Reutilizável). Esses princípios foram desenvolvidos em 2016 por um grupo de especialistas, de diferentes áreas, com o objetivo de estabelecer diretrizes para tornar os dados científicos mais acessíveis e utilizáveis em diferentes contextos.

Ente





O objetivo é tornar os dados mais acessíveis, compartilháveis e reutilizáveis. Esses princípios têm sido amplamente adotados e endossados em diversos domínios da pesquisa, promovendo maior transparência, colaboração e avanço do conhecimento científico.




1.6 - No princípio, os vocabulários






O aumento no volume de informações exige sistemas de busca mais sofisticados,

podem ser organizadas e acessadas, como os usuários interagem com os sistemas, como melhorar a experiência do usuário.



dependência de dispositivos tecnológicos e sistemas computacionais na vida cotidiana tem aumentado a necessidade de uma recuperação de informações

empenhada em entender o fenômeno informacional e desenvolver técnicas que possibilitem uma comunicação mais eficiente e direta entre seres humanos e máquinas.




1.7 - Conclusão

O desenvolvimento recente de novas formas sociotécnicas de relacionamento com a linguagem, recoloca o desafio de compreender os avanços tecnológicos e as alternativas possíveis, aos pesquisadores da ciência da informação, nos sistemas de processamento da linguagem e de recuperação de informações.

Entender esses novos arranjos sociotécnicos que envolvem a seleção e a geração de informações possibilita ao profissional de informação uma avaliação crítica das limitações e contribuições desses modelos, ampliando a capacidade de identificar áreas não exploradas, desafios sem soluções e suscitar perguntas que demandem investigações aprofundadas.











 



![Analisadores conceituais baseados em memória - [@riesbeck1986, p. 241]. (tradução automatizada com correções manuais)](https://github.com/gabrielmacedo/ci/assets/20596966/d8c1ec42-7a00-44f3-899d-52fe1a3601a8)

## Referências
