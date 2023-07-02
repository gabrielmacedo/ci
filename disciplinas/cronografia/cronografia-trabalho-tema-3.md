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

Visando dar continuidade ao trabalho empenhado no resumo anterior, do módulo 02, adotaremos aqui o recorte temporal entre o final dos anos 1950 até os anos 1970.

Os problemas de recuperação da informação que motivaram Cyril Cleverdon, um ex-bibliotecário da _Engine Division of the Bristol Aeroplane Co. Ltd._, a implementar o _The ASLIB Cranfield Research Project_, no _College of Aeronautics at Cranfield_, e os testes que o sucederam, entre 1958 e 1963 que foram realizados também em outros centros de estudos são exemplos seminais abordados por autores da ciência da informação [@araujo2014].

Os projetos consistiram numa pesquisa, inicialmente sem a utiliação de computadores, com o objetivo de melhorar a eficiência dos sistemas de recuperação de informação, avaliando melhores linguagens e métodos de indexação [@cleverdon1960; @cleverdon1967].

O primeiro projeto, iniciado em abril de 1958, foi caracterizado pela comparação de 4 modelos de indexação sob uma coleção de documentos de aviaçao: Classificação Decimal Universal (CDU), catálogo de assuntos em ordem alfabéfica, esquema de classificação facetada, sistema de termo único. Os testes envolveram a comparação da eficiência relativa de cada um dos quatro índices em comparação a um conjunto de questões. As questões usadas foram produzidas por representantes de cerca de cinquenta organizações no Reino Unido, Estados Unidos, Canadá e Holanda [@cleverdon1960]. 

Ao tratar detalhadamente das razões de fracasso ou de sucesso na busca de informação relevante, o projeto objetivou levantar os requisitos que um sistema de recuperação de informação deveria atender. Cleverdon [-@cleverdon1960, p.9] indica que a ausência de experimentos práticos atrelados às teorias de indexação a superestimavam, "todos aqueles que tentam resolver os problemas de recuperação de informações estão trabalhando muito no escuro, incertos quanto aos problemas reais e totalmente incapazes de aplicar quaisquer medições às soluções propostas". 

Assim, conclui que o requisito principal para avaliar a recuperação da informação é um padrão de medição reconhecido e um método de medição satisfatório. E, com o projeto, esperavam ter dados suficientes para formar um padrão de medição para sistemas de recuperação [@cleverdon1960]. Em termos de desempenho, foi constatado que todos os sistemas operavam em níveis próximos de eficiência [@cleverdon1967].

Em 1963, cinco anos após o início dos experimentos, os testes realizados com a documentação de metalurgia da _Western Reserve University_, seviram para estabelecer duas medidas utilizadas para avaliar os sistemas, a taxa de recuperação ou revocação (_recall ratio_) e a taxa de precisão (_precision ratio_) [aitchison1963; @cleverdon1967]. 

