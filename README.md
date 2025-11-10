# Conhecimentos Técnicos Essenciais nas Vagas da Computação

Na computação, existem diversas áreas de atuação, como desenvolvimento de software e hardware, robótica, análise de dados, inteligência artificial, aprendizado de máquina e segurança. Além disso, inúmeras tecnologias frequentemente surgem e se popularizam no mercado de trabalho. Para poder se tornar um profissional qualificado, é importante conhecer as tecnologias mais relevantes.

Assim, o objetivo do projeto contido neste repositório é analisar quais são os conhecimentos técnicos mais presentes nas vagas de emprego na área da computação. Para esse fim, uma rede relacionando vagas de emprego aos seus requisitos técnicos foi construída a partir de vagas disponíveis online no Brasil. Cada vaga de emprego conta com um id, sua localização (região do país ou apenas "Brazil" caso não se saiba e ela seja remota) e se a vaga é remota ou não. Cada conhecimento técnico é caracterizado pelo seu nome.

O arquivo `job_skill_graph.gexf` representa a rede completa e os notebooks na raiz do repositório abrangem a coleta de dados, processamento dos dados originais, construção do grafo e análises. O arquivo `job_skill_graph_with_metrics.gexf` representa a rede completa, com atributos nos nós de conhecimentos técnicos representando as medidas de centralidade avaliadas.

Para algumas análises, subgrafos foram construídos a partir da rede completa, e eles estão disponíveis na pasta `subgraphs`. As pastas `gephi_plots` e `images` contêm imagens de visualizações dos grafos na ferramenta Gephi e gráficos construídos a partir dos grafos, respectivamente. A pasta `results` contém os valores das métricas avaliadas.
