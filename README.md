# Sumário do artigo

Nos últimos anos, as tecnologias emergentes e as melhorias nos protocolos da Internet facilitaram a comunicação entre dispositivos, levando ao surgimento da Internet das Coisas (IoT). A IoT é uma combinação de tecnologias embarcadas, comunicações sem fio, sensores e dispositivos físicos conectados à Internet. Isso tem como objetivo simplificar as atividades humanas e melhorar a experiência do usuário. Para alcançar esse objetivo, a análise de dados desempenha um papel crucial.

A IoT gera uma quantidade significativa de dados, e a ciência de dados, que usa técnicas como mineração de dados e aprendizado de máquina, é fundamental para extrair insights e padrões desses dados. A aplicação dessas técnicas envolve a definição de tipos de dados, modelos de dados e a seleção de algoritmos eficientes. Além disso, é importante desenvolver algoritmos que possam lidar com as características específicas dos dados da IoT e enfrentar desafios de escala e velocidade de dados em tempo real. 

 

Em resumo, a IoT está gerando uma grande quantidade de dados e a ciência de dados desempenha um papel crucial na análise desses dados para melhorar as aplicações IoT e abrir novas oportunidades de desenvolvimento.

 

O objetivo deste artigo é responder às seguintes questões:

A) Como os algoritmos de aprendizado de máquina podem ser aplicados à IoT inteligente de dados? Aqui foram considerado três conceitos: a aplicação IoT, as características dos dados da IoT e a visão orientada por dados de aprendizado de máquina.

B) Qual é a taxonomia dos algoritmos de aprendizado de máquina que pode ser adotado em IoT? Aqui foi revelado que  existem oito grupos principais de algoritmos aplicáveis a dados IoT. Esses algoritmos são categorizados de acordo com suas semelhanças estruturais,  tipos de dados que podem manipular e a quantidade de dados que podem processar em um tempo razoável.

C) Quais são as características dos dados IoT no mundo real? 

Para obter uma visão mais profunda dos dados inteligentes da IoT, os padrões devem ser extraídos e os dados gerados interpretados.

D) Por que a cidade inteligente é um caso de uso típico de aplicações IoT? 
Uma cidade inteligente foi selecionada como nosso principal caso de uso em IoT portrês razões: Primeiro, entre todos os artigos revisados, o foco de 60% está no campo das cidades inteligentes. Em segundo lugar, as cidades inteligentes incluem muitos dos outros casos de uso em IoT. Terceiro, existem muitos conjuntos de dados abertos para aplicações de cidades inteligentes que sejam facilmente acessíveis para pesquisadores. Além disso, um algoritmo Support Vector Machine (SVM) é implementado no tráfego de dados da cidade inteligente Aarhus para prever horas de trânsito durante um dia. Ao responder às perguntas acima sobre dados inteligentes Iot e algoritmos de aprendizado de máquinas seríamos capazes de escolher o melhor algoritmo de aprendizado de máquina que pode lidar com características de dados inteligentes da IoT.

 

Neste contexto, o artigo é organizado da seguinte forma:

2. Literatura a respeito – artigos relacionados são revisados e reportados;

3. IoT – Aplicações IoT e protocolos de comunicação, estruturas de computação, arquitetura IoT e segmentos de cidades inteligentes são revisados, explicados, resumidos e ilustrados. Computer framework é abordao – Fog computing, Edge computing e Cloud computing.

4. Cidade Inteligente - O conceito de cidades inteligentes tem ganhado destaque devido à necessidade de melhorar a qualidade de vida e a eficiência dos serviços urbanos. Com o aumento da população e da complexidade das infraestruturas urbanas, as cidades buscam soluções para lidar com desafios urbanos em larga escala. A Internet das Coisas (IoT) desempenha um papel fundamental na coleta de dados do ambiente urbano, permitindo que as cidades usem informações em tempo real e sistemas de monitoramento inteligente para responder de maneira mais eficaz a situações emergenciais, como desastres naturais. Ao adotar tecnologias IoT, os ativos urbanos podem ser interconectados, tornando-os mais visíveis e gerenciáveis. O objetivo das cidades inteligentes é melhorar serviços como gestão de tráfego, fornecimento de água, e eficiência energética, ao mesmo tempo em que melhora a qualidade de vida dos habitantes urbanos. Além disso, as cidades inteligentes buscam reduzir despesas em áreas como saúde pública, segurança, transporte e gestão de recursos, o que pode impulsionar suas economias. A visão de longo prazo para uma cidade inteligente é que todos os sistemas e estruturas urbanas monitorariam automaticamente suas próprias condições e se autoreparariam conforme necessário. Isso representa um nível avançado de automação e eficiência na gestão urbana.

Os casos de utilização para cidades inteligentes consistem em energia inteligente, mobilidade inteligente, cidadãos inteligentes e planejamento urbano
 

5. Taxonomia de algoritmos de aprendizado de máquina - Algoritmos de aprendizado de máquina em oito categorias com base em estudos recentes sobre os dados de IoT e a frequência dos algoritmos de aprendizado de máquina são revisados.
 
6. Discussão da taxonomia de algoritmos de aprendizado de máquina – os algoritmos correspondentes a aplicações específicas de cidades inteligentes são abordados.
 

7. Tendencias futuras de pesquisas.

