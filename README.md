# Programa servidor API-REST de Calculadora utilizando Node.js.

## Descrição

- O projeto foi desenvolvido no VSCode deve ser chamado "calculadora_nodejs".
- Programa cliente está no projeto "calculadora_reactjs".
- Programa servidor cria o webservice na posta 8000.
- Implementação do serviço utilizando REST e o método GET.
- Classe Calculadora executa quatro operações: adição, subtração, multiplicação e divisão.

## Dependências

- cors,
- express.

## Execução

   <pre><code>npm start</code></pre>
   
## Atualização

   Caso o diretório "node_modules" tenha sido apagado basta executar o comando npm a seguir para recriar a pasta e os arquivos das dependências.
   <pre><code>npm update</code></pre> 
   
## Arquivos fontes do projeto em src

- index.js - Programa principal com o servidor Express.
- calculadora.js - Contêm a classe da calculadora.
- calculadoraresultado.js - Contêm a classe de retorno ddas operações da calculadora.
- calculadorarecurso.js - Contêm os métodos de acesso aos recursos da calculadora.
- servicos.js - Contêm as rotas aos métodos de acesso a calculadora.

## Serviços

 - Serviço da rota inicial VIA GET.
    `http://localhost:8000`

 - Serviço de adição via GET.
    Substitua `<VALOR1\>` e `<VALOR2\>` pelos valores a serem somados.<br>
    `http://localhost:8000/adicao/<VALOR1>/<VALOR1>`

- Serviço de subtração via GET.
    Substitua `<VALOR1\>` e `<VALOR2\>` pelos valores a serem subtraídos.<br>
    `http://localhost:8000/subtracao/<VALOR1>/<VALOR1>`

- Serviço de produto via GET.
    Substitua `<VALOR1\>` e `<VALOR2\>` pelos valores a serem multiplicados.<br>
    `http://localhost:8000/produto/<VALOR1>/<VALOR1>`

- Serviço de divisão via GET.
    substitua \<VALOR1\> e \<VALOR2\> pelos valores a serem divididos.<br>
    http://localhost:8000/divisao/<VALOR1>/<VALOR1>        
