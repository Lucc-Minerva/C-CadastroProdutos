# Cadastro de produtos

Seu programa dever� armazenar, para um produto, os seguintes dados:

- Nome do produto;
- Marca;
- Tamanho/quantidade (em gramas, ml, etc);
- Pre�o no estabelecimento 1;
- Pre�o no estabelecimento 2;
- Pre�o no estabelecimento 3;
- 
Por exemplo, considere como produto Arroz Branco, Tio Urbano, 5 Kg, cujo pre�o est� R$ 22,75 na Central de Alimentos, R$ 26,80 no Viver Bem Saud�vel, e R$ 16,99 no Semar Supermercados (dados de cunho ilustrativo, pre�os pesquisados na Internet em outubro/2022).

Depois que voc� pesquisar diversos produtos, seu programa deve indicar quais produtos est�o mais baratos em qual estabelecimento, fornecendo 3 listas (vetores), cada uma contendo os produtos mais baratos apenas naquele estabelecimento.

### Algumas dicas:

Escolha estabelecimentos de sua cidade ou da Internet.
Utilize ZERO ou R$-1 como pre�o para produtos que n�o forem encontrados.
Nomeie os estabelecimentos apenas uma vez, fora da lista. Pesquise apenas nos mesmos estabelecimentos.
Seu programa deve contemplar os seguintes itens:

Crie uma estrutura para armazenar os dados de um produto.
Crie um vetor, para ser poss�vel armazenar os dados de diversos produtos.
Popule os dados de suas vari�veis no vetor. Entrar com os dados de sua preferencia no programa faz parte da quest�o. Crie pelo menos 10 produtos.
Fa�a uma fun��o que decide qual � o menor pre�o de um produto.
No main, mostre os resultados chamando a fun��o criada para os dados que voc� cadastrou na lista/vetor.
Fa�a um menu com as seguintes op��es:

	[1] Inicializar os dados
	[2] Cadastrar um novo produto
	[3] Mostrar os produtos mais baratos � supermercado 1
	[4] Mostrar os produtos mais baratos � supermercado 2
	[5] Mostrar os produtos mais baratos � supermercado 3