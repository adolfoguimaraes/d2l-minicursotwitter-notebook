# Minicursos Data2Learning
## O que o twitter está pensando? Extraindo informações em redes sociais utilizando Python.

`por: `[http://www.instagram.com/profadolfoguimaraes](@profadolfoguimaraes)

Esse projeto foi resultado de um minicurso de coleta de dados do twitter ministrado em 2016. 
Em março de 2018, resolvi retomá-lo para ministrar novamente o minicurso. Na ocasião foram coletados 
em torno de 600 tweets com as hashtags *#teambatman* e *#teamsuperman*. A proposta do minicurso é 
coletar os dados, fazer um rápido pré-processamento e exibir as informações em uma página web. 

O material completo desse minicurso pode ser encontrado no site: 
[http://www.data2learning.com/cursos](http://www.data2learning.com/cursos)


## Repositórios

O projeto está dividido em dois repositórios: 

[d2l-minicursotwitter-notebook](http://github.com/adolfoguimaraes/d2l-minicursostwitter-notebook) `(este repositorio)`: possui todos os jupyter notebook de explicação do conteúdo abordado no minicurso. 
[d2l-minicursortwitte-web](http://github.com/adolfoguimaraes/d2l-minicursotwitter-web): possui a página web criada para visualizar as informações coletadas do twitter.

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
pode ser encontrada [aqui](http://www.data2learning.com/minicurso-o-que-o-twitter-esta-pensando/).

### Jupyter Notebook

Para editar os notebooks é preciso instalar o Jupyter Notebook. Informações em: [http://jupyter.org/](http://jupyter.org/)

Qualquer dúvida e sugestões é só entrar em contato:**

[adolfo@data2learning.com](mailto:adolfo@data2learning.com) ou [@profadolfoguimaraes](http://www.instagram.com/profadolfoguimaraes) (instagram) 