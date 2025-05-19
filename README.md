# criacao_BD_Azure
Criação de um Banco de Dados na Azure

A Microsoft Azure oferece diversos serviços de banco de dados em nuvem que permitem armazenar, gerenciar e acessar dados com segurança e escalabilidade. Um dos serviços mais comuns é o Azure SQL Database, um banco de dados relacional baseado na plataforma SQL Server, totalmente gerenciado pela Azure. Com ele, você não precisa se preocupar com infraestrutura, backups ou atualizações.

Passo a Passo para Criar um Banco de Dados no Azure SQL Database
Acesse o Portal da Azure

Vá para https://portal.azure.com e faça login com sua conta.

Crie um novo recurso

No menu lateral esquerdo, clique em "Criar um recurso".

Escolha "Banco de Dados" > "SQL Database".

Configure o banco de dados

Nome do banco de dados: Escolha um nome para o banco.

Assinatura e Grupo de recursos: Selecione uma assinatura e grupo de recursos existentes, ou crie um novo.

Servidor: Crie um novo servidor (definindo nome, login, senha e região) ou use um existente.

Escolha o plano de computação e armazenamento

Clique em "Configurar banco de dados" para definir desempenho, tamanho e modelo de compra (DTU ou vCore).

Defina regras de firewall

Após a criação, vá até o servidor SQL e configure as regras de firewall para permitir acesso ao banco (incluindo seu IP).

Criar banco de dados

Clique em "Revisar + Criar" e depois em "Criar". A Azure iniciará a implantação do recurso.

Conectar ao banco

Após a criação, vá até o recurso e clique em "Mostrar cadeia de conexão" para obter os dados de acesso e conectar-se via SQL Server Management Studio (SSMS), Azure Data Studio ou sua aplicação.

