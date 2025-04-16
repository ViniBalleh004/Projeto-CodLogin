# PROJETO CODLOGIN

## Descrição
O **PROJETO CODLOGIN** é uma aplicação web simples que implementa um sistema de login e cadastro de usuários. Ele utiliza HTML, CSS e JavaScript para criar uma interface funcional e interativa. O projeto é dividido em duas páginas principais: uma tela de login e uma tela de cadastro.

## Estrutura do Projeto
O projeto é composto pelos seguintes arquivos:

### 1. `index.html`
- Página inicial do projeto, que contém o formulário de login.
- Inclui campos para o usuário inserir seu email e senha.
- Possui um botão "Entrar" que, ao ser clicado, redireciona o usuário para a página de cadastro (`cadastro.html`) caso os campos estejam preenchidos.

### 2. `cadastro.html`
- Página de cadastro de usuários.
- Contém um campo para inserir o nome do usuário e um botão "Salvar".
- Exibe uma tabela que lista os nomes cadastrados.
- Permite editar ou excluir os nomes da lista.

### 3. `signin.css`
- Arquivo de estilos CSS personalizado para a página de login.
- Define o layout responsivo e estiliza os elementos do formulário de login.
- Utiliza classes do Bootstrap para facilitar o design.

### 4. `main.js`
- Arquivo JavaScript que implementa a lógica do sistema.
- **Funções principais:**
  - `acessar()`: Verifica se os campos de login estão preenchidos e redireciona para a página de cadastro.
  - `salvarUser()`: Adiciona um nome à lista de usuários cadastrados.
  - `criaLista()`: Atualiza a tabela de usuários cadastrados.
  - `excluir(i)`: Remove um nome da lista de usuários.
  - `editar(i)`: Permite editar um nome já cadastrado.

## Funcionalidades
1. **Tela de Login (`index.html`):**
   - Formulário com campos de email e senha.
   - Validação para garantir que os campos sejam preenchidos.
   - Redirecionamento para a página de cadastro ao clicar no botão "Entrar".

2. **Tela de Cadastro (`cadastro.html`):**
   - Campo para inserir o nome do usuário.
   - Botão "Salvar" que adiciona o nome à lista.
   - Tabela que exibe os nomes cadastrados.
   - Botões para editar ou excluir nomes da lista.

3. **Estilização (`signin.css`):**
   - Layout responsivo e estilizado para a tela de login.
   - Integração com o framework Bootstrap para facilitar o design.

4. **Interatividade (`main.js`):**
   - Validação de campos.
   - Manipulação dinâmica da tabela de usuários.
   - Funções para adicionar, editar e excluir usuários.

## Tecnologias Utilizadas
- **HTML5**: Estrutura das páginas.
- **CSS3**: Estilização das páginas.
- **Bootstrap**: Framework CSS para design responsivo.
- **JavaScript**: Lógica e interatividade.

## Como Executar
1. Certifique-se de que todos os arquivos estão na mesma pasta.
2. Abra o arquivo `index.html` em um navegador web.
3. Utilize o formulário de login para acessar a página de cadastro.
4. Na página de cadastro, insira nomes e interaja com a tabela.

## Observações
- Este projeto é um exemplo básico de um sistema de login e cadastro, ideal para aprendizado e demonstração de conceitos fundamentais de desenvolvimento web.
- Não há integração com banco de dados ou backend; os dados são manipulados apenas no lado do cliente.

## Melhorias Futuras
- Implementar validação mais robusta para os campos de entrada.
- Adicionar persistência de dados utilizando localStorage ou um banco de dados.
- Criar um backend para autenticação e gerenciamento de usuários.
- Melhorar a segurança, como criptografia de senhas.

---