# Formularios

Um formulario de cadastro de usuários.

A tag **input** “monta” uma caixinha (para escrever algo) é possível adicionar uma “variável”, dentro de input, escrevendo ```“<input name=”usuario”>```. feito isso, colocamos um comando para ler essas variáveis em label, por exemplo ```<label for=”usuario”>```. 
Também podemos adicionar o ```id=”senha”```, esse comando faz com que, quando o usuário cliquei em cima de **“senha”**, o cursor dele vai direto para a caixa de digitação. por exemplo ```<input name=”senha” id=”senha”>```. Para que não mostre a senha que está digitada, eu adiciono, dentro do input ```type=”password”```, ficaria: ```<input name=”senha” id=”senha” type=”password”>```. 
Para adicionar um limite de caracteres a ser digitado, eu uso o ```maxlength=”qtd caracteres"```. esse comando será digitado dentro de input. 
Para diminuir o tamanho da caixa onde o usuário irá escrever, é só adicionar, dentro de input o  ```size=”10”```.
Para deixar mostrando uma palavra dentro da caixa onde o usuário vai digitar o email, eu adiciono dentro de input, ``` placeholder=”nome do usuário ou e-mail”```.
