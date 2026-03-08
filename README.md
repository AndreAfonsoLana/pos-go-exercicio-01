Visual code
git clone https://github.com/AndreAfonsoLana/pos-go-exercisio-01

Acesse: 
cd .\pos-go-exercicio-01\se1. Clonar o Repositório
Abra o terminal ou o VS Code e execute:

Bash
git clone https://github.com/AndreAfonsoLana/pos-go-exercisio-01
2. Executar o Servidor (Server)
Acesse a pasta do servidor:

Bash
cd .\pos-go-exercicio-01\server\cmd\server\
Inicie a API com o comando:

Bash
go run main.go
O banco de dados SQLite (cotacoes.db) será gerado automaticamente nesta mesma pasta.

3. Executar o Cliente (Client)
Abra um novo terminal e acesse a pasta do cliente:

Bash
cd .\pos-go-exercicio-01\client\cmd\client\
Inicie o cliente com o comando:

Bash
go run main.go
O arquivo cotacao.txt será gerado nesta pasta contendo o valor atual da cotação.rver\cmd\server\

Execute a API server o comando:
go run main.go

Em outro prompt Acesse:
cd .\pos-go-exercicio-01\client\cmd\client\
Execute o Client o comando :
go run main.go
Vai gerar o arquivo cotacao.txt com a cotação e dentro do \pos-go-exercicio-01\server\cmd\server\ terá o banco de dados sqlite com o cotacao.db
