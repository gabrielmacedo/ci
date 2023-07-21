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
date: 17/07/2023
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

Este ensaio parte de algumas inquietações enfrentadas durante os quase 10 anos de trabalho desse autor na agência reguladora de aviação civil no Brasil. Há um problema de informação na gestão da segurança da aviação civil? Quais seriam esses problemas? Como a Ciência da Informação (CI), campo interdisciplinar dedicado a compreender o fenômeno informacional, pode contribuir para a compreensão dessas questões?

Tópicos:

- É comum a divulgação de documentos, padrões, orientações e dados técnicos relacionados à segurança da aviação em formatos não legíveis por máquinas, tornando a integração dessas informações ineficiente em contraste ao estado atual do desenvolvimento de tecnologias pensadas para a interoperabilidade.

- O estudo das fragilidades do sistema de segurança de aviação permite agir em relação a problemas sistêmicos e à gestão de riscos, promovendo recomendações práticas aos agentes do setor aéreo. É a ação sistemática de investigar e aplicar recomendações que assegura a aprendizagem e auxilia na prevenção de futuras ocorrências.

- Dentre as propostas de adoção e massificação do uso das tecnologias da web para o tratamento de dados, os princípios FAIR (acrônimo para _Findable, Accessible, Interoperable and Reusable_), conforme publicado por GO FAIR, reúnem boas práticas e recomendações para a localização, acessibilidade, interoperabilidade e reutilização de dados.

- O conjunto de princípios FAIR foi proposto para permitir uma infraestrutura para a reutilização de dados acadêmicos. Contudo, a experiência de utilização das tecnologias da web vai além do mundo acadêmico e nos leva a entender que esse arcabouço pode ser adotado em outros campos, como na aviação civil, especialmente para os dados de interesse da segurança da aviação.

- Ao investigar os requisitos para tornar os dados FAIR, um dos pontos críticos é a disponibilidade de vocabulários que também estejam disponibilizados como dados FAIR. A presença de um conjunto de metadados que possa ser referenciado seguindo as boas práticas de publicaçaõ está na raiz da possibilidade de tornar dados interoperáveis.

- A área de _Recuperação da Informação_ (RI) na CI tem se voltado ao entendimento de como o fenômeno informacional ocorre e como ele pode ser trabalhado para possibilitar a correta comunicação diretamente entre homens e homens e entre homens e homens mediados por máquinas.


1.1 Evolução da segurança na aviação

A evolução da segurança da aviação civil tem sido um trabalho contínuo que envolve a identificação e avaliação minuciosa dos riscos envolvidos no setor aéreo. Ao longo dos anos, a indústria da aviação tem se dedicado a aprimorar seus sistemas e processos para garantir um ambiente cada vez mais seguro. Isso inclui a análise de incidentes passados, a investigação de acidentes, a coleta de dados relevantes e a implementação de recomendações de segurança.

Além disso, os provedores de serviços e as autoridades da aviação civil devem colaboram para estabelecer padrões e procedimentos comuns, bem como para promover uma cultura de segurança abrangente.

Tanto os provedores de serviços quanto as autoridades da aviação civil têm a responsabilidade de gerenciar os riscos, embora os tipos e abrangência dos perigos possam variar. Por exemplo, enquanto um provedor de serviços pode identificar riscos específicos relacionados à sua organização individual, uma autoridade de aviação civil pode identificar tendências emergentes em todo o sistema de aviação, com base em dados agregados de vários provedores de serviços.

Para possibilitar que os gestores de todas as organizações tomem decisões baseadas em riscos, é fundamental que essas entidades possuam e analisem dados de segurança para identificar os perigos presentes em seus respectivos sistemas. Dessa forma, o uso de terminologia e definições comuns torna-se essencial para agregar e comparar dados de maneira eficiente.

A gestão de riscos é fundamental para identificar potenciais problemas e implementar medidas preventivas que salvaguardem a integridade de passageiros, tripulações e aeronaves, solidificando assim a segurança como um pilar da aviação civil moderna.

1.2 A centralidade do problema de informação

Um dos problemas frequentes na gestão da segurança da aviação civil é o desafio de obter informações abrangentes e precisas sobre incidentes, riscos e tendências relacionados à segurança. 

