---
title: Módulo 4 - Interdisciplinaridade na Ciência da Informação
# subtitle: 
tags:
  - science information
  - chronography
  - information retrieval
  - reinforcement learning
  - large language models
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
date: 17/07/2023
abstract: >-
    Resumo do Módulo 4 da disciplina "Cronografia da Ciência da 
    Informação",  "Interdisciplinaridade na Ciência da Informação", 
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

# Módulo 4: Interdisciplinaridade na Ciência da Informação

Este resumo apresenta um recorte sobre o percurso histórico da interdisciplinaridade na Ciência da Informação (CI). A natureza cronográfica apresentada neste texto pretender identificar os eventos relacionados ao estudo da informação em seu diálogo com a tecnologia, principalmente na área da _Recuperação da Informação_ (RI).

Uma vez que os estudos sobre a interdisciplinaridade da Ciência da Informação lançam um olhar sobre as interseções de conteúdos de diferentes campos disciplinares na construção do conhecimento científico, este trabalho buscará, através de uma análise das tecnologias contemporâneas de Processamento de Linguagem Natural (PLN), identificar os marcos do seu desenvolvimento, a relação temporal que estabelecem e a presença desse variado esforço de diferentes ciências na compreensão dos problemas do seu objeto de estudo: a _informação_.

O desenvolvimento recente de novas formas sociotécnicas de relacionamento com a linguagem, por meio de modelos pré-treinados de recuperação da informação, recoloca o desafio de compreender os avanços tecnológicos e as alternativas possíveis, aos pesquisadores da ciência da informação, nos sistemas de processamento da linguagem e de recuperação de informações.

Até recentemente, o processo de recuperação da informação era predominantemente conduzido por meio de um método controlado de indexação e busca por termos, mesmo com o apoio de sistemas computacionais. Contudo, avanços recentes na área têm introduzido abordagens que utilizam Grandes Modelos de Linguagem (GML) ou _Large Language Models (LLM)_, em inglês. Esses modelos se destacam pela capacidade de gerar conteúdo informacional diversificado, abrangendo textos, imagens e áudios, com base em um modelo computacional probabilístico manipulando uma imensa disponibilidade de informações e interagindo por meio de linguagem natural com agentes humanos. É essa característica distintiva que vem sendo aplicada na recuperação de informações em sistemas conversacionais de interação homem-máquina. 

No caso mais destacado - ChatGPT, considerando o crescimento e a quantidade da base de usuários, especialmente por meio da integração de tecnologias como aprendizado profundo (_deep learning_), aprendizado não supervisionado, ajuste fino de instrução, aprendizado multitarefa, aprendizado em contexto e aprendizado por reforço com feedback humano (_Reinforcement learning from Human Feedback - RLHF_) [@chatgpt2022; @wu2023].

Entender esse novo arranjo sociotécnico que envolve a seleção e a geração de informações possibilita uma avaliação crítica das limitações e contribuições desses modelos, ampliando a capacidade de identificar áreas não exploradas, desafios sem soluções e suscitar perguntas que demandem investigações aprofundadas.

Quais critérios seriam necessários para avaliar a capacidade de recuperação de informações e de geração de linguagem natural presentes em tecnologias de GML? Como estabelecer métricas para comparar diferentes modelos e selecionar, a cada caso de uso, a melhor tecnologia disponível?

Oferecer resposta à essas perguntas não é uma tarefa trivial. No entanto, em que pese a atualidade e o desenvolvimento recente dessas novas abordagens de processamento da linguagem natural, não seriam essas perguntas similares às realizadas nas experiências do projeto Cranfield I e II e no desenvolvimento do SMART, quando propõem os conceitos de taxa de revocação (_recall ratio_) e de taxa de precisão (_precision ratio_), propostas por Aitchison [-@aitchison1963], Cleverdon [-@cleverdon1967] e Salton [-@salton1965], abordadas no resumo do módulo 3 desta disciplina? 

