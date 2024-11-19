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

* **Login:** Permite ao usuário entrar no sistema utilizando CPF, CNPJ, E-mail e senha.  Inclua mecanismos de recuperação de senha.
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

![Arquivos do Projeto/Imagens do Protótipo/Protótipo Rate +/1. Tela de Login.jpg](https://github.com/dangs12/rate-plus/blob/c76ee9748719ce71e6149f0a41986eeed1fc3ee2/Arquivos%20do%20Projeto/Imagens%20do%20Prot%C3%B3tipo/Prot%C3%B3tipo%20Rate%20%2B/1.%20Tela%20de%20Login.jpg)
![Arquivos do Projeto/Imagens do Protótipo/Protótipo Rate +/2. Tela Inicial (após login).jpg](https://github.com/dangs12/rate-plus/blob/c76ee9748719ce71e6149f0a41986eeed1fc3ee2/Arquivos%20do%20Projeto/Imagens%20do%20Prot%C3%B3tipo/Prot%C3%B3tipo%20Rate%20%2B/2.%20Tela%20Inicial%20(ap%C3%B3s%20login).jpg)
![Arquivos do Projeto/Imagens do Protótipo/Protótipo Rate +/3. Formulários de Cadastro.jpg](https://github.com/dangs12/rate-plus/blob/c76ee9748719ce71e6149f0a41986eeed1fc3ee2/Arquivos%20do%20Projeto/Imagens%20do%20Prot%C3%B3tipo/Prot%C3%B3tipo%20Rate%20%2B/3.%20Formul%C3%A1rios%20de%20Cadastro.jpg)
![Arquivos do Projeto/Imagens do Protótipo/Protótipo Rate +/4. Cadastro de Pessoa Física.jpg](https://github.com/dangs12/rate-plus/blob/c76ee9748719ce71e6149f0a41986eeed1fc3ee2/Arquivos%20do%20Projeto/Imagens%20do%20Prot%C3%B3tipo/Prot%C3%B3tipo%20Rate%20%2B/4.%20Cadastro%20de%20Pessoa%20F%C3%ADsica.jpg)
![Arquivos do Projeto/Imagens do Protótipo/Protótipo Rate +/5. Cadastro de Pessoa Jurídica.jpg](https://github.com/dangs12/rate-plus/blob/c76ee9748719ce71e6149f0a41986eeed1fc3ee2/Arquivos%20do%20Projeto/Imagens%20do%20Prot%C3%B3tipo/Prot%C3%B3tipo%20Rate%20%2B/5.%20Cadastro%20de%20Pessoa%20Jur%C3%ADdica.jpg)
![Arquivos do Projeto/Imagens do Protótipo/Protótipo Rate +/6. Cadastro de Professor.jpg](https://github.com/dangs12/rate-plus/blob/c76ee9748719ce71e6149f0a41986eeed1fc3ee2/Arquivos%20do%20Projeto/Imagens%20do%20Prot%C3%B3tipo/Prot%C3%B3tipo%20Rate%20%2B/6.%20Cadastro%20de%20Professor.jpg)
![Arquivos do Projeto/Imagens do Protótipo/Protótipo Rate +/7. Cadastro de Fornecedor.jpg](https://github.com/dangs12/rate-plus/blob/c76ee9748719ce71e6149f0a41986eeed1fc3ee2/Arquivos%20do%20Projeto/Imagens%20do%20Prot%C3%B3tipo/Prot%C3%B3tipo%20Rate%20%2B/7.%20Cadastro%20de%20Fornecedor.jpg)
![Arquivos do Projeto/Imagens do Protótipo/Protótipo Rate +/8.Cadastro de Aluno.jpg](https://github.com/dangs12/rate-plus/blob/c76ee9748719ce71e6149f0a41986eeed1fc3ee2/Arquivos%20do%20Projeto/Imagens%20do%20Prot%C3%B3tipo/Prot%C3%B3tipo%20Rate%20%2B/8.Cadastro%20de%20Aluno.jpg)
![Arquivos do Projeto/Imagens do Protótipo/Protótipo Rate +/9. Conclusão de Cadastro.jpg](https://github.com/dangs12/rate-plus/blob/c76ee9748719ce71e6149f0a41986eeed1fc3ee2/Arquivos%20do%20Projeto/Imagens%20do%20Prot%C3%B3tipo/Prot%C3%B3tipo%20Rate%20%2B/9.%20Conclus%C3%A3o%20de%20Cadastro.jpg)

# Como Executar:

1. **Usuário acessa o sistema:**  O processo inicia quando um usuário acessa a aplicação web.

2. **Login?**: Verifica se o usuário já está logado.

3. **Validação de credenciais:** Se o usuário está logado, verifica as credenciais (CPF, CNPJ, E-mail e senha) no banco de dados.

4. **Redirecionar para tela de login:** Se o usuário não está logado, redireciona para a tela de login.

5. **Exibe mensagem de erro:** Caso a validação de credenciais falhe, exibe uma mensagem de erro ao usuário.

6. **Carrega dados de perfil do usuário:** Após a autenticação bem-sucedida, carrega os dados do usuário no sistema e exibe a tela inicial.

7. **Tela inicial do sistema:**  A tela inicial exibe as funcionalidades do sistema, que podem incluir cadastro de dados, gestão de dados e logout.

8. **Tipo de usuário?**: O sistema pergunta ao usuário o seu tipo para direcioná-lo ao formulário correto de cadastro.

9. **Formulários de Cadastro (Pessoa Física, Pessoa Jurídica, Professor, Aluno e Fornecedor):** O sistema direciona o usuário para o formulário de cadastro específico do seu tipo de usuário.

10. **Salvar Dados:**  Os dados são enviados ao banco de dados.

11. **Redirecionar para tela inicial (O):** Após o cadastro, o usuário é redirecionado de volta à tela inicial.

12. **Gestão de Dados**:  O usuário logado pode realizar as operações de alteração, visualização e logout.

# Diagramas UML:

## Diagrama de Caso de Uso

![Arquivos do Projeto/Diagramas UML/Diagrama de Caso de Uso.jpg](https://github.com/dangs12/rate-plus/blob/cd14e79e1aa87f6f3a3fb4e2921b52575d933a8d/Arquivos%20do%20Projeto/Diagramas%20UML/Diagrama%20de%20Caso%20de%20Uso.jpg)

## Diagrama de Classe

![Arquivos do Projeto/Diagramas UML/Diagrama de Classe.jpg](https://github.com/dangs12/rate-plus/blob/aac191a1cabd2f85c9c38ca4128e9e011904eac6/Arquivos%20do%20Projeto/Diagramas%20UML/Diagrama%20de%20Classe.jpg)

# Contribuições:

Contribuições são bem-vindas! Por favor, siga as diretrizes de contribuição ![[link para diretrizes]](https://github.com/dangs12/rate-plus/blob/e08c7a672948ce3e857241b4711104569434b40a/Arquivos%20do%20Projeto/Info/Contribui%C3%A7%C3%B5es%20do%20Projeto%20Rate%2B).

# Licença:

![Licença de Uso do Sistema Rate+ - 2024](https://github.com/dangs12/rate-plus/blob/41f509c2fd9aff0915c044b9c5cd6b78e47154e5/Arquivos%20do%20Projeto/Info/Licen%C3%A7a%20de%20Uso%20do%20Sistema%20Rate%2B%20-%202024)
