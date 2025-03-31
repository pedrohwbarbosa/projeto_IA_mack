Database Spotify
Itegrantes: Isabella Abreu Comelli - 10400807, Pedro Henrique Wege Barbosa - 10400851
Link do Colab:

https://colab.research.google.com/drive/1rr6noxzXdB7f6xwbzzrvlD5WYVw7TArR?usp=sharing

Arquivos disponíveis em:

https://drive.google.com/drive/folders/1St9-2VWKUYEUl1uBNAFSOhRMD8C9zXLp?usp=sharing

Link para a criação das client keys para se conectar à API do Spotify (é necessário ter uma conta na plataforma):

https://developer.spotify.com/dashboard/create

Dataset Utilizado

Os dados foram coletados a partir da API pública do Spotify e estruturados em dois dataframes principais:

df_tracks: Contém informações gerais sobre as músicas, incluindo ID da faixa, nome, popularidade, duração, explicit content, gênero principal, múltiplos gêneros, além de detalhes do artista e do álbum, como nome, tipo, data de lançamento e número total de faixas.

df_audio_features: Inclui características de áudio de cada faixa, como dançabilidade, energia, tom, volume, modo musical, presença de discurso, acústica, instrumentalidade, vivacidade, valência, tempo e assinatura de tempo.

Os dados são completos, com poucas ocorrências de valores ausentes, geralmente em colunas relacionadas ao álbum. Foi realizada uma etapa de pré-processamento para remoção de duplicatas, tratamento de valores ausentes e conversão de colunas categóricas e numéricas para otimizar o desempenho dos modelos de machine learning.
