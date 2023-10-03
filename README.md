# Ponderada_Programação-Semana-9

Um dos principais problemas encarados pelos sistemas conversacionais é o fato dos modelos não serem atualizados ao longo do tempo. Conforme os novos dados são gerados e o ambiente em que o sistema opera se transforma, ocorre um fenômeno conhecido como concept drift, que é a mudança gradual nas distribuições dos dados de entrada ao longo do tempo. Como consequência disso, respostas imprecisas ou desatualizadas do sistema podem ocorrer, comprometendo a qualidade da interação com os usuários.

<img src='https://imgur.com/nch3fET.png'/>

Descrição do diagrama de blocos:

Coletor de Dados: É responsável por reunir informações das interações passadas do sistema de conversação, incluindo conversas, feedback dos usuários e outras informações relevantes. Esses dados são muito importantes para o treinamento e atualização do modelo.

Pré-processamento: Os dados coletados passam por um processo de reorganização e preparação. Isso pode envolver a limpeza dos dados, a remoção de informações confidenciais e a transformação dos dados em um formato adequado para o treinamento.

Treinamento do Modelo: O modelo inicial do sistema de conversação é aprimorado usando os dados pré-processados. Assim, são aplicados algoritmos de aprendizado de máquina para ajustar as configurações do modelo com base nas informações disponíveis.

Atualização do Modelo: Quando os novos dados são obtidos, é necessário manter a atualização do modelo para acompanhar as mudanças no contexto. Dessa forma, os novos dados são incorporados aos dados de treinamento existentes e o modelo é recalibrado para refletir as informações mais recentes.

Sistema de Conversação: O modelo atualizado é implantado no sistema de conversação, permitindo que os usuários interajam com ele. O sistema utiliza o modelo para criar respostas pertinentes e atualizadas com base nas entradas dos usuários.


A proposta de fomentar o aprendizado contínuo no sistema conversacional é um passo muito importante para tentar resolver o problema de falta de atualização dos modelos. Ao fazer a coleta de dados, pré-processamento, treinamento e atualização do modelo, é possível manter a relevância e a precisão das respostas fornecidas pelo sistema. Porém, é importante ressaltar que a implementação dessa proposta requer a criação de infraestrutura para coleta e armazenamento de dados, desenvolvimento de algoritmos de aprendizado de máquina e a integração do modelo atualizado ao sistema conversacional. Apesar dos desafios, o investimento nesse tipo de abordagem pode melhorar significativamente a experiência do usuário e a eficácia do sistema conversacional ao longo do tempo.

REFERÊNCIAS BIBLIOGRÁFICAS:

JANG, Joel. Towards continual knowledge learning of language models. 2022. Disponível em: <https://arxiv.org/pdf/2110.03215.pdf>.

WANG, Shenghui. Concept drift and how to identify it. 2011. Disponível em: <https://www.sciencedirect.com/science/article/abs/pii/S1570826811000254>.

GONÇALVES JR., Paulo M. A comparative study on concept drift detectors. 2014. Disponível em: <https://www.sciencedirect.com/science/article/abs/pii/S0957417414004175>.

BAYRAM, Firas. From concept drift to model degradation: An overview on performance-aware drift detectors. 2022. Disponível em: <https://www.sciencedirect.com/science/article/pii/S0950705122002854>.
