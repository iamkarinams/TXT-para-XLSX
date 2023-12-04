# Convertendo TXT para XLSX

<img align="center" alt="Ka-Python" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg"> <img align="center" alt="Ka-pycharm" height="30" width="120" src="https://img.shields.io/badge/PyCharm-000000.svg?&style=for-the-badge&logo=PyCharm&logoColor=white">

#
O código faz o seguinte:

Lista todos os arquivos TXT na pasta "Enviados".


Para cada arquivo TXT:

1. Extrai o nome do arquivo sem a extensão.
2. Lê o arquivo TXT e cria um DataFrame com os dados.
3. Remove linhas vazias do DataFrame.
4. Cria uma planilha no Excel com o mesmo nome do arquivo TXT original.
5. Move o arquivo TXT para a pasta "Processados".

   
Mais especificamente, as etapas da função são as seguintes:

Linha 3: Define os parâmetros da função processar_arquivos_txt().

Linha 5: Usa a função os.listdir() para listar todos os arquivos na pasta "Enviados".

Linha 7: Itera sobre a lista de arquivos TXT.

Linha 9: Extrai o nome do arquivo sem a extensão.

Linha 11: Abre o arquivo TXT em modo de leitura.

Linha 13: Lê o arquivo TXT e cria um DataFrame com os dados.

Linha 15: Remove linhas vazias do DataFrame.

Linha 17: Cria uma planilha no Excel com o mesmo nome do arquivo TXT original.

Linha 19: Move o arquivo TXT para a pasta "Processados".

A função processar_arquivos_txt() pode ser usada para processar arquivos TXT com formatos diferentes. Para isso, basta alterar a lista de colunas do DataFrame.

Por exemplo, para processar arquivos TXT com o formato especificado no código original, a lista de colunas seria a seguinte:

colunas = ["Pagador", "SEU NUMERO", "NOSSO NUMERO", "VENCTO", "DT PGT", "VALOR TITULO", "JUROS", "ABAT/DESC", "VALOR PAGO", "TARIFAS", "EVENTO"]


Se os arquivos TXT tiverem um formato diferente, as colunas do DataFrame devem ser definidas de acordo com o formato dos arquivos.