Existem diversas razões para esse problema:

1) Subnotificação: nem todos os incidentes ou ocorrências de risco são devidamente relatados às autoridades responsáveis. Às vezes, indivíduos ou organizações podem hesitar em divulgar eventos adversos por medo de consequências legais ou impacto na reputação.

2) Cultura de sigilo: algumas companhias aéreas, provedores de serviços ou outros atores do setor podem ter uma cultura de sigilo em torno de questões de segurança. Isso pode dificultar a comunicação aberta e a troca de informações relevantes.

3) Falta de padrões e de sistemas integrados: a falta de padrões unificados e sistemas integrados de gerenciamento de segurança pode ocasionar a fragmentação dos dados. Isso dificulta a compilação e análise de informações em nível global e sistêmico.

4) Dificuldades na análise de dados: os sistemas de gestão da segurança da aviação civil podem não ter capacidade para acompanhar a quantidade crescente de dados disponíveis. A falta de recursos adequados ou tecnologias eficientes para analisar esses dados pode tornar difícil a identificação de padrões e tendências relevantes para mitigação de ocorrências.

5) Cooperação e compartilhamento limitados: algumas organizações podem hesitar em compartilhar informações de segurança com outras partes interessadas, como concorrentes ou reguladores, devido a segredos comerciais ou ou preocupações com a confidencialidade dos dados.

6) Dependência de trajetória tecnológica pelo meio de suporte da informação: a dependência de trajetória tecnológica baseada em sistemas criados para funcionar tendo o papel como meio de suporte e comunicação podem ser limitados em termos de eficiência, precisão e capacidade de coleta e análise de dados. Sistemas baseados em papel exigem processos manuais, o que pode ser lento e propenso a erros. Isso pode resultar em atrasos na comunicação de informações críticas. O armazenamento físico de dados em papel dificulta o compartilhamento rápido e abrangente de informações entre diferentes partes interessadas. Sistemas em papel tornam difícil lidar com grandes volumes de dados, dificultando a identificação de tendências e padrões.

Superar esses desafios requer esforços contínuos para promover uma cultura de segurança aberta e transparente, incentivar a comunicação e cooperação entre os atores do setor, estabelecer padrões e sistemas integrados de coleta e análise de dados e garantir a confidencialidade necessária para proteger as partes envolvidas.

A gestão eficaz da segurança da aviação civil depende do acesso e compartilhamento adequado de informações para identificar riscos e implementar medidas preventivas de forma proativa.

Uma vez que os estudos sobre a interdisciplinaridade da Ciência da Informação lançam um olhar sobre as interseções de conteúdos de diferentes campos disciplinares na construção do conhecimento científico, este trabalho buscará, através de uma análise das tecnologias contemporâneas de Processamento de Linguagem Natural (PLN), identificar os marcos do seu desenvolvimento, a relação temporal que estabelecem e a presença desse variado esforço de diferentes ciências na compreensão dos problemas do seu objeto de estudo: a _informação_.

O desenvolvimento recente de novas formas sociotécnicas de relacionamento com a linguagem, por meio de modelos pré-treinados de recuperação da informação, recoloca o desafio de compreender os avanços tecnológicos e as alternativas possíveis, aos pesquisadores da ciência da informação, nos sistemas de processamento da linguagem e de recuperação de informações.

Até recentemente, o processo de recuperação da informação era predominantemente conduzido por meio de um método controlado de indexação e busca por termos, mesmo com o apoio de sistemas computacionais. Contudo, avanços recentes na área têm introduzido abordagens que utilizam Grandes Modelos de Linguagem (GML) ou _Large Language Models (LLM)_, em inglês. Esses modelos se destacam pela capacidade de gerar conteúdo informacional diversificado, abrangendo textos, imagens e áudios, com base em um modelo computacional estatístico manipulando uma imensa disponibilidade de informações e interagindo por meio de linguagem natural com agentes humanos. É essa característica distintiva que vem sendo aplicada na recuperação de informações em sistemas conversacionais de interação homem-máquina.

