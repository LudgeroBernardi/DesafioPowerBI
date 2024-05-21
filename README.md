# Desafio Processando e Transformando Dados com Power BI

# Passos realizados para conclusão do desafio

Criado um servidor do MySQL no Azure.
Criado uma database no MySQL denominada "Azure_Company", criado as tabelas e inserido os dados utilizando os scripts "script_bd_company.sql" e "insercao_de_dados_e_queries_sql.sql" fornecidos no desafio.
Para conectar no MySQl e executar os scripts foi utilizado o Bash do Azure.
Criado um relatório no Power BI denominado "Processando e Transformando Dados com Power BI", utilizando a database "Azure_Company" do servidor MySQL criado no Azure. 
Antes de inserir os dados no relatório do Power BI foi utilizado o PowerQuery para transformação dos dados conforme descrito abaixo.

Foi realizado a verificação de todos os cabeçalhos e tipos de dados.
Modificado os valores monetários para o tipo Numero Decimal Fixo.
Verificado a existência dos nulos e analisado a remoção.
Verificado se havia algum colaborador sem gerente.
Verificado se havia algum departamento sem gerente.
Verificado o número de horas dos projetos.
Separado as colunas complexas.
Mesclado as consultas employee e departament para criar uma tabela employee com o nome dos departamentos associados aos colaboradores. Usado como base a tabela employee e eliminado as colunas desnecessárias.
Realizado a junção dos colaboradores e respectivos nomes dos gerentes.
Mesclado as colunas de Nome e Sobrenome para ter apenas uma coluna definindo os nomes dos colaboradores.
Mesclado os nomes de departamentos e localização.
Foi utilizado o mesclar, porque utilizamos a opção de mesclar para combinar dados de tabelas diferentes com base em uma chave de correspondência.
Agrupado os dados a fim de saber quantos colaboradores existem por gerente.
Eliminado as colunas desnecessárias, que não serão usadas no relatório de cada tabela.
