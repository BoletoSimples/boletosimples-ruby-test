# Exemplo de Uso - Kobana Ruby

Esse é um código de exemplo de uso da [Biblioteca Ruby do Kobana](https://github.com/BoletoSimples/boletosimples-ruby).

## Usando

Baixe o código

    $ git clone https://github.com/BoletoSimples/boletosimples-ruby-test
    $ cd boletosimples-ruby-test

Instale as dependências usando o [Bundler](http://bundler.io/)

    $ bundle install

Crie uma conta no ambiente de Sandbox do Kobana acessando [https://app-sandbox.kobana.com.br/users/sign_up](https://app-sandbox.kobana.com.br/users/sign_up)

Configure o seu acess token, disponível em [https://app-sandbox.kobana.com.br/conta/api/tokens](https://app-sandbox.kobana.com.br/conta/api/tokens)

Edite o arquivo `index.rb` na linha 14 onde está o bloco `BoletoSimples.configure` e inclua as informações obrigatórias para user_agent e api_token.

Configure o ambiente(`environment`) desejado, lembrando que cada ambiente tem seu próprio api_token.

Descomente o exemplo que deseja ser executado.

Rode o código:

```
    $ ruby index.rb
```

## Licença

Esse código é livre para ser usado dentro dos termos da licença [MIT license](http://www.opensource.org/licenses/mit-license.php).

## Bugs, Issues, Agradecimentos, etc

Comentários são bem-vindos. Envie seu feedback através do [issue tracker do GitHub](http://github.com/BoletoSimples/boletosimples-ruby-test/issues)

## Autor

[**Rafael Lima**](http://github.com/rafaelp) trabalhando no [Kobana](https://kobana.com.br)

[**Kivanio Barbosa**](http://github.com/rafaelp) trabalhando no [Kobana](https://kobana.com.br)

Blog: [http://rafael.adm.br](http://rafael.adm.br)

Twitter:

[http://twitter.com/rafaelp](http://twitter.com/rafaelp)

[http://twitter.com/kivanio](http://twitter.com/kivanio)