No caso mais destacado de sistema utilizando GML, como exemplo o ChatGPT em sua versão com o GPT-3.5, ocorreu uma integração de diversas tecnologias voltadas a melhorar os resultados das respostas. Ou seja, foi buscada a qualificação da recuperação de informações combinando tecnologias de aprendizado profundo (_deep learning_), aprendizado não supervisionado (_unsupervised learning_), ajuste fino de instrução (_instruction fine-tuning_), aprendizado multitarefa (_multi-task learning_), aprendizado em contexto (_in-context learning_) e aprendizado por reforço com feedback humano (_Reinforcement learning from Human Feedback - RLHF_) [@chatgpt2022; @wu2023].

Entender esses novos arranjos sociotécnicos que envolvem a seleção e a geração de informações possibilita ao profissional de informação uma avaliação crítica das limitações e contribuições desses modelos, ampliando a capacidade de identificar áreas não exploradas, desafios sem soluções e suscitar perguntas que demandem investigações aprofundadas.

Quais critérios seriam necessários para avaliar a capacidade de recuperação de informações e de geração de linguagem natural presentes em novas tecnologias? Como estabelecer métricas para comparar diferentes modelos e selecionar, a cada caso de uso, a melhor tecnologia disponível?

Oferecer resposta à essas perguntas não é uma tarefa trivial. No entanto, em que pese a atualidade e o desenvolvimento recente dessas novas abordagens de processamento da linguagem natural, não seriam essas perguntas similares - enquanto aos objetivos pretendidos - às já realizadas nas experiências pioneiras do projeto Cranfield I e II e no desenvolvimento do SMART, quando propõem os conceitos de taxa de revocação (_recall ratio_) e de taxa de precisão (_precision ratio_), como elaborados por Aitchison [-@aitchison1963], Cleverdon [-@cleverdon1967] e Salton [-@salton1965], visando identificar melhores abordagens para o problema de recuperar conteúdos de um determinado acervo? 

Quanto à caracterização de um problema de informação, salientamos ainda a visão de interdisciplinaridade apresentada por Tefko Saracevic [-@saracevic1995], ao indicar que não devemos estudar propriamente assuntos na Ciência da Informação, mas sim problemas. A abordagem centrada em problemas atinge diferentes temas e disciplinas, não respeitando o estabelecimento de fronteiras rígidas. A área da recuperação da informação, para o autor, é tomada como o espaço de consolidação maior dessa interdisciplinaridade. Afinal, várias disciplinas são mobilizadas para responder às questões sobre como ofertar informações úteis e como promover interações efetivas para os usuários frente à explosão informacional ocorrida.

Assim, quanto aos desenvolvimentos dos modelos posteriores às formas de recuperação da informação já vistas, quais novas perguntas se colocaram e como elas foram respondidas? Ou, como apontou Tefko Saracevic [-@saracevic1995], como se deu a organização intelectual da informação, a sua recuperação, interação e quais sistemas e técnicas foram usadas nesse processo?

Sobre essas últimas questões é que nos debruçaremos neste resumo. Faremos um recorte temporal a partir dos anos 1970 até o final dos anos 1980. Ou seja, iniciaremos após a divulgação da tese _Procedures as a Representation for Data in a Computer Program for Understanding Natural Language_ sobre o desenvolvimento do sistema _SHRDLU_, um modelo de mundo de blocos que experimentava a interação entre homem e máquina por meio de textos em linguagem natural, com um vocabulário limitado, como visto no resumo anterior [@winograd1971]. Serão destacados os autores, as obras de referência e os conceitos centrais em suas abordagens. Adicionalmente serão acrescentados comentários destinados a oferecer um contexto narrativo aos textos.

O desenvolvimento subsequente ao _SHRDLU_, após 1970, se dá pela construção de modelos de mundo na área de computação para análises conceituais. Tal esforço visava estruturar conceitos do mundo material em informações e dados que fossem corretamente classificados ou inferidos por um computador, superando as limitações de vocabulário que restringiam as aplicações desenvolvidas até então, muito centradas na sintaxe, para aplicações que pudessem capturar as relações semânticas da linguagem. Ou seja, deveria haver algum tipo de representação conceitual subjacente no qual os modelos computacionais pudessem usar de referência para a análise da linguagem.

