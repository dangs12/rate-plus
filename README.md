# Proposta de Sistema Orientado a Objetos – Segunda Entrega 

# Sistema Rate+

## Introdução:

O sistema, chamado Rate+, visa centralizar e gerenciar informações de cadastro sobre pessoas físicas e jurídicas, incluindo professores, alunos e fornecedores. O trabalho inclui o diagrama de casos de uso, com descrição detalhada dos cenários para cada caso, é um diagrama de classes, que representa a estrutura do sistema e suas relações entre as classes. 

# Tecnologias Utilizadas:

## Front-end:

HTML: Estruturação do conteúdo web.

CSS: Estilização visual do site.

Vue.js: Framework JavaScript para criar interfaces interativas.

## Back-end:

JavaScript: Adicionar interatividade, pode ser utilizado no back-end para gerenciar dados e se comunicar com servidores.

Node.js: Plataforma JavaScript para desenvolvimento de aplicações web.

Banco de Dados:

SQL Server: Armazenamento de dados, incluindo informações dos usuários.

Editor de Código:

VS Code: Ferramenta de desenvolvimento com extensões para facilitar o trabalho.

# Funcionalidades:

**I. Cadastro de Usuários:**

* **Cadastro de Pessoa Física:** Permite o cadastro de usuários com informações pessoais (nome, CPF, data de nascimento, endereço, telefone e e-mail).
* **Cadastro de Pessoa Jurídica:**  Permite o cadastro de entidades com informações da empresa (nome, CNPJ, endereço, telefone e e-mail).
* **Cadastro de Professor:**  Permite o cadastro de professores com informações específicas, incluindo titulação, área de atuação, departamento e currículo (opção de upload de arquivo).
* **Validação de Dados:** Realiza validações em tempo real nos campos de entrada para garantir a consistência e a correção dos dados informados (ex: CPF, CNPJ, e-mail, datas).  As validações incluem a verificação de campos obrigatórios, formatos de dados (ex: CPF, CNPJ, data), e a existência de dados duplicados.
* **Armazenamento de Dados:** Armazena as informações dos usuários no banco de dados (SQL Server).  O sistema deve garantir a segurança dos dados armazenados.
* **Controle de Acesso:**  Garante que apenas os usuários autorizados possam acessar os dados.


**II. Autenticação:**

* **Login:** Permite ao usuário entrar no sistema utilizando nome de usuário e senha.  Inclua mecanismos de recuperação de senha.
* **Autenticação:** Utiliza um mecanismo de autenticação seguro (ex: hashing de senha) para garantir a segurança das credenciais do usuário.
* **Segurança:** Implementa medidas de segurança adequadas para proteger as informações dos usuários (criptografia de dados, proteção contra ataques de força bruta, etc.).

**III. Gestão de Dados:**

* **Alteração de Dados:**  Permite que os usuários alterem suas informações pessoais e de cadastro.
* **Visualização de Dados:** Exibe informações do usuário cadastrado de forma organizada, permitindo a visualização detalhada dos dados do cadastro.
* **Logout:** Permite ao usuário sair do sistema.


**IV. Gerenciamento de Dados (Administração):**

* Se houver um nível administrativo, poderá haver funcionalidades adicionais para gerenciar os usuários, como:
    * **Exclusão de Usuários:** Permitir que a administração exclua usuários do sistema.
    * **Pesquisa de Usuários:** Busca por usuários com base em critérios específicos (nome, CPF, etc).
    * **Gerenciamento de Permissões:**  Permitir que a administração configure diferentes níveis de acesso e permissões aos usuários.


**V. Integração e Restrições:**

* **Integração com outros sistemas:** Podem existir funcionalidades para integração com outros sistemas ou serviços.
* **Restrições de acesso:**  O acesso a determinadas funcionalidades pode ser restrito com base no tipo de usuário. Por exemplo, um usuário comum não pode alterar as informações de outro usuário.
* **Interface amigável:**  Uma interface de usuário intuitiva e amigável para facilitar o acesso e uso de todas as funcionalidades do sistema.

# Protótipo:

[Insira imagens do protótipo aqui]

# Como Executar:

1. **Usuário acessa o sistema:**  O processo inicia quando um usuário acessa a aplicação web.

2. **Login?**: Verifica se o usuário já está logado.

3. **Validação de credenciais:** Se o usuário está logado, verifica as credenciais (nome de usuário e senha) no banco de dados.

4. **Redirecionar para tela de login:** Se o usuário não está logado, redireciona para a tela de login.

5. **Exibe mensagem de erro:** Caso a validação de credenciais falhe, exibe uma mensagem de erro ao usuário.

6. **Carrega dados de perfil do usuário:** Após a autenticação bem-sucedida, carrega os dados do usuário no sistema e exibe a tela inicial.

7. **Tela inicial do sistema:**  A tela inicial exibe as funcionalidades do sistema, que podem incluir cadastro de dados, gestão de dados e logout.

8. **Tipo de usuário?**: O sistema pergunta ao usuário o seu tipo para direcioná-lo ao formulário correto de cadastro.

9. **Formulários de Cadastro (Pessoa Física, Pessoa Jurídica, Professor):** O sistema direciona o usuário para o formulário de cadastro específico do seu tipo de usuário.

10. **Salvar Dados:**  Os dados são enviados ao banco de dados.

11. **Redirecionar para tela inicial (O):** Após o cadastro, o usuário é redirecionado de volta à tela inicial.

12. **Gestão de Dados**:  O usuário logado pode realizar as operações de alteração, visualização e logout.

# Diagramas UML:

## Diagrama de Caso de Uso

![Arquivos do Projeto/Diagramas UML/Diagrama de Caso de Uso.jpg]()

## Diagrama de Classe

![Arquivos do Projeto/Diagramas UML/Diagrama de Classe.jpg](https://github.com/dangs12/rate-plus/blob/aac191a1cabd2f85c9c38ca4128e9e011904eac6/Arquivos%20do%20Projeto/Diagramas%20UML/Diagrama%20de%20Classe.jpg)

# Contribuições:

Contribuições são bem-vindas! Por favor, siga as diretrizes de contribuição [link para diretrizes].

# Licença:

LICENÇA DE USO DO SOFTWARE RATE+ 