8. Conclusões
A IoT consiste em um grande número de diferentes dispositivos conectados entre si e transmitem grandes quantidades de dados. A cidade inteligente é uma das aplicações mais importantes da IoT e fornece vários serviços em domínios como energia, mobilidade e planejamento urbano. Esses serviços podem ser aprimorados e otimizados analisando os dados inteligentes coletados destas áreas. Para extrair conhecimento dos dados coletados, muitos algoritmos analíticos de dados podem ser aplicados. Escolhendo um algoritmo adequado para IoT específica ou aplicação de cidade inteligente é uma questão importante. Neste artigo, muitos estudos de análise de dados de IoT são revisados para resolver esse problema. Aqui, três fatos devem ser considerados na aplicação de algoritmos de análise de dados para dados inteligentes. O primeiro é que diferentes aplicações em IoT e cidades inteligentes possuem características próprias, como número de dispositivos e tipos de dados que eles geram. O segundo é que os dados gerados terão características específicas que devem ser consideradas. O terceiro é que a taxonomia de algoritmos é outro aspecto importante na aplicação de análise de dados inteligentes. As descobertas deste artigo facilitam a escolha de um algoritmo adequado para um problema específico. Os algoritmos analíticos caem em oito categorias, descritas em detalhes. Isto é seguido pela revisão de aplicação de casos de uso de cidades inteligentes. As características e as qualidades dos dados inteligentes são descritas em detalhes. Na seção de discussão, a maneira pela qual as características dos dados e as especificidades da aplicação podem levar à escolha de algoritmos de análise de dados adequados é revisada. Por fim, tendências futuras e o caminho futuro para pesquisas na área de análise inteligente de dados são discutidas.
 
# Comparação das técnicas

ETL (Extração, Transformação e Carga):
- No contexto do artigo, a ETL envolve a extração de dados provenientes de sensores IoT em uma cidade inteligente, seguida da transformação desses dados em formatos apropriados para análise.
- No projeto, o processo de ETL consiste na extração de dados do sistema Bleed dos motores de aeronaves (fornecidos pela própria companhia aérea AZUL), na sua subsequente transformação em informações úteis e na carga desses dados em um ambiente preparado para análise.

Análise de Dados:
- No artigo, a análise de dados compreende a aplicação de algoritmos de aprendizado de máquina com o objetivo de extrair insights e antecipar tendências com base nos dados das cidades inteligentes.
- No projeto, a análise de dados envolve a utilização de algoritmos de aprendizado de máquina para identificar padrões nos dados do sistema Bleed dos motores e antecipar possíveis falhas.

Objetivos de Predição:
- O artigo tem como meta a previsão de eventos ou padrões relacionados às cidades inteligentes, como previsões de tráfego ou análise do consumo de energia.
- No projeto, o principal objetivo é prever o momento em que ocorrerá uma falha no sistema Bleed dos motores da aeronave, baseando-se nos dados disponíveis.

Utilização de Algoritmos de Aprendizado de Máquina:
- No contexto do artigo, é abordada a aplicação de algoritmos de aprendizado de máquina em um contexto de IoT, voltada para a análise de dados.
- No projeto, também há a aplicação de algoritmos de aprendizado de máquina, porém direcionados especificamente para a previsão de falhas no sistema bleed de motores de aeronaves.

# Resenha crítica

O artigo intitulado "Machine learning for internet of things data analysis: a survey" oferece uma análise completa e informativa sobre a aplicação de técnicas de aprendizado de máquina na análise dos dados gerados pela Internet das Coisas (IoT). Este trabalho proporciona uma visão detalhada dos desafios e oportunidades relacionados ao processamento de grandes volumes de dados da IoT, bem como das diversas possibilidades de aplicação em setores como cidades inteligentes.

Aspectos Positivos:

Magnitude e Relevância: O artigo aborda um tema muito relevante na area da tecnologia, com a importância crescente do papel desempenhado pela IoT em diversas indústrias. A análise de dados da IoT é uma área em plena ascensão e expansão, e o artigo traz uma análise profunda do status atual das técnicas de aprendizado de máquina aplicadas a esse contexto.

Linguagem e Contextualização: O artigo é muito bem escrito e apresentado num contexto sólido e claro. Os conceitos fundamentais da IoT e do aprendizado de máquina é explicado de forma clara e detalhada, possibilitando o entendimento para um vasto grupo de leitores.

Análise Técnica: O artigo oferece uma análise técnica bem detalhada e sólida das características dos dados da IoT. Ao longo do texto várias categorias de algoritmos de aprendizado de máquina são exploradas e exemplificadas. O público-alvo mais técnico pode ampliar muito seu conhecimento a aprofundar a análise e compreensão das várias técnicas aplicadas e discutidas.

Aspectos Negativos:

Ausência de Exemplos Práticos: Embora o artigo apresente uma análise teórica sólida, ele deixa a desejar ao não incluir exemplos práticos de implementação. A inclusão de estudos de caso ou exemplos reais teria sido útil para ilustrar como as técnicas de aprendizado de máquina são aplicadas de forma concreta na análise de dados da IoT.
Limitação na Discussão de Desafios Éticos e de Privacidade: Dado o caráter intrusivo da coleta de dados da IoT, seria benéfico se o artigo tivesse explorado de forma mais ampla os desafios éticos e de privacidade associados. Isso teria enriquecido a discussão sobre o uso responsável dos dados da IoT.
Extensão Excessiva da Visão Geral: Apesar de ser abrangente, o artigo pode ser considerado demasiadamente longo para alguns leitores. Uma visão geral mais concisa poderia ter mantido o foco nos pontos-chave.

No nosso projeto foi testado em relação a parte de ETL até achar a melhor forma de concluir essa etapa, foi testado alguns algoritmos de aprendizado de maquina que utiliza o ETL, por exemplo, o modelo AutoML do pycaret, KNN e regressão linear, formas diferentes de analisar os dados brutos providenciados pela AZUL e o melhor jeito de fazer o output da predição 
