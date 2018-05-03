## O que o twitter está pensando? Extraindo informações em redes sociais utilizando Python.

`por: `[@profadolfoguimaraes](http://www.instagram.com/profadolfoguimaraes)

Esse projeto foi resultado de um minicurso de coleta de dados do twitter ministrado em 2016. 
Em março de 2018, resolvi retomá-lo para ministrar novamente. Na ocasião foram coletados 
em torno de 600 tweets com as hashtags *#teambatman* e *#teamsuperman*. A proposta do minicurso é 
coletar os dados, fazer um rápido pré-processamento e exibir as informações em uma página web. 

O material completo desse minicurso pode ser encontrado no site: 
[http://www.data2learning.com/cursos](http://www.data2learning.com/cursos)


## Repositórios

O projeto está dividido em dois repositórios: 

* [d2l-minicursotwitter-notebook](http://github.com/adolfoguimaraes/d2l-minicursostwitter-notebook) `(este repositorio)`: possui todos os jupyter notebooks de explicação do conteúdo abordado no minicurso. 
* [d2l-minicursortwitte-web](http://github.com/adolfoguimaraes/d2l-minicursotwitter-web): possui a página web criada para visualizar as informações coletadas do twitter.

## Instalação das dependências

Para o projeto funcionar é necessário instalar algumas depedências que estão listadas no arquivo `requirements.txt`. Para 
instalar utilize o comando: 

```shell
pip install -r requirements.txt
```

O projeto utiliza python versão 3.x.

### API do Twitter

Para usar a API do Twitter é preciso se cadastrar em [apps.twitter.com](http://apps.twitter.com) e criar um App para obter 
as credenciais: Keys e Tokens. No código todas as credenciais estão como `None`. Esse valor deve ser substituído pelas credenciais
obtidas no site do twitter. Uma breve explicação de como obter tais credenciais
pode ser encontrada nos slides disponibilizados [neste link](http://www.data2learning.com/cursos).

### Jupyter Notebook

Para editar os notebooks é preciso instalar o Jupyter Notebook. Informações em: [http://jupyter.org/](http://jupyter.org/)

### Conteúdo deste repositório:

1. [Coletando dados do twitter (Parte 1)](01_ColetandoDadosTwitter_Parte1.ipynb)
2. [Coletando dados do twitter (Parte 2)](02_ColetandoDadosTwitter_Parte2.ipynb)
3. [Pré-processamento utilizando NLTK](03_PreProcessamentoDeTexto_NLTK.ipynb)
4. [Juntanto Twittet + NLTK](04_JuntandoTudo.ipynb)

Qualquer dúvida e/ou sugestões, entre em contato:

`e-mail: `
[adolfo@data2learning.com](mailto:adolfo@data2learning.com) 

`instagram: `
[@profadolfoguimaraes](http://www.instagram.com/profadolfoguimaraes)