# Sobre o projeto:

Projeto realizado no Qt Creator, como avaliação na disciplina de Técnicas de Programação, do Curso de Bacharelado em Engenharia Elétrica no IFPB Campus João Pessoa.
O projeto tem como foco incentivar os alunos a criarem uma interface funcional, capaz de receber dados informados pelo usuário através da interface, organizá-los, manipulá-los e salvá-los em arquivos ".csv".


# O projeto

O projeto "Listas" foi criado com o intuito de oferecer aos usuários uma interface simples, ainda assim, eficaz que seja capaz de armazenar informações em formato de listas de tarefas ou de compras.

## Manual da interface

A paginas inicial do programa tem uma aparência bem simples e intuitiva, aonde o usuário pode criar uma nova lista, ou ver as listas e templates que ele já salvou.

![enter image description here](https://github.com/LucVeloso/TP_Projeto1/blob/master/Imagens/PaginaInicial.png)

## Criando uma lista

O processe para criar uma lista é simples, após clicar no ícone de adicionar nova lista, uma janelinha aparece e nela o usuário escolhe o nome da lisa, e se ela vai ser de tarefas ou de compras.

![enter image description here](https://github.com/LucVeloso/TP_Projeto1/blob/master/Imagens/AdicionarLista.png)

As listas são únicas dentro das suas categorias, sendo assim eu posso ter duas listas de com o mesmo nome, desde que elas não sejam do mesmo tipo.


### Lista de compras

Na lista de compras o usuário vai adicionar itens de seu desejo, podendo modificar a quantidade e o valor individual de cada item.

![enter image description here](https://github.com/LucVeloso/TP_Projeto1/blob/master/Imagens/ListaDeCompras.png)

A interface da lista de compras ainda informa a quantidade de itens totais, o valor total da lista e quantos itens estão marcados; os itens marcados ainda podem ser ocultos para facilitar a visualização daquilo que ainda não foi comprado, ou até mesmo podem ser excluídos, caso seja a vontade do usuário.

### Lista de tarefas

A lista de tarefas é mais simples e direta que a de compras, aqui o usuário insere apenas a tarefa e marca ela quando quando achar necessário;

![enter image description here](https://github.com/LucVeloso/TP_Projeto1/blob/master/Imagens/ListaDeTarefas.png)

A lista de tarefas conta com as mesmas opções da de compras, para a visualização do usuário.

Obs: Cada umas das listas podem ser ordenadas por cada uma de suas colunas.

## Adicionando um item ou tarefa

Independe da lista que o usuário escolha a maneira de inserir dados vai ser a mesma.
Clicando no botão "Adicionar item", abrira uma pequena janela aonde o usuário nomeia seu item, e caso ele seja válido, será inserido na tabela.

![enter image description here](https://github.com/LucVeloso/TP_Projeto1/blob/master/Imagens/AdicionarItemNaTabela.png)

### Salvar

Ambas as tabelas contam em seus cabeçalhos com as opções de "Salvar" e "Salvar template".
Salvar: cria um arquivo .csv na pasta documentos com o nome da tabela que o usuário informou na sua criação, o arquivo contem todas as informações da tabela.
Salvar template: cria um arquivo .csv com apenas os nomes dos itens, que servem de base para listas novas.


## Carregar arquivos

Na aba de carregar arquivos o usuário encontrará tabelas que mostram os nomes dos arquivos salvos na pasta de documentos;

![enter image description here](https://github.com/LucVeloso/TP_Projeto1/blob/master/Imagens/ListasSalvasTemplate.png)


![enter image description here](https://github.com/LucVeloso/TP_Projeto1/blob/master/Imagens/ListasSalvasListas.png)

### Obrigado pela atenção!

Informações, dúvidas ou feedbacks: [lucas.paulo@academico.ifpb.edu.br](mailto:lucas.paulo@academico.ifpb.edu.br)
