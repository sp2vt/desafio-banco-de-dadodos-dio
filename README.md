criação do banco
criar banco de dados se não existir vendas

conjunto de caracteres padrão=utf8

agrupamento padrão=utf8-general-ci

*usar o banco
usar vendas

*criação  de tabelas
criar tabela se não existir clientes

id smallint (9) auto-increment não chave

nome varchar (30) não nulo

sobrenome varchar (40)

cpf int(15) não nulo

telefone int (15) não nulo

 cidade varchar (30)
 
 
