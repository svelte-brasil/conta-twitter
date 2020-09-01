# conta-twitter
Faça um PR para promover algo no perfil do twitter Svelte Brasil!

Esse projeto usa [twitter-together](https://github.com/gr2m/twitter-together) e é um fork desanexado do [twitter-account](https://github.com/svelte-society/twitter-account).

## A pasta tweets/

Para criar um novo tweet, crie um arquivo `*.tweet` na pasta `tweets/`.

<kbd>[Create new tweet](https://github.com/svelte-brasil/conta-twitter/new/master/?filename=tweets/<your-path>.tweet)</kbd>

## Exemplo

Crie um arquivo `tweets/ola-mundo.tweet` com o conteudo

> Olá, mundo!

Você pode usar subdiretórios, por exemplo `tweets/2019-02/ola-mundo.tweet`, contanto que o arquivo esteja na pasta `tweets/` e tenha a extensão `.tweet`

## Crie um tweet com uma votação/enquete

**Observação**: A conta do twitter precisa estar autorizada a utilizar a Twitters Ads API para mandar votações.

Um tweet com votação deve ter 2 a 4 opções e precisa estar nesse formato

> Aqui vai algum texto
>
> ( ) opção A  
> ( ) opção B  
> ( ) opção C  
> ( ) opção D

## Observações

- Somente novos arquivos são tratados, deleções, atualizações ou renomeios são ignorados.
- Arquivos `*.tweet` não serão criados para tweets enviados direto do twitter.com
- Se você precisa renomear um arquivo, faça isso localmente com [`git mv antigo_nome novo_nome`](https://help.github.com/pt/articles/renaming-a-file-using-the-command-line), de outra forma ele reconhecerá como uma deleção e criação.