Os primeiros analisadores conceituais foram Spinoza e Spinoza II (SCHANK, _et al._, 1970 _apud_ FITZGERALD, 1996). Dentre as diversas propostas, se destacou em 1975 o sistema MARGIE, um programa que fazia inferências em linguagem natural e que era inspirado na Teoria da Dependência Conceitual [@fitz1996]. Desenvolvido incialmente por Roger Schank como um esforço teórico no programa de pós-graduação em linguística na Universidade do Texas, a programação do sistema será iniciada, posteriormente, com um analisador conceitual (_conceptual parser_) elaborado no Projeto de Inteligência Artificial da Universidade de Standford, em parceria com Larry Tesler e Sylvia Weber [@schank1975]. 

Para os propositores do sistema, o problema do processamento de linguagem natural foi dividido em três partes distintas, porém interdependentes: "(1) mapear sentenças em uma representação de seu significado; (2) armazenar e fazer inferências sobre um significado que é recebido por uma memória; e (3) a tradução de uma representação de significado de volta para uma linguagem natural" [@schank1975, p. 1] (tradução automatizada com correções manuais). O MERGIE se baseava num conjunto de regras "se-então", nomeadas de _requests_, tendo por objetivo principal produzir programas de computador que pudessem entender e gerar sentenças de forma geral, para problemas de linguística computacional, sem as limitações de escopo dos projetos de micro mundos.

Quanto às formas de funcionamento, explica o autor: 

> "o programa MARGIE tem dois modos: _PARAPHRASE_ e _INFERENCE_. No modo _PARAPHRASE_, as paráfrases semânticas podem ser geradas a partir de uma frase de entrada lendo a representação conceitual subjacente a essa frase usando diferentes palavras e combinações de conceitos. No modo INFERENCE, muitas das possíveis inferências que podem ser feitas a partir de uma sentença de entrada são produzidas e, em seguida, geradas como saída" [@schank1975, p. 2] (tradução automatizada com correções manuais).

Destacamos aqui uma ideia apresentada por Roger Schank e Robert Abelson, na Conferência Conjunta Internacional sobre Inteligência Artificial, realizada em setembro de 1975, que ilustra a necessidade de um modelo destinado não mais a recuperar documentos ou traduzir referências, mas em construir uma cadeia de significados que são inicialmente abstraídas de textos em linguagem natural, têm seus elementos principais armazenados e, posteriormente, recriar o texto a partir de ligações feitas entre esses elementos. Cabendo ao modelo selecionar o que é realmente relevante e o que precisa ser armazenado para a reconstrução da mensagem [@schank1975a].

Os autores indicam que uma teoria da compreensão da linguagem deveria levar em consideração que: "quando as pessoas têm uma pista do que esquecer, elas se saem melhor em lembrar. Em outras palavras, o bom esquecimento é a chave para a lembrança" [@schank1975a, p. 155] (tradução automatizada com correções manuais). Portanto, a primeira tarefa seria encontrar os itens mais significativos em um texto e, em seguida, construir uma heurística para extrair e recordar exatamente esses itens.

É interessante notar que, apesar dos sistemas atuais terem uma implementação mais complexa, a ideia de aprendizado de máquina (_machine learning_) sob um dado significado textual compartilha do mesmo tipo de objetivo, qual seja, construir um modelo para responder à novos dados de entrada com base também em heurísticas depreendidas dos dados de treinamento. 

Além do desenvolvimento do MARGIE, outros analisadores posteriores foram construídos na mesma tradição, produzindo alguns avanços incrementais, incluindo melhorias nas estruturas de controle e nos formatos padronizados para requisições (_requests_), como: ELI (RIESBECK; SCHANK, 1976 _apud_ RIESBECK, 1986), ELI-2 (GERSHMAN, 1979 _apud_ RIESBECK, 1986), SAM (SCHANK; ABELSON, 1977 _apud_ RIESBECK, 1986), PAM (WILENSKY, 1978 _apud_ RIESBECK, 1986), FRUMP (DEJONG, 1979 _apud_ FITZGERALD, 1996) e CA (BIRNBAUM; SELFRIDGE, 1981 _apud_ RIESBECK, 1986) [@fitz1996; @riesbeck1986]. 

A imagem a seguir apresenta um diagrama de blocos indicando o modelo subjacente aos primeiros analisadores conceituais: 

