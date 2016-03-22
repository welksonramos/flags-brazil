## Contribua

flags-brazil é construído usando stylus. Siga as seguintes etapas para contribuir corrigindo bugs ou adicionando novas _`features`_.

1. Clone o repo:
 ```
  $ git clone https://github.com/welksonramos/flags-brazil.git
 ```

2. Instale as dependências:
 ```
  $ npm install
 ```

3. Crie uma nova branch para sua feature:
 ```
  $ git checkout -b my-new-feature
 ```

4. Edite o arquivo **_index.html_** adicionando a classe `flag-*` referente ao estado que você irá desenvolver.
  Ex:
  ```html
  <!-- ACRE -->
  <div class="flag-ac">
	  <div class="flag"></div>
	  <h1>Acre<h1>
  </div>
  ```
  Aqui estão a lista de classes que você deve usar:
 ```
  flag-ac - Acre
  flag-al - Alagoas
  flag-ap - Amapá
  flag-am - Amazonas
  flag-ba - Bahia
  flag-cd - Ceará
  flag-df - Distrito Federal
  flag-es - Espírito Santo
  flag-go - Goiás
  flag-ma - Maranhão
  flag-mt - Mato Grosso
  flag-ms - Mato Grosso do Sul
  flag-mg - Minas Gerais
  flag-pa - Pará
  flag-pb - Paraíba
  flag-pr - Paraná
  flag-pe - Pernambuco
  flag-pi - Piauí
  flag-rj - Rio de Janeiro
  flag-rn - Rio Grande do Norte
  flag-rs - Rio Grande do Sul
  flag-ro - Rondônia
  flag-rr - Roraima
  flag-sc - Santa Catarina
  flag-sp - São Paulo
  flag-se - Sergipe
  flag-to - Tocantins
  ```

5. Adicione/Edite os arquivos **_stylus_** que estão em _`src/flags`_:
 ```
  +- src
     +- flags
    	  |- ac.styl
    	  |- ...
     |-- flagsbrasil.styl
 ```

6. Commit suas alterações:
 
 ```
  $ git commit -m "Add flag ac"
 ```

7. Envie para o branch:
 
 ```
  $ git push origin my-new-feature
 ```
8. Envie seu Pull Request

## Rode o projeto localmente

1. Inicie o servidor para compilar e observar as alterações :smile:
```
$ npm run dev
```
