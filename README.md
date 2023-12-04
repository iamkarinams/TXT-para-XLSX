# Convertendo TXT para XLSX

<img align="center" alt="Ka-Python" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg"> <img align="center" alt="Ka-pycharm" height="30" width="120" src="https://img.shields.io/badge/PyCharm-000000.svg?&style=for-the-badge&logo=PyCharm&logoColor=white">

#
O código faz o seguinte:
1. Localiza todos os arquivos TXT na pasta "Enviados".
2. Para cada arquivo TXT:
3. Extrai o nome do arquivo sem a extensão.
4. Lê o arquivo TXT e cria um DataFrame com os dados.
5. Remove linhas vazias do DataFrame.
6. Cria uma planilha no Excel com o mesmo nome do arquivo TXT original.
7. Move o arquivo TXT para a pasta "Processados".


Mais especificamente, as etapas do código são as seguintes:

  Linha 3: Define as pastas "Enviados", "Processados" e "TXT-XLSX".
  
  Linha 5: Usa a função os.listdir() para listar todos os arquivos na pasta "Enviados".
  
  Linha 7: Verifica se há arquivos TXT na pasta "Enviados". Se não houver, o código é encerrado.
  
  Linha 9: Define o nome do arquivo TXT a ser processado.
  
  Linha 11: Abre o arquivo TXT em modo de leitura.
  
  Linha 13: Usa um loop para encontrar a linha que contém a marcação "LIQUIDACOES".
  
  Linha 17: Se a linha não for encontrada, o código é encerrado.
  
  Linha 19: Volta para o início do arquivo para ler a partir da linha desejada.
  
  Linha 21: Ignora as linhas até a linha desejada.
  
  Linha 23: Lê as linhas restantes do arquivo.
  
  Linha 25: Extrai os dados de cada coluna conforme as especificações.
  
  Linha 29: Cria um DataFrame com os dados extraídos.
  
  Linha 31: Remove linhas vazias do DataFrame.
  
  Linha 33: Cria uma planilha no Excel com o mesmo nome do arquivo TXT original.
  
  Linha 35: Move o arquivo TXT para a pasta "Processados".
  
  Linha 37: Imprime uma mensagem de sucesso.
  
Para que o código funcione corretamente, é necessário que os arquivos TXT estejam na pasta "Enviados" e sigam o formato especificado.
