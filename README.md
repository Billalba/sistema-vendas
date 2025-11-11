# Instalação Frontend
npm install

# Rodar
npm run dev

# Acesso
http://localhost:5173/

# Considerações
# Bibliotecas principais usadas
 - axios para fazer as requisições
 - vite para vsialização mais rápida do front
 - bootstrap para layout do front
 - react-icons para os icons do Navigation.tsx


 ##########################################################


# Instalção BANCO de DADOS phpmyadmin XAMPP PORT 3306
Agrupamento do banco
utf8mb4_general_ci

vendas-api >  database - importe o banco populado vendas_db_teste.sql dentro do phpmyadmin para aparecer com vendas realizadas de teste
OU
vendas-api >  database - importe o schema.sql e seeds.sql com apenas Clientes e Produtos

# Instalção API
npm install

# Roda API
npm run start 

# Considerações
 - express para facilitar a criação da conexão
 - mysql2 para conexões com MySql

# APIs
URL: http://localhost:3001
Produtos: http://localhost:3001/api/produtos
Clientes: http://localhost:3001/api/clientes
Vendas: http://localhost:3001/api/vendas
Dashboard: http://localhost:3001/api/dashboard
 
