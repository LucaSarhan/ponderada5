# Sumário do artigo
O artigo "Machine learning for internet of things data analysis: a survey" aborda, em suma, a utilização de dados abertos para a aplicação de cidades inteligentes.

Introdução

Existem muitos conjuntos de dados abertos para aplicações de cidades inteligentes que são facilmente acessíveis aos investigadores. Além disso, um algoritmo Support Vector Machine é implementado nos dados de tráfego inteligentes da cidade de Aarhus para prever as horas de trânsito durante um dia. Ao responder às perguntas acima sobre dados inteligentes de IoT e algoritmos de aprendizado de máquina, seríamos capazes de escolher o melhor algoritmo de aprendizado de máquina que pode lidar com as características de dados inteligentes de IoT. Ao contrário de pesquisas semelhantes sobre aprendizado de máquina e IoT, os leitores deste artigo seriam capazes de obter uma compreensão profunda e técnica de algoritmos de aprendizado de máquina, aplicativos de IoT e características de dados de IoT, juntamente com implementações técnicas e simples.

Organização

A qualidade dos dados, geração de big data, integração de dados de sensores e anotação de dados semânticos são revisados ​​na Seção 4. Algoritmos de aprendizado de máquina em oito categorias com base em estudos recentes sobre dados de IoT e frequência de algoritmos de aprendizado de máquina são revisados ​​e resumidos na Seção 5. A correspondência dos algoritmos com aplicações específicas de cidades inteligentes é realizada na Seção 6, e a conclusão, juntamente com tendências futuras de pesquisa e questões em aberto, são apresentadas na Seção 7, Fig.

Internet das Coisas

O objetivo da Internet das Coisas é o monitoramento do sistema. Os avanços mais recentes feitos na IoT começaram quando as etiquetas RFID foram colocadas em uso com mais frequência, sensores de baixo custo tornaram-se mais disponíveis, a tecnologia web foi desenvolvida e os protocolos de comunicação foram alterados. Este tipo de comunicação é aplicado principalmente ao processamento em nuvem. Servidor para servidor armazenando dados locais para uso local.

Computação em nuvem

Esta arquitetura possui alta latência e alto balanceamento de carga, indicando que esta arquitetura não é suficiente para processar dados de IoT porque a maior parte do processamento deve ser executada em altas velocidades. O volume desses dados é alto e o processamento de big data aumentará o uso da CPU dos servidores em nuvem. Neste modelo, todo o software prático será hospedado por um provedor de serviços e estará acessível aos usuários através da Internet. Este serviço cloud se beneficia de uma interface de programação de aplicações e kits de desenvolvimento de software e capacidade de processar um maior volume de dados.

Como a cidade inteligente é uma das principais aplicações da IoT, os casos de uso mais importantes da cidade inteligente e suas características de dados são discutidos nas seções a seguir.

Cidade inteligente

Com o aumento da população e a complexidade das infra-estruturas urbanas, as cidades procuram métodos para lidar com problemas de urbanização em grande escala. A IoT desempenha um papel vital na coleta de dados do ambiente da cidade. O objetivo da construção de cidades inteligentes é melhorar serviços como gestão de tráfego, gestão de água e consumo de energia, bem como melhorar a qualidade de vida dos cidadãos.

Mobilidade inteligente

Através da IoT, as autoridades municipais podem melhorar a qualidade de vida na cidade. Com os dados coletados dos veículos, as rotas mais populares/congestionadas podem ser previstas e podem ser tomadas decisões para diminuir o congestionamento do tráfego. Os carros autônomos podem melhorar a segurança dos passageiros porque têm a capacidade de monitorar a direção dos outros carros. Existem diferentes perspectivas sobre como construir sistemas inteligentes de transporte público.

Esses sistemas precisam gerenciar diferentes tipos de dados, como dados de localização de veículos e dados de tráfego. Os sistemas inteligentes de transporte público devem ser orientados para o tempo real, a fim de tomar decisões adequadas em tempo real, bem como utilizar a análise de dados históricos. Por exemplo, foi proposto um mecanismo que considera dispositivos de cidades inteligentes como graph nodes, e os autores usaram soluções de big data para resolver esses problemas.

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




