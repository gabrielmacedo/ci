---
title: Módulo 3 - Epistemologia da Ciência da Informação
# subtitle: 
tags:
  - science information
  - chronography
  - information retrieval
author: >-
    Gabriel Santiago Macedo^[Universidade Federal do Rio de
    Janeiro (UFRJ), Instituto Brasileiro de Informação em Ciência e
    Tecnologia (IBICT), Programa de Pós-Gradução em Ciência da 
    Informação (PPGCI), gabrielmacedo@discente.ibict.br, 
    [orcid:0000-0001-8845-7985](https://orcid.org/0000-0001-8845-7985);
    Disciplina - Cronografia da Ciência da Informação, Docente - 
    Lillian Maria Araujo de Rezende Alvares.]
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
date: 02/07/2023
abstract: >-
    Resumo do Módulo 3 da disciplina "Cronografia da Ciência da 
    Informação",  "Epistemologia da Ciência da Informação", 
    Docente - Lillian Maria Araujo de Rezende Alvares.
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

# Módulo 3: Epistemologia da Ciência da Informação

Este resumo apresenta um recorte sobre o percurso histórico da epistemologia da Ciência da Informação (CI). A natureza cronográfica a ser empregada neste texto tem por objetivo identificar os eventos relacionados ao estudo da informação em face das novas tecnologias, especialmente quanto ao campo da _Recuperação da Informação_ (RI).

Considerando que a epistemologia busca compreender a natureza do conhecimento científico, suas bases, limitações e métodos, uma análise das tecnologias contemporâneas de Processamento de Linguagem Natural (PLN), em inglês _Natural Language Processing_ (NLP), para a recuperação de informações requer, inicialmente, a identificação dos marcos do seu desenvolvimento e a compreensão da relação temporal estabelecida entre estes.

Atualmente, com a ampla adoção de sistemas de PLN, como o ChatGPT (_Generative Pre-trained Transformer_), a análise da evolução desses modelos torna-se ainda mais relevante para os pesquisadores da ciência da informação que estão interessados em aprofundar o entendimento das interrelações entre informação e tecnologia. 

Ao abordar as formas de recuperação da informação produzidas por esses sistemas, os pesquisadores podem realizar uma avaliação crítica das limitações e contribuições apresentadas, além de expandir a capacidade de identificar áreas não exploradas, desafios em aberto ou questões não resolvidas que demandam atenção e investigação adicional.

Podemos nos perguntar se, seriam os atuais modelos de interação homem-máquina como o ChatGPT, ou seja, interfaces com sistemas pré-treinados para realizar conversas em linguagem natural uma resposta consistente aos problemas de _complexidade e difusão de conhecimento_ ou mesmo de _explosão informacional_, sob os quais se debruçaram respectivamente Paul Otlet e Vannevar Bush?

A relação entre a tecnologia e a informação foi abordada por esses e outros autores ao longo do tempo, sendo uma questão central à ciência da informação desde a sua proposição enquanto ciência, no início dos anos 1960. A recuperação da informação, em específico, foi até considerada como "o  _núcleo_  da  área  por diferentes autores, entre os quais Saracevic, em seu livro _Introduction to Information Science de 1970_" [@araujo2014].

Visando dar continuidade ao trabalho empenhado no resumo anterior, do módulo 02, adotaremos aqui o recorte temporal entre o final dos anos 1950 e o início dos anos 1970. Serão destacados os autores, as obras de referência e os conceitos centrais em suas abordagens. Adicionalmente serão acrescentados comentários destinados a oferecer um contexto narrativo aos textos.

Os problemas de recuperação da informação que motivaram Cyril Cleverdon, um ex-bibliotecário da _Engine Division of the Bristol Aeroplane Co. Ltd._, a implementar o _The ASLIB Cranfield Research Project_, no _College of Aeronautics at Cranfield_, e os testes que o sucederam, entre 1958 e 1963 que foram realizados também em outros centros de estudos são exemplos seminais abordados por autores da ciência da informação [@araujo2014].

Os projetos consistiram numa pesquisa, inicialmente sem a utilização de computadores, com o objetivo de melhorar a eficiência dos sistemas de recuperação de informação, avaliando melhores linguagens e métodos de indexação [@cleverdon1960; @cleverdon1967].

O primeiro projeto, iniciado em abril de 1958, foi caracterizado pela comparação de 4 modelos de indexação sob uma coleção de documentos de aviação: Classificação Decimal Universal (CDU), catálogo de assuntos em ordem alfabética, esquema de classificação facetada, sistema de termo único. Os testes envolveram a comparação da eficiência relativa de cada um dos quatro índices em comparação a um conjunto de questões. As questões usadas foram produzidas por representantes de cerca de cinquenta organizações no Reino Unido, Estados Unidos, Canadá e Holanda [@cleverdon1960]. 

Ao tratar detalhadamente das razões de fracasso ou de sucesso na busca de informação relevante, o projeto objetivou levantar os requisitos que um sistema de recuperação de informação deveria atender. Cleverdon [-@cleverdon1960, p.9] indica que a ausência de experimentos práticos atrelados às teorias de indexação a superestimavam, "todos aqueles que tentam resolver os problemas de recuperação de informações estão trabalhando muito no escuro, incertos quanto aos problemas reais e totalmente incapazes de aplicar quaisquer medições às soluções propostas". 

Assim, conclui que o requisito principal para avaliar a recuperação da informação é um padrão de medição reconhecido e um método de medição satisfatório. E, com o projeto, esperavam ter dados suficientes para formar um padrão de medição para sistemas de recuperação [@cleverdon1960]. Em termos de desempenho, foi constatado que todos os sistemas operavam em níveis próximos de eficiência [@cleverdon1967].

Em 1963, cinco anos após o início dos experimentos, os testes realizados com a documentação de metalurgia da _Western Reserve University_, seviram para estabelecer duas medidas utilizadas para avaliar os sistemas, a taxa de recuperação ou revocação (_recall ratio_) e a taxa de precisão (_precision ratio_) [aitchison1963; @cleverdon1967]. 

![Figura 1 - Recuperação/Precisão, @cleverdon1967](https://github.com/gabrielmacedo/ci/assets/20596966/7afc38a1-ca30-4a0b-88ff-be5259f718da)

Os resultados dos testes indicaram a relação inversa entre recuperação e precisão. Considerando que a taxa de recuperação máxima possível de 100 por cento pode ser obtida ao recuperar todos os documentos disponíveis, a melhoria na taxa de precisão implicaria, portanto, numa queda na taxa de recuperação. De forma inversa, para aumentar a taxa de recuperação um maior número de documentos não relevantes também seria recuperado. "Este é sempre o caso ao operar dentro de um determinado sistema" [@cleverdon1967, p. 179].

Outra abordagem de indexação foi proposta por Salton com o sistema SMART (_System for the Mechanical Analysis and Retrieval of Text_), desenvolvido entre os anos 1960 e 1970. Embora tratasse de problemas semalhantes aos que estavam sendo trabalhados em Cranfield, ao comparar os efeitos de diferentes formas de indexação de textos, havia diferenças expressivas entre as duas abordagens. A mais significativa delas consistia na utilizava de computadores por Salton, permitindo processamento avançado de dados e algoritmos complexos, enquanto os experimentos de Cranfield dependiam de técnicas manuais e estatísticas [@cleverdon1967]. Essa distinção no uso da tecnologia permitiu que Salton explorasse análises mais sofisticadas.

Uma das principais contribuições do sistema SMART foi o desenvolvimento do modelo de espaço vetorial (_vector space model_) para recuperação de informações. Esse modelo utilizava representações matemáticas dos documentos e das consultas para calcular a similaridade entre eles. Em vez de se basear apenas na presença ou ausência de palavras-chave, o modelo vetorial considerava a relevância e importância relativa dos termos, permitindo uma recuperação mais precisa. Além disso o SMART implementou a indexação automática de documentos, utilizando técnicas como a extração de palavras-chave e a atribuição de pesos aos termos com base em sua frequência nos documentos. O SMART também introduziu a ideia de consultas interativas, permitindo aos usuários refinar suas consultas com base nos resultados apresentados. Isso possibilitava uma interação mais dinâmica entre o usuário e o sistema de recuperação de informações [@salton1965].

> "O sistema pode ser controlado pelo usuário de modo que uma solicitação de pesquisa possa ser processada primeiro em um modo padrão; o usuário fica então livre para analisar a saída obtida e, dependendo de seus requisitos adicionais, uma reavaliação da solicitação pode ser solicitada sob novas condições. A nova saída pode ser novamente examinada e o processo iterado até o momento em que o tipo e a quantidade correta de informações sejam recuperados" [@salton1965]. (tradução automatizada com correções manuais)

Apesar das metodologias divergentes, tanto o desenvolvimento do SMART quanto dos projetos de Cranfield fizeram contribuições significativas para o campo da recuperação de informações. No entanto, enquanto o PNL avançava nos modelos de indexação, as tarefas de tradução automatizada (_machine translation_) passaram a ser questionadas.

Após a não concretização das altas expectativas geradas com o experimento de tradução automatizada do russo para o inglês, iniciado no experimento da Georgetown-IBM de 1954, o governo dos Estados Unidos cria 10 anos depois, em 1964, o ALPAC (_Automatic Language Processing Advisory Committee_). O ALPAC foi um comitê composto por sete cientistas, liderado por John R. Pierce, com o objetivo de avaliar o progresso da linguística computacional e da tradução automatizada. 

O relatório intitulado _Language and Machines_, publicado 02 anos depois pelo ALPAC, em 1966, é cético sobre o custo e a eficácia da tradução automatizada, indicando que para o estado atual da tecnologia não houve a tradução de texto científico geral e que a utilidade das traduções dependeria de pós-edição humana. O documento ainda enfatiza que seria necessário ampliar a pesquisa básica em lingüística computacional e na construção de auxílios de máquina para tradutores humanos [@alpac1966]. 

Em suma, o comitê avaliador considerou que a tradução mecanizada era mais cara, mais lenta e menos precisa do que um tradutor humano [@alpac1966; @josselson1971]. Como consequência, o relatório acabou fazendo com que o governo dos Estados Unidos reduzisse o financiamento do tema.

Josselson [-@josselson1971] ao abordar a reação soviética ao relatório, com base no documento _Nauchno-Tekhnicheskaja Informatsija_ (Informação Técnico-Científica) publicado em 1968, destaca que a avaliação do comitê foi encarada como muito estreita e pragmática, pois não refletia as potencialidades da tradução automatizada. Para os soviéticos, esta tecnologia carregava ideias para resolver "um dos problemas mais importantes do século XX, os problemas envolvendo a simbiose entre homens e máquinas" [Nauchno-Tekhnicheskaja _apud_ @josselson1971, p. 47].

A relação de comunicação entre homens e máquinas continuou sendo explorada também em outros campos, como na inteligência artificial simbólica. Um recurso interessante utilizado nesse campo é a construção de problemas de brinquedo (_toy problems_), úteis para testar e demonstrar metodologias, apesar de não terem uma aplicação imediata. Nesse sentido, um esforço de pesquisa importante foi realizado sobre os chamados micromundos, sendo o mais conhecido deles o mundo de blocos (_blocks world_) [@norvig2013].

Atuando sobre o problema do mundo de blocos, entre 1968 e 1970, Terry Winograd desenvolveu o SHRDLU, um programa de demonstração voltado à compreensão de linguagem natural em inglês, usando as linguagens LISP e Planner. Em sua tese no Massachusetts Institute of Technology (MIT), publicada em 1971, sob o título _PROCEDURES AS A REPRESENTATION FOR DATA IN A COMPUTER PROGRAM FOR UNDERSTANDING NATURAL LANGUAGE_ o autor descreve o sistema como um modelo capaz de receber comandos e de interagir por textos em linguagem natural, respondendo a frases e realizando ações com as figuras presentes no micromundo, além de pedir esclarecimentos quando não consegue deduzir, ou seja, fazer inferência sobre o sentido de uma interação com base no contexto disponível.

![Figura 2 - Diálogo no SHRDLU demonstrando a interação para a máquina pega o bloco vermelho - @winograd1971, p. 38](https://github.com/gabrielmacedo/ci/assets/20596966/414a890f-b488-4cfe-a925-70401ebf4108)

Seu objetivo era superar os problemas de manipulação apenas sintática e gramatical presentes nos primeiros sistemas de tradução automatizada, como os aplicados na tradução entre inglês e russo. O autor reconhecia a necessidade de lidar com os aspectos semânticos e de conferir aos computadores a capacidade de usar um conhecimento prévio sobre os assuntos para os quais deveria oferecer resposta. O entendimento da linguagem por máquinas deveria combinar "gramática, semântica e racioncínio de uma maneira muito íntima, chamando cada parte para ajudar as outras" [@winograd1971, p. 12].

Em síntese, os eventos destacados ao longo dessas duas décadas possibilitam refletir acerca dos desafios no processamento da linguagem. Os trabalhos apresentados reforçam a centralidade dos problemas de linguística para que as máquinas interpretem a linguagem humana. Isso requer uma compreensão profunda da estrutura, significado e nuances que utilizamos aos nos comunicar. Os problemas envolvendo questões de semântica, sintaxe, análise do contexto e de interpretação das intenções do usuário demandaram posteriormente o desenvolvimento de técnicas, algoritmos e modelos para permitir o processamento eficiente da linguagem natural.

Rever o histórico apresentado neste resumo permite observar as origens das tecnologias de interação atuais. Essas tecnologias se concentram na capacidade das máquinas de entender e responder à linguagem natural. Os avanços recentes no processamento de linguagem natural, tais como os realizados pelo ChatGPT, destacam a importância de uma melhor compreensão das formas de recuperação de informações no campo da Ciência da Informação. A revisão cronográfica apresentada neste trabalho explora alguns marcos do desenvolvimento de sistemas de indexação e linguística computacional, contribuindo para esse objetivo. 

Olhar para as tecnologias por meio da Ciência da Informação é fundamental para as discussões no âmbito desta disciplina, trazendo novas perspectivas para os profissionais envolvidos. Compreender a gênese desses  proporciona uma base sólida para entender as interações entre humanos e máquinas de hoje.

## Referências
