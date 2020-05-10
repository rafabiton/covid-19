# covid-19
Análise de artigos científicos referentes á Covid – 19
De acordo com o CDC (Centers for Disease Control and Prevention), o novo coronavírus de 2019 (Covid – 19) é um vírus identificado como a causa de um surto de doença respiratória detectado pela primeira vez em Wuhan, na China.

Desde o início, muitos dos pacientes do surto em Wuhan teriam algum vínculo com um grande mercado de frutos do mar e animais silvestres. Um número crescente de pacientes supostamente não teve exposição ao mercado de animais, indicando a ocorrência de disseminação de pessoa para pessoa. O vírus já se espalhou para praticamente todos os países do mundo, causando muitas mortes e sérios problemas na economia.

Devido a isso, a Casa Branca dos Estados Unidos junto com pesquisadores e líderes do Allen Institute for AI, Chan Zuckerberg Initiative (CZI), Georgetown University’s Center for Security and Emerging Technology (CSET), Microsoft, e o National Library of Medicine (NLM) at the National Institutes of Health lançaram uma base de dados com artigos publicados sobre o COVI-19, SARS-CoV-2 e vírus do grupo dos coronavírus.

A base de dados possui mais de 59.000 artigos científicos (cerca de 8Gb) sobre essas doenças, sendo que o objetivo principal é ajudar pesquisadores e profissionais da saúde obterem informações relevantes sobre esses assuntos. Leia alguns trechos do chamado (call to action) da Casa Branca:

“A Casa Branca se une a essas instituições ao emitir um apelo à ação dos especialistas em inteligência artificial da nação para desenvolver novas técnicas de mineração de texto e dados que podem ajudar a comunidade científica a responder perguntas científicas de alta prioridade relacionadas ao COVID-19”.

“Precisamos nos unir como empresas, governos e cientistas e trabalhar para trazer nossas melhores tecnologias para a biomedicina, epidemiologia, IA e outras ciências. O recurso e desafio da literatura COVID-19 estimulará esforços que podem acelerar o caminho para soluções em COVID-19“.

“Uma das aplicações mais imediatas e impactantes da IA é a capacidade de ajudar cientistas, acadêmicos e tecnólogos a encontrar as informações corretas em um mar de artigos científicos para impulsionar a pesquisa mais rapidamente“.

“É difícil para as pessoas revisarem manualmente mais de 50.000 artigos e sintetizarem suas descobertas. Avanços recentes em tecnologia podem ser úteis aqui“.

Diante deste cenário, farei a exploração e tratamento dos dados, aplicação de alguns algoritmos de NLP (Natural Language Processing) específicos para dados de saúde, contrução de um modelo, treinamento e validação.

As solicitações feitas pelo governo Americano dizem respeito ao que é citado nos artigos científicos, mais especificamente o que a literatura diz sobre:

Dados e potenciais fatores de riscos:
Tabagismo e doença pulmonar pré-existente;
Doenças respiratórias pré-existentes e outras comorbidades
Recém nascidos e mulheres grávidas;
Fatores sócio econômicos e comportamentais para entender o impacto econômico do vírus.
Dinâmica de transmissão do vírus, incluindo o número total de reprodução, período de incubação, intervalo de incubação, modo de transmissão e fatores ambientes;
Gravidade da doença, incluindo risco de fatalidade entre pacientes hospitalizados sintomáticos e grupos de pacientes de alto risco;
Suscetibilidade da população;
Medidas de mitigação da saúde pública que podem ser eficazes para o controle
Faremos a recuperação de informações de bases de dados de artigos e para isso, vamos usar a base de dados dos artigos científicos e aplicar algumas técnicas diferentes de mineração de textos e processamento de linguagem natural, utilizando bibliotecas como NLTK (Natural Language Toolkit), spaCy, WordCloud e fuzzywuzzy.

Focaremos na etapa de preparação e visualização dos textos, como por exemplo: contagem de termos frequentes, nuvem de palavras e aplicação de algoritmos para agrupamento, como o k-means!

Faremos também sistemas de busca em textos que levam em consideração palavras-chave e similaridade entre documentos utilizando TF-IDF (Term Frequency – Inverse Document Frequency)

O código-fonte foi desenvolvido utilizando a linguagem Python na plataforma Google Colab e está comentado linha por linha, de forma que seja de fácil compreensão. 