Aqui, salientamos também a visão de interdisciplinaridade apresentada por Saracevic [-@saracevic1995], ao indicar que não devemos estudar propriamente assuntos na Ciência da Informação, mas sim problemas. A abordagem centrada em problemas atinge diferentes temas e disciplinas, não respeitando o estabelecimento de fronteiras rígidas. A área da recuperação da informação, para o autor, é tomada como o espaço de consolidação maior dessa interdisciplinaridade. Afinal, várias disciplinas são mobilizadas para responder às questões sobre como ofertar informações úteis e como promover interações efetivas para os usuários frente à explosão informacional ocorrida.

Assim, quanto aos desenvolvimentos dos modelos posteriores às formas de recuperação da informação já vistas, quais novas perguntas se colocaram e como elas foram respondidas? Ou, como apontou Saracevic [-@saracevic1995], como se deu a organização intelectual da informação, a sua recuperação, interação e quais sistemas e técnicas foram usadas nesse processo?

Sobre essas últimas questões é que nos debruçaremos neste resumo. Faremos um recorte temporal a partir dos anos 1970, após a divulgação da tese _Procedures as a Representation for Data in a Computer Program for Understanding Natural Language_ sobre o desenvolvimento do sistema _SHRDLU_, visto anteriormente [@winograd1971]. Serão destacados os autores, as obras de referência e os conceitos centrais em suas abordagens. Adicionalmente serão acrescentados comentários destinados a oferecer um contexto narrativo aos textos.











Os projetos consistiram numa pesquisa, inicialmente sem a utilização de computadores, com o objetivo de melhorar a eficiência dos sistemas de recuperação de informação, avaliando melhores linguagens e métodos de indexação [@cleverdon1960; @cleverdon1967].

O primeiro projeto, iniciado em abril de 1958, foi caracterizado pela comparação de 4 modelos de indexação sob uma coleção de documentos de aviação: Classificação Decimal Universal (CDU), catálogo de assuntos em ordem alfabética, esquema de classificação facetada, sistema de termo único. Os testes envolveram a comparação da eficiência relativa de cada um dos quatro índices em comparação a um conjunto de questões. As questões usadas foram produzidas por representantes de cerca de cinquenta organizações no Reino Unido, Estados Unidos, Canadá e Holanda [@cleverdon1960]. 

Ao tratar detalhadamente das razões de fracasso ou de sucesso na busca de informação relevante, o projeto objetivou levantar os requisitos que um sistema de recuperação de informação deveria atender. Cleverdon [-@cleverdon1960, p.9] indica que a ausência de experimentos práticos atrelados às teorias de indexação a superestimavam, "todos aqueles que tentam resolver os problemas de recuperação de informações estão trabalhando muito no escuro, incertos quanto aos problemas reais e totalmente incapazes de aplicar quaisquer medições às soluções propostas". 

Assim, conclui que o requisito principal para avaliar a recuperação da informação é um padrão de medição reconhecido e um método de medição satisfatório. E, com o projeto, esperavam ter dados suficientes para formar um padrão de medição para sistemas de recuperação [@cleverdon1960]. Em termos de desempenho, foi constatado que todos os sistemas operavam em níveis próximos de eficiência [@cleverdon1967].

Em 1963, cinco anos após o início dos experimentos, os testes realizados com a documentação de metalurgia da _Western Reserve University_, seviram para estabelecer duas medidas utilizadas para avaliar os sistemas, a taxa de revocação (_recall ratio_) e a taxa de precisão (_precision ratio_) [@aitchison1963; @cleverdon1967]. 

