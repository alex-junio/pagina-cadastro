# página de cadastro simples
Desafio técnico proposto pela Gama Academy

## Projeto a ser desenvolvido
Página de cadastro simples, utilizando html, javascript e CSS

## Estrutura do projeto
A página irá conter os seguintes campos de preenchimento obrigatório:
* Nome
* CPF
* Campos referentes ao endereço, com exceção do complemento, que será opcional
* Celular

Os demais campos (RG, Sexo, Complemento, E-mail e Telefone residencial) são opcionais

### Desenvolvimento
A página é desenvolvida em HTML, contando com recursos de CSS para aplicar alguns estilos e formatações.
Além disso, são utilizados alguns códigos em javascript para realizar validação e/ou aplicar máscaras em alguns campos, como por exemplo o formato xxx.xxx.xxx-xx no CPF.

Para os campos referentes ao endereço, ao informar o CEP, um código javascript faz o acesso ao webservice do ViaCEP com a biblioteca jQuery/Json e, se localizar o CEP informado, faz o preenchimento automático dos campos rua, bairro, cidade e estado.

É feita a validação no CPF, para que não seja possível informar um valor inválido, caso isso aconteça, o conteúdo do campo é apagado.

Um código simples em javascript também foi criado para que, ao clicar no botão enviar, seja exibida uma mensagem ao usuário, informando que o cadastro foi realizado.

Para melhor organização, os arquivos .js e a CSS são arquivos externos, que foram linkados no código da página.

Sobre o uso da CSS, é importante ressaltar que como a página foi desenvolvida por uma pessoa com deficiência visual, inicialmente foi feita uma estilização básica e, com auxílio de conteúdos encontrados na internet, tentou-se deixar o formulário mais apresentável.
Foram feitas alterações com base em modelos e exemplos encontrados, mas uma parte permanece fiel ao original, incluindo-se aí os comentários, já que é um conteúdo que será aprofundado.

### Fontes
[Script para buscar e preencher as informações com base no CEP][1]
[Meu primeiro formulário HTML - Aprendendo desenvolvimento web | MDN][2]
[Validar CPF com JavaScript][3]
[Customizando formulários com CSS][4]
[https://encycolorpedia.pt/][5]

[1]: https://viacep.com.br/exemplo/jquery/
[2]: https://developer.mozilla.org/pt-BR/docs/Learn/Forms/Your_first_form
[3]: https://www.devmedia.com.br/validar-cpf-com-javascript/23916
[4]: https://www.devmedia.com.br/customizando-formularios-com-css/37212
[5]: https://encycolorpedia.pt/%2079%25%20intensidade.