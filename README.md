# Desafio-RESTIC-em-dupla---kNN-main
 Objetivo: Implementar e avaliar o desempenho do algoritmo k-Nearest Neighbors (kNN) em um conjunto de dados real, documentando todo o processo em um relatório técnico.

# Autores
Vitor Miranda e Wallisson Dias.

# Descrição do projeto
O projeto traz uma modelagem do score de influência dos usuários do instagram com mais seguidores em uma época passada. A previsão de score pode ajudar empresas a escolher influenciadores para investir em publicidade.

# Instalação das bibliotecas necessárias
!pip install pandas
!pip install numpy
!pip install matplotlib
!pip install seaborn
!pip install scikit-learn
!pip install imbalanced-learn
!pip install scikit-optimize

# Estrutura dos arquivos
As bases .csv estão sendo puxadas publicamente do Google Sheets, mas serão deixadas também nesse repositório A pasta /src contém o código-fonte, /csv contém as bases de dados, enquanto /docs contém o relatório

# Sobre a base de dados
No arquivo, basicamente, há 10 atributos. Ele está ordenado com base no rank, que foi decidido com base nos "followers".

rank: Classificação do Influenciador com base no número de seguidores que ele possui.
- channel_info: Nome de usuário do Instagrammer.
- influence score: Pontuação de influência dos usuários. É calculada com base em menções, importância e popularidade.
- posts: Número de postagens feitas até agora.
- followers: Número de seguidores do usuário.
- avg_likes: Média de curtidas nas postagens do Instagrammer (total de curtidas/total de postagens).
- 60_day_eng_rate: Taxa de engajamento dos últimos 60 dias do Instagrammer como uma fração dos engajamentos realizados até agora.
- new_post_avg_like: Média de curtidas em novas postagens.
- total Likes: Total de curtidas que o usuário recebeu em suas postagens (em bilhões).
- country: País ou região de origem do usuário.