![Revocação/Precisão, [@cleverdon1967, p. 182.]](https://github.com/gabrielmacedo/ci/assets/20596966/7afc38a1-ca30-4a0b-88ff-be5259f718da)

Os resultados dos testes indicaram a relação inversa entre revocação e precisão. Considerando que a taxa de revocação máxima possível de 100 por cento pode ser obtida ao recuperar todos os documentos disponíveis, a melhoria na taxa de precisão implicaria, portanto, numa queda na taxa de revocação. De forma inversa, para aumentar o número de documentos relevantes recuperados seria necessário aumentar, em maior medida, o número de documentos não relevantes também recuperados. "Este é sempre o caso ao operar dentro de um determinado sistema" [@cleverdon1967, p. 179] (tradução automatizada com correções manuais).

Outra abordagem de indexação foi proposta por Salton com o sistema SMART (_System for the Mechanical Analysis and Retrieval of Text_), desenvolvido entre os anos 1960 e 1970. Embora tratasse de problemas semalhantes aos que estavam sendo trabalhados em Cranfield, ao comparar os efeitos de diferentes formas de indexação de textos, havia diferenças expressivas entre as duas abordagens. A mais significativa delas consistia na utilizava de computadores por Salton, permitindo processamento avançado de dados e algoritmos complexos, enquanto os experimentos de Cranfield dependiam de técnicas manuais e estatísticas [@cleverdon1967]. Essa distinção no uso da tecnologia permitiu que Salton explorasse análises mais sofisticadas.

![Diferentes métodos de avaliação do SMART, apresenta os "Valores de revocação e precisão para a solicitação _Equações Diferenciais_" - [@salton1965, p. 397]. (tradução automatizada com correções manuais)](https://github.com/gabrielmacedo/ci/assets/20596966/d3d80803-eacc-4b4f-a1d2-492d38704065)

Uma das principais contribuições do sistema SMART foi o desenvolvimento do modelo de espaço vetorial (_vector space model_) para recuperação de informações. Esse modelo utilizava representações matemáticas dos documentos e das consultas para calcular a similaridade entre eles. Em vez de se basear apenas na presença ou ausência de palavras-chave, o modelo vetorial considerava a relevância e importância relativa dos termos, permitindo uma recuperação mais precisa. Além disso o SMART implementou a indexação automática de documentos, utilizando técnicas como a extração de palavras-chave e a atribuição de pesos aos termos com base em sua frequência nos documentos. O SMART também introduziu a ideia de consultas interativas, permitindo aos usuários refinar suas consultas com base nos resultados apresentados. Isso possibilitava uma interação mais dinâmica entre o usuário e o sistema de recuperação de informações [@salton1965].

> "O sistema pode ser controlado pelo usuário de modo que uma solicitação de pesquisa possa ser processada primeiro em um modo padrão; o usuário fica então livre para analisar a saída obtida e, dependendo de seus requisitos adicionais, uma reavaliação da solicitação pode ser solicitada sob novas condições. A nova saída pode ser novamente examinada e o processo iterado até o momento em que o tipo e a quantidade correta de informações sejam recuperados" [@salton1965]. (tradução automatizada com correções manuais)

Apesar das metodologias divergentes, tanto o desenvolvimento do SMART quanto dos projetos de Cranfield fizeram contribuições significativas para o campo da recuperação de informações. No entanto, enquanto o PNL avançava nos modelos de indexação, as tarefas de tradução automatizada (_machine translation_) passaram a ser questionadas.



Seu objetivo era superar os problemas de manipulação apenas sintática e gramatical presentes nos primeiros sistemas de tradução automatizada, como os aplicados na tradução entre inglês e russo. O autor reconhecia a necessidade de lidar com os aspectos semânticos e de conferir aos computadores a capacidade de usar um conhecimento prévio sobre os assuntos para os quais deveria oferecer resposta. O entendimento da linguagem por máquinas deveria combinar "gramática, semântica e raciocínio de uma maneira muito íntima, chamando cada parte para ajudar as outras" [@winograd1971, p. 12].

Em síntese, os eventos destacados ao longo dessas duas décadas possibilitam refletir acerca dos desafios no processamento da linguagem. Os trabalhos apresentados reforçam a centralidade dos problemas de linguística para que as máquinas interpretem a linguagem humana. Isso requer uma compreensão profunda da estrutura, significado e nuances que utilizamos aos nos comunicar. Os problemas envolvendo questões de semântica, sintaxe, análise do contexto e de interpretação das intenções do usuário demandaram posteriormente o desenvolvimento de técnicas, algoritmos e modelos para permitir o processamento eficiente da linguagem natural.

Rever o histórico apresentado neste resumo permite observar as origens das tecnologias de interação atuais. Essas tecnologias se concentram na capacidade das máquinas de entender e responder à linguagem natural. Os avanços recentes no processamento de linguagem natural, tais como os realizados pelo ChatGPT, destacam a importância de uma melhor compreensão das formas de recuperação de informações no campo da Ciência da Informação. A revisão cronográfica apresentada neste trabalho explora alguns marcos do desenvolvimento de sistemas de indexação e linguística computacional, contribuindo para esse objetivo. 

Olhar para as tecnologias por meio da Ciência da Informação é fundamental para as discussões no âmbito desta disciplina, trazendo novas perspectivas para os profissionais envolvidos. Compreender a gênese desses  proporciona uma base sólida para entender as interações entre humanos e máquinas de hoje.



A relação entre os LLM e os Transformers é intrínseca, pois os Transformers são a arquitetura de rede neural usada para construir os LLMs. Os Transformers são modelos de processamento de linguagem natural (NLP) que se destacam por sua capacidade de capturar relações de longo alcance em sequências de dados, como texto. Essa arquitetura se baseia em mecanismos de atenção para aprender representações contextualizadas de palavras ou tokens em uma sequência.

Os LLMs são versões aprimoradas dos Transformers, treinados em enormes quantidades de dados textuais para gerar, completar ou compreender texto de maneira fluente. Eles são capazes de capturar informações semânticas e contextuais complexas e produzir resultados que se assemelham à linguagem humana.


Em síntese, os GML são usados para treinamento das possibilidades de inferência e generalização dos agentes de aprendizado computacionais, auxiliando a contextualizar a linguagem e a oferta de resposta mais sofisticadas

## Linha do tempo

Linha do tempo considerando o ano de início dos eventos, projetos, trabalhos ou marcos avaliados ao longo deste resumo:

1975	Máquina de Vetores de Suporte (SVM)	Algoritmo de aprendizado supervisionado para classificação.	Vladimir Vapnik - "Estimation of Dependences Based on Empirical Data"
1986	Redes Neurais Artificiais	Modelos computacionais inspirados na estrutura do cérebro humano.	David Rumelhart, Geoffrey Hinton, Ronald Williams - "Learning representations by back-propagating errors"
2014	Word2Vec	Modelo de representação vetorial de palavras baseado em redes neurais.	Tomas Mikolov et al. - "Efficient Estimation of Word Representations in Vector Space"
2017	Transformadores (Transformers)	Arquitetura de rede neural que captura relações de longo alcance.	Vaswani et al. - "Attention is All You Need"
2018	Modelo de Linguagem Generativo Pré-Treinado (GPT)	Modelo de linguagem treinado em grandes conjuntos de dados.	Alec Radford et al. - "Improving Language Understanding by Generative Pre-training"
2020	GPT-3	Modelo de linguagem de escala gigante com 175 bilhões de parâmetros.	Brown et al. - "Language Models are Few-Shot Learners"
2021	ChatGPT	Sistema de chat baseado em GPT-3, permitindo interação em linguagem natural.	OpenAI - Lançamento público do ChatGPT

1970: Backpropagation Algorithm

Main Concepts: Algorithm for training artificial neural networks.
Academic Work / Technological Event: Seppo Linnainmaa - "The Representation of the Cumulative Rounding Error of an Algorithm as a Taylor Expansion of the Local Rounding Errors" (Link)
Relevance: The backpropagation algorithm is crucial for training neural networks, including the models underlying ChatGPT. It enables the optimization of neural network parameters by propagating error gradients backward through the network layers, facilitating the learning process.
1973: Earley Parser

Main Concepts: Parsing algorithm for context-free grammars.
Academic Work / Technological Event: Jay Earley - "An Efficient Context-Free Parsing Algorithm" (Link)
Relevance: Earley parser is an important algorithm for parsing context-free grammars, which helps in syntactic analysis and understanding of natural language. It aids in the processing of input text, enabling ChatGPT to parse and comprehend the grammatical structure of sentences.
1983: Connectionist Models of Language Processing

Main Concepts: Neural network models for natural language processing.
Academic Work / Technological Event: James L. McClelland and David E. Rumelhart - "Parallel Distributed Processing: Explorations in the Microstructure of Cognition, Volume 2" (Link)
Relevance: Connectionist models of language processing, inspired by neural network architectures, play a significant role in ChatGPT's ability to process and generate natural language. These models capture the distributed representation of linguistic information, allowing for more nuanced understanding and generation of text.
1986: Bidirectional Encoder Representations from Transformers (BERT)

Main Concepts: Pre-training and fine-tuning of transformer models for language understanding.
Academic Work / Technological Event: Jacob Devlin et al. - "BERT: Pre-training of Deep Bidirectional Transformers for Language Understanding" (Link)
Relevance: BERT is a landmark model that introduced the concept of pre-training transformer-based models on large-scale datasets. This approach significantly improved language understanding and became a foundation for subsequent advancements in language models, including ChatGPT.
1998: Recursive Neural Networks (RNN)

Main Concepts: Neural network architecture capable of processing structured recursive data.
Academic Work / Technological Event: Richard Socher et al. - "Recursive Deep Models for Semantic Compositionality Over a Sentiment Treebank" (Link)
Relevance: Recursive Neural Networks (RNNs) are relevant for ChatGPT as they provide a framework for processing structured and hierarchical information, such as syntactic and semantic structures of sentences. These networks enable the model to capture compositional relationships between words and generate coherent responses.
1998: WordNet

Main Concepts: Lexical database of semantic relationships between words.
Academic Work / Technological Event: George A. Miller - "WordNet: An Electronic Lexical Database" (Link)
Relevance: WordNet is a valuable resource for ChatGPT as it provides a structured representation of word meanings and semantic relationships. Incorporating WordNet's knowledge helps the model to understand word senses, synonyms, hypernyms, and hyponyms, improving its ability to generate contextually appropriate and semantically accurate responses.
2003: Conditional Random Fields (CRF)

Main Concepts: Probabilistic models for structured prediction, such as sequence labeling.
Academic Work / Technological Event: John Lafferty et al. - "Conditional Random Fields: Probabilistic Models for Segmenting and Labeling Sequence Data" (Link)
Relevance: Conditional Random Fields (CRFs) are useful for various natural language processing tasks, including part-of-speech tagging and named entity recognition. These models capture dependencies between input features and output labels, enhancing ChatGPT's ability to generate responses that respect linguistic structures and adhere to specific patterns.
2013: Skip-gram with Negative Sampling (Word2Vec)

Main Concepts: Word embedding model based on neural networks.
Academic Work / Technological Event: Tomas Mikolov et al. - "Efficient Estimation of Word Representations in Vector Space" (Link)
Relevance: The Word2Vec model, specifically the skip-gram with negative sampling variant, is instrumental in capturing distributed representations of words in vector space. These embeddings help ChatGPT to understand semantic relationships between words and generate more contextually coherent responses.
2014: Sequence-to-Sequence (Seq2Seq) Models

Main Concepts: Neural network models for sequence generation and machine translation.
Academic Work / Technological Event: Ilya Sutskever et al. - "Sequence to Sequence Learning with Neural Networks" (Link)
Relevance: Seq2Seq models, typically based on recurrent neural networks (RNNs) or transformers, are instrumental in tasks like machine translation and text generation. ChatGPT leverages the sequence-to-sequence paradigm to transform input queries into output responses, enabling conversational interactions.
2017: Attention Mechanism

Main Concepts: Mechanism to focus on relevant parts of input data in neural network models.
Academic Work / Technological Event: Dzmitry Bahdanau et al. - "Neural Machine Translation by Jointly Learning to Align and Translate" (Link)
Relevance: The attention mechanism plays a vital role in neural network models, including transformers. It allows ChatGPT to focus on relevant parts of the input sequence, enabling more precise understanding and generation of contextually relevant responses.
2018: Transformer-XL

Main Concepts: Transformer-based model with enhanced context understanding and longer-term dependencies.
Academic Work / Technological Event: Zihang Dai et al. - "Transformer-XL: Attentive Language Models Beyond a Fixed-Length Context" (Link)
Relevance: Transformer-XL addresses the limitation of fixed-length context in transformers, allowing models to capture longer-term dependencies in text. This improvement enhances ChatGPT's contextual understanding, enabling it to generate more coherent and contextually aware responses.

1971: Gramáticas Livres de Contexto (CFG)

Conceitos Principais: Formalismo para descrever a estrutura sintática das linguagens.
Trabalhos Acadêmicos / Eventos Tecnológicos: Noam Chomsky - "Hierarchy of Formal Languages" (Link)
Relevância: O uso de gramáticas livres de contexto é relevante para o ChatGPT, pois fornece uma estrutura formal para descrever a estrutura sintática das linguagens naturais. Com base nesse formalismo, o ChatGPT pode compreender e gerar frases gramaticalmente corretas, auxiliando na produção de respostas coerentes e inteligíveis.
1972: Autômatos Finitos Determinísticos (DFA)

Conceitos Principais: Modelos computacionais de processamento de linguagem.
Trabalhos Acadêmicos / Eventos Tecnológicos: Michael O. Rabin e Dana Scott - "Finite Automata and Their Decision Problem" (Link)
Relevância: Os autômatos finitos determinísticos (DFA) são importantes para o ChatGPT, pois fornecem um modelo teórico para o processamento de linguagem. Embora o ChatGPT utilize abordagens mais avançadas, a compreensão de conceitos fundamentais de autômatos finitos é relevante para entender como os modelos de linguagem podem lidar com a estrutura e o processamento de sequências de texto.
1975: Máquina de Vetores de Suporte (SVM)

Conceitos Principais: Algoritmo de aprendizado supervisionado para classificação e regressão.
Trabalhos Acadêmicos / Eventos Tecnológicos: Vladimir Vapnik - "Estimation of Dependences Based on Empirical Data" (Link)
Relevância: Os Support Vector Machines (SVMs) são relevantes para o ChatGPT por serem uma técnica de aprendizado utilizada para classificação e regressão. A compreensão desses algoritmos é importante para entender como o ChatGPT pode ser treinado e ajustado para responder apropriadamente a diferentes tipos de entrada e fornecer respostas relevantes e úteis aos usuários.
1980: Modelos Ocultos de Markov (HMM)

Conceitos Principais: Modelos probabilísticos para sequências de eventos.
Trabalhos Acadêmicos / Eventos Tecnológicos: L. E. Baum e outros - "A Maximization Technique Occurring in the Statistical Analysis of Probabilistic Functions of Markov Chains" (Link)
Relevância: Os Modelos Ocultos de Markov são relevantes para o ChatGPT por serem modelos probabilísticos capazes de modelar sequências de eventos. Esses modelos são úteis para entender e prever a estrutura e a probabilidade de uma sequência de palavras, auxiliando o ChatGPT a gerar respostas coerentes e contextualmente relevantes.
1986: Redes Neurais Artificiais

Conceitos Principais: Modelos computacionais inspirados na estrutura do cérebro humano.
Trabalhos Acadêmicos / Eventos Tecnológicos: David Rumelhart, Geoffrey Hinton, Ronald Williams - "Learning representations by back-propagating errors" (Link)
Relevância: As Redes Neurais Artificiais são fundamentais para o ChatGPT, pois são modelos computacionais inspirados no funcionamento do cérebro humano. Essas redes têm a capacidade de aprender e representar informações complexas, permitindo ao ChatGPT compreender e gerar texto em linguagem natural de maneira mais sofisticada e contextualmente adequada.
1997: Algoritmo de PageRank

Conceitos Principais: Algoritmo de classificação de páginas da web para mecanismos de busca.
Trabalhos Acadêmicos / Eventos Tecnológicos: Sergey Brin e Lawrence Page - "The Anatomy of a Large-Scale Hypertextual Web Search Engine" (Link)
Relevância: O algoritmo de PageRank é relevante para o ChatGPT, pois foi uma das bases para a construção de mecanismos de busca eficientes e escaláveis. Embora o ChatGPT não seja um mecanismo de busca, a capacidade de organizar e classificar informações é fundamental para gerar respostas relevantes e informativas com base na entrada do usuário.
2001: Support Vector Machines (SVM)

Conceitos Principais: Algoritmo de aprendizado de máquina para classificação e regressão.
Trabalhos Acadêmicos / Eventos Tecnológicos: Corinna Cortes e Vladimir Vapnik - "Support-Vector Networks" (Link)
Relevância: Os Support Vector Machines (SVMs) são relevantes para o ChatGPT por serem uma técnica de aprendizado utilizada para classificação e regressão. A compreensão desses algoritmos é importante para entender como o ChatGPT pode ser treinado e ajustado para responder apropriadamente a diferentes tipos de entrada e fornecer respostas relevantes e úteis aos usuários.
2014: Word2Vec

Conceitos Principais: Modelo de representação vetorial de palavras baseado em redes neurais.
Trabalhos Acadêmicos / Eventos Tecnológicos: Tomas Mikolov et al. - "Efficient Estimation of Word Representations in Vector Space" (Link)
Relevância: O Word2Vec é relevante para o ChatGPT, pois é uma técnica de representação de palavras que captura informações semânticas e relacionamentos entre palavras. Isso permite que o ChatGPT compreenda e gere texto que reflete a semântica e o contexto das palavras utilizadas, melhorando a qualidade e a relevância das respostas geradas.
2017: Transformadores (Transformers)

Conceitos Principais: Arquitetura de rede neural que captura relações de longo alcance.
Trabalhos Acadêmicos / Eventos Tecnológicos: Vaswani et al. - "Attention is All You Need" (Link)
Relevância: A arquitetura dos Transformadores é essencial para o ChatGPT, permitindo que o modelo capture relações de longo alcance em sequências de texto. Os mecanismos de atenção dos Transformadores são fundamentais para compreender e gerar respostas coerentes e contextualmente relevantes, melhorando a capacidade do ChatGPT de entender e responder às perguntas e comandos dos usuários.
2018: Modelo de Linguagem Generativo Pré-Treinado (GPT)

Conceitos Principais: Modelo de linguagem treinado em grandes conjuntos de dados.
Trabalhos Acadêmicos / Eventos Tecnológicos: Alec Radford et al. - "Improving Language Understanding by Generative Pre-training" (Link)
Relevância: O modelo de linguagem generativo pré-treinado (GPT) é um marco importante para o ChatGPT, pois demonstra como modelos de linguagem podem ser treinados em grandes conjuntos de dados para gerar texto de alta qualidade. O GPT estabeleceu a base para o desenvolvimento de modelos de linguagem em grande escala, como o ChatGPT, permitindo que ele gere respostas mais fluentes e coerentes aos usuários.
2020: GPT-3

Conceitos Principais: Modelo de linguagem de escala gigante com 175 bilhões de parâmetros.
Trabalhos Acadêmicos / Eventos Tecnológicos: Brown et al. - "Language Models are Few-Shot Learners" (Link)
Relevância: O GPT-3 é relevante para o ChatGPT, pois é um modelo de linguagem de escala gigante que demonstra a capacidade de aprender e gerar texto de alta qualidade em diversos contextos. O GPT-3 estabeleceu novos padrões em termos de tamanho e complexidade dos modelos de linguagem, inspirando o desenvolvimento do ChatGPT e aprimorando sua capacidade de gerar respostas mais abrangentes e informativas.
2021: ChatGPT

Conceitos Principais: Sistema de chat baseado em GPT-3, permitindo interação em linguagem natural.
Trabalhos Acadêmicos / Eventos Tecnológicos: OpenAI - Lançamento público do ChatGPT (Link)
Relevância: O ChatGPT é o produto final desta linha do tempo, construído sobre os avanços anteriores em modelos de linguagem e técnicas de processamento de linguagem natural. O ChatGPT incorpora os conceitos e técnicas relevantes mencionados anteriormente, permitindo interação em linguagem natural e geração de respostas contextuais e inteligentes. É uma aplicação prática e relevante dos avanços da inteligência artificial e do processamento de linguagem natural.

## Referências
