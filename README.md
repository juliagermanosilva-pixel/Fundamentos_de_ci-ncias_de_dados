Web Scraping de Notícias do G1 e Visualização de Dados
Este projeto demonstra a coleta de notícias do portal G1 utilizando web scraping e a visualização de dados com matplotlib.

Funcionalidades
Coleta de Notícias: Extrai títulos, links e datas de notícias do portal G1 (globo.com).
Processamento de Dados: Utiliza a biblioteca pandas para estruturar os dados coletados.
Visualização de Dados: Apresenta um exemplo de gráfico utilizando matplotlib.
Bibliotecas Utilizadas
As seguintes bibliotecas Python são necessárias para executar este projeto:

requests: Para fazer requisições HTTP e obter o conteúdo das páginas web.
BeautifulSoup (bs4): Para fazer o parse do HTML e extrair os dados desejados.
pandas: Para manipulação e análise de dados (estruturação das notícias).
datetime: Para lidar com datas e horários.
matplotlib.pyplot: Para a criação de gráficos e visualizações de dados.
Como Executar
Instale as Dependências: Certifique-se de ter as bibliotecas necessárias instaladas. Se não as tiver, pode instalá-las usando pip:

pip install requests beautifulsoup4 pandas matplotlib
Execute o Notebook: Abra o arquivo .ipynb (se estiver no Google Colab ou Jupyter Notebook) e execute as células na ordem.

A primeira célula importa as bibliotecas necessárias.
A segunda célula define a função coletar_noticias_g1() que realiza o web scraping.
A terceira célula chama a função e exibe as 10 primeiras notícias coletadas.
As células subsequentes mostram um exemplo de como criar um gráfico com matplotlib.# Fundamentos_de_ci-ncias_de_dados
