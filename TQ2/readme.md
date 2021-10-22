## Como avaliar estratégias de day trading no mercado financeiro? - #2 TQ
O repositório em questão apresenta os arquivos utilizados no segundo vídeo da série Trading Quantitativo da Asimov Academy.

Neste segundo episódio da série Trading Quantitativo, nós apresentamos o passo a passo de como avaliar de maneira quantitativa uma estratégia de investimento. Como exemplo, utilizamos uma estratégia de day trading apresentada por um canal no YouTube.
Você vai aprender a representar essa estratégia com programação em Python, usando código para procurar por todas as ocorrências do padrão e verificar se ela realmente vale a pena.


### Descrição dos arquivos:
- 1. PPI-V.ipynb: Código fonte de todo o projeto desenvolvido no vídeo.
- ppvi.csv: Arquivo csv (que pode ser importado no Python) contendo informações sobre todos os momentos onde o padrão apresentado ocorreu, bem como o retorno de cada um deles.
- win_1min.parquet: Arquivo do tipo .parquet (requer instalação do pyarrow, usando 'pip install pyarrow') com os dados usados neste projeto. Todos foram obtidos no MetaTrader 5.
