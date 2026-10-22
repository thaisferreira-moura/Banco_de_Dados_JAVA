PROJETO 05 - Sistema CRUD de Cadastro de Usuários (Android SQLite em Java)

Projeto desenvolvido como parte da disciplina de Programação para Dispositivos Móveis, focado na criação de uma aplicação móvel completa no Android Studio utilizando Java e o banco de dados nativo SQLite.

📱 Sobre o Projeto

A aplicação consiste num sistema de cadastro de usuários com suporte a todas as operações essenciais de um CRUD (Create, Read, Update, Delete):

Cadastrar (Gravar): Regista um novo usuário com Nome e Idade no banco de dados SQLite.

Consultar: Busca um usuário existente pelo Nome e exibe a sua Idade na interface.

Atualizar: Permite alterar a Idade de um usuário previamente cadastrado.

Deletar: Remove o registo do usuário do banco de dados a partir do Nome.

🛠️ Tecnologias Utilizadas

Linguagem: Java

Banco de Dados: SQLite (SQLiteOpenHelper)

Interface de Usuário: XML / Material Design (TextInputLayout, TextInputEditText, Button)

IDE: Android Studio

📂 Estrutura de Arquivos

app/src/main/res/layout/activity_main.xml: Define a interface visual com os campos de entrada, texto de resultado e os 4 botões de ação do CRUD.

app/src/main/java/com/example/projetocrud/BancoHelper.java: Classe em Java responsável pela criação e gestão do banco de dados usuarios.db e execução das queries (inserção, busca, alteração e exclusão).

app/src/main/java/com/example/projetocrud/MainActivity.java: Controla a lógica de apresentação, capturando os cliques nos botões e interagindo com a classe BancoHelper.

🚀 Como Executar o Projeto

Clone este repositório para a sua máquina local:

git clone https://github.com/thaisferreira-moura/Banco_de_Dados_JAVA.git

Abra o Android Studio.

Selecione File > Open... e escolha a pasta do projeto clonado.

Aguarde a sincronização automática do Gradle (Gradle Sync).

Certifique-se de que a declaração do pacote (package com.example.projetocrud;) no topo dos arquivos Java corresponde à estrutura do seu projeto.

Ligue um emulador Android ou um dispositivo físico via USB com a Depuração USB ativada.

Clique no botão Run (▶️) ou utilize o atalho Shift + F10.