![Primeiros analisadores conceituais, [@riesbeck1986, p. 239]. (tradução automatizada com correções manuais)](https://github.com/gabrielmacedo/ci/assets/20596966/45b789e9-f181-4979-ab64-7670aad19b4a)

Enquanto categorização, podemos agrupar os modelos desenvolvidos na década de 1970 em função do analisador conceitual (_parser_) está vinculado a uma **tarefa semântica**, uma vez que o objetivo do analisar era extrair o sentido do texto, das setenças analisadas palavra a palavra da esquerda para a direita, por meio de um processo de inferência sobre o significado das palavras [@fitz1996; @riesbeck1986].

Já na década de 1980, o analisador passa a estar vinculado a uma **tarefa de memória**, crescendo o foco colocado sobre a modelagem de memória e a realização de inferências. Will Fitzgerald [-@fitz1996] destacará os modelos de Memória Dinâmica de Schank (SCHANK, 1982) relacionados ao IPP (LEBOWITZ, 1980), BORIS (DYER, 1983) e o MOPTRANS (LYTINEN, 1984). 

As representações conceituais são então descritas como Pacotes de Organização da Memória (POM) (_Memory Organization Packages_ - MOP). Os POM representaram um avanço em relação aos modelos conceituais anteriores devido à sua capacidade de adaptação dinâmica. Isso significava que o estado da memória computacional poderia se adaptar com base em novas entradas, como a de novo texto. Além disso, enfatizavam o empacotamento das representações conceituais, permitindo que essas representações fossem aprendidas e generalizadas por meio de experimentações. Isso resultava em uma melhor organização e armazenamento das informações na memória, contribuindo para uma maior fluidez no processamento e na decisão sobre novos conteúdos [@fitz1996]. 

Riesbeck [-@riesbeck1986] descreve esses analisadores conceituais como sistemas de construção e armazenamento, nos quais o analisador sintático constrói uma representação conceitual durante a análise, que é posteriormente armazenada na memória. Um exemplo desse tipo de modelo é o DMAP (_Direct Memory Access Parsing_; Martin 1989, 1990), que busca modelar a análise como um processo integrado à memória. O DMAP é um analisador de reconhecimento, o que significa que ele se baseia em uma representação elaborada da memória conceitual para reconhecer referências a partes dessa memória [@fitz1996]. 

O diagrama de blocos a seguir ilustra o modelo de analisador conceitual baseado em memória: 

![Analisadores conceituais baseados em memória - [@riesbeck1986, p. 241]. (tradução automatizada com correções manuais)](https://github.com/gabrielmacedo/ci/assets/20596966/d8c1ec42-7a00-44f3-899d-52fe1a3601a8)

Os analisadores baseados em semântica e em memória serão vinculados à ideia de **modelos cognitivos** para o processamento de linguagem natural, ou seja, uma tentativa de aproximar a tarefa da computação da maneira como as pessoas processam e compreendem textos. Os modelos cognitivos serão preponderantes até o início dos anos 1990. Após esse período, serão iniciadas as aplicações de sistemas baseados em redes neurais para a relização de tarefas de linguística computacional.

Este resumo procurou compreender os desafios e as soluções encontradas no processamento de linguagem natural, em diálogo com as teorias e respostas que emergiram no campo da computação entre os anos 1970 e 1990. Entende-se que esse esforço auxilia na compreensão das visões sobre essa trajetória, sobre a recuperação e o uso eficiente de um conjunto informacional cada vez maior e mais disponível.

Revisitar os modelos do passado pode evitar a repetição de trajetórias equivocadas ou mesmo a identificação de necessidades persistentes. Por exemplo, a capacidade de comparar soluções com base em dados empíricos e a necessidade de criar métricas de avaliação quanto à precisão da recuperação informacional, seja de um documento completo ou de fragmentos recortados por mapeamentos semânticos, inferidos por sistemas baseados em regras. Como sugeriu Tefko Saracevic [-@saracevic1995], apreender o fenômeno informacional por meio do enfrentamento de problemas pode contribuir para distinguir as novas tecnologias e perceber que caminhos parecem mais promissores. E é nesse sentido que observar as origens das tecnologias de interação atuais, considerando os marcos do desenvolvimento da linguística computacional e sob o aspecto interdisciplinar na Ciência da Informação, que novas e velhas questões pertinentes podem ser exploradas.


## Referências