![Figura 1: Recuperação/Precisão, @cleverdon1967](https://github.com/gabrielmacedo/ci/assets/20596966/7afc38a1-ca30-4a0b-88ff-be5259f718da)

Os resultados dos testes indicaram a relação inversa entre recuperação e precisão. Considerando que a taxa de recuperação máxima possível de 100 por cento pode ser obtida ao recuperar todos os documentos disponíveis, a melhoria na taxa de precisão implicaria portanto numa queda na taxa de recuperação. De forma inversa, para aumentar a taxa de recuperação, um maior número de documentos não relevantes também seriam recuperados. "Este é sempre o caso ao operar dentro de um determinado sistema" [@cleverdon1967, p. ?].

É interessante observar que até esse momento o PNL contrapunha tanto os métodos manuais, sem auxílio mecanizado, quanto a introdução de computadores. As investigações realizadas por Salton com o sistema SMART (_System for the Mechanical Analysis and Retrieval of Text_), publicadas em 1965, eram semelhantes às que estavam sendo feitas em Cranfield. O sistema SMART focava em comparar os efeitos de diferentes dispositivos ou opções. No entanto, havia diferenças significativas entre as duas abordagens. Salton utilizava um computador grande, permitindo processamento avançado de dados e algoritmos complexos, enquanto Cranfield dependia de técnicas manuais e estatísticas.



Após a não concretização das altas expectativas geradas com o experimento de tradução automatizada do russo para o inglês, iniciado no experimento da Georgetown-IBM de 1954, o governo dos Estados Unidos cria 10 anos depois, em 1964, o ALPAC (_Automatic Language Processing Advisory Committee_). O ALPAC foi um comitê composto por sete cientistas, liderado por John R. Pierce, com o objetivo de avaliar o progresso da linguística computacional e da tradução automatizada. 

O relatório intitulado _Language and Machines_, publicado 02 anos depois pelo ALPAC, em 1966, é cético sobre o custo e a eficácia da tradução automatizada, indicando que para o estado atual da tecnologia não houve a tradução de texto científico geral e que a utilidade das traduções dependeria de pós-edição humana. O documento ainda enfatiza que seria necessário ampliar a pesquisa básica em lingüística computacional e na construção de auxílios de máquina para tradutores humanos [@alpac1966]. 

Em suma, o comitê avaliador considerou que a tradução mecanizada era mais cara, mais lenta e menos precisa do que um tradutor humano [@alpac1966; @josselson1971]. Como consequência, o relatório acabou fazendo com que o governo dos Estados Unidos reduzisse o financiamento do tema.

Josselson [-@josselson1971] ao abordar a reação soviética ao relatório, com base no documento _Nauchno-Tekhnicheskaja Informatsija_ (Informação Técnico-Científica) publicado em 1968, destaca que a avaliação do comitê foi encarada como muito estreita e pragmática, pois não refletia as potencialidades da tradução automatizada. Para os soviéticos, esta tecnologia carregava ideias para resolver "um dos problemas mais importantes do século XX, os problemas envolvendo a simbiose entre homens e máquinas" [Nauchno-Tekhnicheskaja _apud_ @josselson1971, p. 47].




Entre 1968 e 1970, Terry Winograd desenvolveu o SHRDLU, um programa de demonstração voltado à compreensão de linguagem natural em inglês, usando as linguagens LISP e Planner. Em sua tese no Massachusetts Institute of Technology (MIT), publicada em 1971, sob o título _PROCEDURES AS A REPRESENTATION FOR DATA IN A COMPUTER PROGRAM FOR UNDERSTANDING NATURAL LANGUAGE_ o autor descreve o sistema como um modelo capaz de receber comandos e de interagir em linguagem natural, respondendo a frases e realizando ações, além de pedir esclarecimentos quando não consegue deduzir, ou seja, fazer inferência sobre o sentido de uma interação com base no contexto disponível. 

Seu objetivo era superar os problemas de manipulação apenas sintática e gramatical presentes nos primeiros sistemas de tradução automatizada, como os aplicados na tradução entre inglês e russo. O autor reconhecia a necessidade de lidar com os aspectos semânticos e de conferir aos computadores a capacidade de usar um conhecimento prévio sobre os assuntos para os quais deveria oferecer resposta. O entendimento da linguagem por máquinas deveria combinar "gramática, semântica e racioncínio de uma maneira muito íntima, chamando cada parte para ajudar as outras" [@winograd1971, p. 12].

![- Grafo indicando o funcionamento do programa SHRDLU. As setas indicam qual parte do programa aciona a outra - @winograd1971] (https://github.com/gabrielmacedo/ci/assets/20596966/1c8d43f6-6644-432d-b9cb-b7e6b67d199a)



Os primeiros sistemas de recuperação da informação 


...
em razão de terem sido referenciadas por @gao2023 para a compreensão dos modelos de Recuperação de Informações Conversacionais (RIC), em inglês _Conversational Information Retrieval_ (CIR), dos quais fazem parte ferramentas como o ChatGPT.
...






LANCASTER, 1968


com base principalmente na sistematização apresentada por @ingwersen2005




Os estudos de Cranfield lançaram conceitos sobre a ciência da computação e a consulta de informações, como _revocação_ e _precisão_, que foram relevantes para o desenvolvimento de sistemas de busca.






Recuperação de Informações Conversacionais (RIC), em inglês Conversational Information Retrieval (CIR), com foco nas abordagens neurais que foram desenvolvidas nos últimos anos. O progresso no aprendizado profundo trouxe grandes melhorias no processamento de linguagem natural (NLP) e na IA de conversação, levando a uma infinidade de serviços de conversação comercial que permitem interação naturalmente falada e digitada, aumentando a necessidade de mais interações centradas no ser humano (no usuário) na recuperação de informações [@gao2023].


Fuzzy para recuperação de informação



por @pinheiro1995, o avanço da computação e da inteligência artificial promovem mudanças significativas na compreensão dos fenômenos informacionais. 


Para Robinson e  [-@robinson2010], ao tratar dos modelos quantitativos de informação,


Mudar o canal na teoria da situação equivale a mudar os tipos de inferências feitas sobre entidades ou objetos. O canal, portanto, determina o que pode ser conhecido sobre uma situação.

a construção da ontologia em um canal marca os limites da utilidade da teoria para a ciência da informação. Em outras palavras, a teoria da situação permite deduções uma vez que um modelo do mundo é dado em termos de objetos e canais que representam as relações entre eles. O problema principal é justamente a construção do modelo qualitativo do mundo que fornece a base para fazer inferências. 








Sinalizamos que tomamos aqui o conceito de informação como visto por xxxx em xxxxx, no qual há uma relação funcional para a caracterização do conceito, ou seja, ele deve responder à uma intenção teleológica e de utilidade para os usuários, mais do que a uma busca por uma definição terminológica precisa.
estabelecer uma base sólida de conhecimento científico para orientar a pesquisa e a prática nessa área.




Assim, será dada especial atenção ao diálogo da Ciência da Informação com a Computação, e




ênfase à recuperação de informações, considerando sua vertente pragmática e tecnológica, 

. É importante destacar que essa relação já foi observada por diversos autores no passado, sendo portanto uma vertente comum aos estudos informacionais [@borko1964; @harmon1971]. No entanto, renovar esse empenho é fundamental para a contínua evolução da ciência, o que demanda dos cientistas da informação a realização periódica de revisões em seus pressupostos ou mesmo a redefinição dos elementos estruturais fundamentais, quando se faz necessário [@zins2007].

De modo mais específico, serão buscados os principais marcos e os pioneiros que exerceram influência no desenvolvimento da interação homem-máquina quanto ao processamento de linguagem natural, no período compreendido entre o nascimento da computação moderna, em 1936, e as primeiras experiências de tradução automatizada (_machine translation_), em 1954. Serão destacados os autores, as obras de referência e os conceitos centrais em suas abordagens. Adicionalmente serão acrescentados comentários destinados a oferecer um contexto narrativo aos textos.

Como referência inicial apresentamos os trabalhos seminais sobre _computabilidade_. O artigo intitulado "An Unsolvable Problem of Elementary Number Theory", publicado em 1936, por Alonzo Church, apresenta uma abordagem da teoria dos números elementares, introduzindo o conceito de "calculabilidade efetiva" na matemática, com base em seu _cálculo lambda_, trabalhando as limitações da computabilidade [@church1936]. Logo em seguida, no mesmo ano, no artigo "On computable numbers, with an application to the Entscheidungsproblem", Alan Turing, utilizando o recurso teórico da _máquina de Turing_ (um modelo abstrato de computador voltado aos aspectos lógicos do seu funcionamento), apresenta uma abordagem equivalente demonstrando que o _problema da decisão_, em alemão "Entscheidungsproblem", é impossível de ser decidido algoritmicamente [@turing1936]. A implicação destes trabalhos será determinante para a história da computação e a teoria da computabilidade, indicando que é impossível criar um algoritmo genérico para resolver todos os problemas computacionais. Essas construções fornecerão as bases teóricas para o estudo das capacidades e limitações dos sistemas computacionais, influenciando o desenvolvimento das linguagens de computação, dos algoritmos e dos computadores modernos.

Em 1945, 11 anos após a apresentação da máquina de Turing, Vannevar Bush publicará o artigo “As We May Think”, apresentando a ideia do _Memex_ (derivada de memory extender), uma máquina eletromecânica do futuro capaz de realizar cálculos complexos, em velocidades extremamente altas, podendo auxiliar ou mesmo substituir as pessoas em atividades que envolvem esforços repetitivos. Essa máquina teórica modificaria não apenas a forma e o volume do conhecimento acessível, mas também permitiria a criação de novas formas de associação entre as informações, chamados por ele de trilhas, nas quais os conteúdos poderiam ser vinculados de modo similar ao que ocorre com os pensamentos humanos [@bush1945]. A contribuição de Bush terá grande influência no desenvolvimento futuro dos computadores pessoais, bem como no surgimento do conceito de hipertexto, que foi introduzido duas décadas mais tarde, em 1965, por Ted Nelson.

Segundo John Hutchins (1997), o marco inicial da aplicação de computadores na tarefa de tradução automática de linguagem natural, conhecida como _machine translation_, pode ser atribuído às sugestões feitas em março 1947 por Warren Weaver a Norbert Wiener. Inicialmente essas sugestões foram recusadas por Norbert Wiener, no entanto Weaver continuou em comunicação com outros pesquisadores. Somente em janeiro de 1954, quase sete anos depois, as ideias precursoras terão uma demonstração prática nos primeiros sistemas de tradução automática de linguagem natural. Importante destacar que outros esforços de tradução mecanizada existiram anteriormente, no entanto, ao que parece, estes autores não eram do conhecimento dos pioneiros do _machine translation_ entre os anos de 1940 e começo de 1950 [@hutchins1997].

O trabalho de Norbert Wiener, no livro "Cybernetics: Or Control and Communication in the Animal and the Machine", publicado em 1948, será significativo para o entendimento do funcionamento da linguagem na interação entre humanos e máquinas. Este trabalho introduziu o termo _cibernética_ e atribuiu significado à essa nova disciplina, que visava compreender a comunicação em animais e máquinas. A cibernética se estabeleceu como uma teoria fundamental para o estudo do controle de máquinas modernas, por meio de sistemas que se retroalimentam, enfatizando a importância do fluxo de informação e o uso da teoria estatística no projeto de sistemas autorreguláveis, capazes de manter um comportamento específico mesmo diante de perturbações externas [@wiener1948]. Ou seja, a possibilidade de mecanismos automatizados de controle poderem ser programados para direcionar um comportamento desejado.

Ainda em 1948, o matemático e criptógrafo Claude Shannon publicará o trabalho “The Mathematical Theory of Communication”, tratando do problema de transferência de mensagens por meio de um canal, como forma de tornar a comunicação mais precisa e eficiente [@shannon1948]. Com a reimpressão do trabalho e as contribuições de Warren Weaver, visando a simplificação da explicação sobre os achados de Shannon para o público de fora do campo da matemática, o modelo da Teoria Matemática da Comunicação (TMC), também conhecido como modelo Shannon-Weaver, será atribuído a ambos. É interessante destacar que no estudo da computação, a teoria de Shannon-Weaver será compreendida nos estudos da teoria da informação. 

Dois anos após, em 1950, Alan Turing apresentará o artigo “Computing Machinery and Intelligence”. Se trata de um artigo pioneiro sobre inteligência artificial, trazendo o conceito do que hoje conhecido por teste de Turing. A ideia central do texto busca determinar se uma máquina pode exibir comportamento inteligente indistinguível do de um ser humano. O autor ainda levantará questões sobre a natureza da mente humana e a possibilidade de replicar a inteligência por meio de máquinas [@turing1950].

Um anos depois, em 1951, no artigo intitulado “Prediction and entropy of printed English”, Claude Shannon apresentará um trabalho estatístico sobre o idioma natural do inglês impresso, desenvolvendo os conceitos de predição e de entropia. Em linhas gerias, o método se baseava no conhecimento das estatísticas linguísticas presentes naqueles que falam a língua, e sua eficácia dependeria de resultados experimentais na previsão da próxima letra quando o texto anterior é conhecido. O estudo apresenta os resultados desses experimentos de previsão e desenvolve algumas propriedades de um preditor ideal. Essa abordagem se fundamenta na compreensão das regularidades e padrões linguísticos, permitindo antecipar a próxima letra com base no texto anterior, contribuindo para a análise e compreensão da estrutura e comportamento da linguagem [@shannon1951].

Quanto ao primeiro experimento de machine translation, em 1954, os dois principais pesquisadores envolvidos foram Paul L. Garvin, que fez o trabalho linguístico, e Peter Sheridan, responsável pela programação. Foi desenvolvido um sistema de pequena escala para traduzir frases do russo para o inglês. Em 7 de janeiro de 1954 a demonstração ocorreu na sede da IBM em Nova York, com testes na tradução entre o idioma russo e inglês. Foram inseridas várias mensagens curtas, compreendidas no intervalo de 250 palavras do dispositivo, que incluíam breves declarações em russo sobre: política, direito, matemática, química, metalurgia, comunicações e assuntos militares. As frases foram então transformadas para inglês sem intervenção humana [@hutchins1997].

Com base nos avanços atuais das tecnologias de processamento de linguagem natural e aprendizado de máquina, é possível considerar a abordagem de Shannon para um preditor de texto como uma das precursoras dos modelos de previsão de próxima palavra. Esses modelos têm ganhado destaque devido à sua aplicação em larga escala, impulsionada pelo progresso dos algoritmos de aprendizado de máquina e pelo aumento do poder de processamento computacional. A contribuição de Shannon nessa área representa um marco importante na evolução desses modelos, que visam melhorar a capacidade de antecipação e sugestão de palavras com base no contexto textual.

Além disso, o modelo de previsão de próxima palavra tem sido utilizado em diversas outras aplicações, como tradução automática, correção automática de texto, completamento de frases, geração automática de texto e até mesmo em assistentes virtuais. A previsão de próxima palavra é uma técnica fundamental para melhorar a eficiência e a precisão dessas aplicações.

A retomada do percurso histórico empreendido nesse resumo preliminar é importante devido à herança que as tecnologias de interação atuais possuem desse desenvolvimento. Isso se deve ao fato de que essas tecnologias computacionais colocam a interação em linguagem natural - e sua consequente tradução - como elemento central na operação de máquinas. Portanto, compreender as origens desse desenvolvimento histórico proporciona uma base sólida para o entendimento das interações homem-máquina contemporâneas.

Em que pese as raízes históricas da CI remontarem a interrelação de diversos campos ciêntificos quanto ao problema da disponibilidade de acesso à informação, serão as modificações impulsionadas pelos esforços de guerra e a estrutura de reprodução do capitalismo do século XX, os fatores responsáveis pela ampliação exponencial da produção e difusão de informações. E é nesse contexto de explosão informacional, principalmente após a segunda guerra, que ocorrerá a consolidação da CI enquanto um campo disciplinar, com as raízes estabelecidas na necessidade de especialização do trato informacional, culminando no início dos anos de 1960 na formulação dos primeiros conceitos da CI e na promoção de debates voltados à delimitação do seu campo [@pinheiro1995; @alvares2010].

Nessa esteira, a utilização massiva de tecnologias computacionais para o processamento de linguagem natural, em parte derivadas do _machine translation_, que atualmente são denominadas como _Large Language Models_ (LLM), representam um novo ciclo de ruptura na produção social contemporânea. Essas tecnologias têm sido adotadas rapidamente nas atividades produtivas, o que corrobora a visão prevista por Bush em seu artigo "As We May Think", onde ele antecipa a relevância dessas tecnologias na vida cotidiana e, principalmente, em temas que serão centrais à Ciência da Informação, como: a produção e difusão de informação científica; a classificação e recuperação de conteúdo; os processos de aprendizagem e a gestão do conhecimento; entre outros.

Os recentes avanços no processamento de linguagem natural destacam a importância de uma compreensão qualitativa aprofundada, por parte do campo da Ciência da Informação, sobre a renovação das práticas de recuperação de informações. A revisão cronológica apresentada neste trabalho, que aborda as origens do desenvolvimento de sistemas computacionais de tradução automática, contribui para alcançar esse objetivo. Nesse sentido, a adoção de uma perspectiva centrada na tecnologia como meio de observação da Ciência da Informação desempenha um papel fundamental na compreensão desse campo. Essa abordagem não apenas faz parte da essência dessa disciplina, mas também traz consigo novas perspectivas aos profissionais envolvidos, enriquecendo a capacidade de compreensão dos desafios enfrentados.

## Referências
