# CADASTRO E LOGIN COM PHP
👨‍🏫FORMULARIO EM HTML, CSS, PHP E MYSQL.

<img src="FOTO.png" align="center" width="500"> <br>

## DESCRIÇÃO:
### INICIO:
Este é um exemplo simples de um sistema de cadastro e login em PHP que utiliza MySQL como banco de dados e a extensão PDO (PHP Data Objects) para interagir com o banco de dados. O sistema permite que os usuários se cadastrem com um email e senha, bem como façam login usando as credenciais cadastradas.

### ESTRUTURA DO PROJETO:
- `FORMULARIO.html`: Contém o formulário HTML com campos de email e senha.
- `FORMULARIO.php`: Lida com a lógica do cadastro e login dos usuários, incluindo a interação com o banco de dados.
- `FORMULARIO.css`: Arquivo CSS para estilizar o formulário.

### EXPLICAÇÃO DO CÓDIGO:
- O arquivo `FORMULARIO.php` é responsável pela lógica de cadastro e login dos usuários.
- O código PHP utiliza PDO para conectar-se ao banco de dados, coletar dados do formulário, inserir dados na tabela `clientes` e verificar as credenciais de login.
- O formulário HTML em `index.html` envia dados para o arquivo `FORMULARIO.php` usando o método POST.

### SEGURANÇA:
Este é um exemplo básico e não inclui todas as medidas de segurança necessárias para um ambiente de produção. Ao implementar um sistema de autenticação em um ambiente real, você deve considerar medidas adicionais de segurança, como:

- Validar e filtrar dados de entrada.
- Criptografar senhas usando funções de hash seguras, como `password_hash` e `password_verify`.
- Implementar proteção contra ataques de injeção de SQL.
- Usar sessões para gerenciar o estado de autenticação dos usuários.
- Implementar políticas de bloqueio de conta e recuperação de senha.
- Configurar HTTPS para proteger a transmissão de dados sensíveis.

## EXECUTANDO O PROJETO:
1. **Configuração do Banco de Dados:**
   - Antes de executar o site, é necessário importar o arquivo `DATABASE.sql`.

2. **Configuração do PHP:**
   - Abra o arquivo `FORMULARIO.php` e ajuste as configurações do banco de dados:

     ```php
     $servidor = "localhost";
     $username = "seu_usuario";
     $usersenha = "sua_senha";
     $database = "registro";
     ```

3. **Executando o Aplicativo com Apache:**
   - Coloque os arquivos em um servidor web compatível com PHP (por exemplo, XAMPP, WAMP, LAMP).
   - Acesse o formulário no navegador visitando [http://localhost/CODIGO/FORMULARIO.html](http://localhost/CODIGO/FORMULARIO.html).

4. **Executando o Aplicativo com `php.exe`:**
   - Alternativamente, você pode iniciar o servidor diretamente no diretório `./CODIGO` com o comando abaixo:
   ```bash
   php -S localhost:8080
   ```
   - Em seguida, acesse o formulário no navegador através do endereço: [http://localhost:8080/FORMULARIO.html](http://localhost:8080/FORMULARIO.html).

5. **Usando o Aplicativo:**
   - Use o formulário para se cadastrar com um email e senha ou fazer login com as credenciais cadastradas.

## NÃO SABE?
- Entendemos que para manipular arquivos em `HTML`, `CSS` e outras linguagens relacionadas, é necessário possuir conhecimento nessas áreas. Para auxiliar nesse aprendizado, oferecemos cursos gratuitos disponíveis:
* [CURSO DE HTML E CSS](https://github.com/VILHALVA/CURSO-DE-HTML-E-CSS)
* [CURSO DE PHP](https://github.com/VILHALVA/CURSO-DE-PHP)
* [CURSO DE MYSQL](https://github.com/VILHALVA/CURSO-DE-MYSQL)
* [CURSO DE PHP COM MYSQL](https://github.com/VILHALVA/CURSO-DE-PHP-COM-MYSQL)
* [CONFIRA MAIS CURSOS](https://github.com/VILHALVA?tab=repositories&q=+topic:CURSO)

## CREDITOS:
- [PROJETO CRIADO PELO VILHALVA](https://github.com/VILHALVA)




