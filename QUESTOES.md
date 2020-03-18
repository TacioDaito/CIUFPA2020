Q4
 - 
Mutiple regression:
 É o modelo que utiliza varias variaveis independentes para chegar em uma variavel dpendente (para realizar uma previsao e cheagar em um unico resutado)

Univariete regression:
 É um modelo que utiliza uma uma unica saida e tenta prever apenas um resultado

Multuivariete regression:
 Já nesse modelo, os valores de N variáveis independentes são usados na previsão de N variáveis dependentes, sendo N  um número natural maior que 1

Q14
 -
 Matplotlib é uma biblioteca de plotagem.
Para dar suporte a todos esses casos de uso, o matplotlib pode direcionar saídas diferentes e cada um desses recursos é chamado de back-end; o "front-end" é o código voltado para o usuário, ou seja, o código de plotagem, enquanto o "back-end" faz todo o trabalho duro nos bastidores para fazer a figura. Existem dois tipos de back-end: back-end da interface do usuário (para uso em pygtk, wxpython, tkinter, qt4 ou macosx; também conhecido como "back-end interativo") e back-end de cópia impressa para criar arquivos de imagem (PNG, SVG, PDF, PS; também conhecido como "back-ends não interativos").

Q21
  -
 O virtualenv, uma ferramenta de criação e simulação de ambientes virtuais isolados, que pode ser instalado através dos comandos `pip install --user -U virtualenv` no CMD do Windows e `python3 -m pip install --user -U virtualenv` no bash do Linux e MacOS — sendo `--user` um argumento usado para realizar instalações sem precisar da permissão do administrador e `-U` para atualizar a ferramenta para a versão mais recente —, é utilizada através do comando `virtualenv env`, o qual cria uma pasta no diretório atual onde os arquivos do novo ambiente serão criados.

 É possível também criar um ambiente virtual através de uma interface gráfica. A IDE PyCharm possui uma janela para criação de ambientes virtuais que pode ser acessada por Settings/Configurações->Project/Projeto->Project Interpreter/Interpretador->Ícone de Engrenagem->Add/Adicionar.

Q28
  -
 Dentro da biblioteca sklearn, é possível sequenciar transformações através da ferramenta e classe chamada `Pipeline`. Como o nome sugere, a Pipeline sequencia uma dada quantidade de passos — descrevidos através de tuplas, com o nome do passo sendo o primeiro elemento e a transformação usada o segundo — os quais todos exceto o último, que deve ser obrigatoriamente um estimador, podem possuir um transformador, pré-processador ou estimador. Qualquer um destes citados que estão contidos no sklearn ou em módulos que sigam o modelo do mesmo podem ser usados na Pipeline.
 
 O sequenciamento via Pipeline ajuda na compreensão e entendimento do código, o que torna o mesmo mais acessível para as diferentes áreas de conhecimento de dados e mais compartilhável entre programadores, visto que cada tarefa que o código executa torna-se mais fácil de entender.
 

Q38
  -

Q45
  -
 No contexto de Machine Learning (ML), Ensemble Methods ou Ensemble Learning ou ainda Métodos de Comitê são métodos de estimagem e previsão de valores que tem como conceito a combinação de diferentes modelos estimativos a fim de atingir uma precisão superior à dos métodos que usam apenas um modelo. Esse aprimoramento se dá através do refinamento e combinação das estimagens individuais desses modelos em uma só estimação, processo este executado por um Ensemble Model adequado aos mesmos.
 
 Um determinado sistema de ML pode ter seu desempenho melhorado com um Ensemble Method que, como exemplo, busca contrabalancear uma dada fraqueza natural de seu modelo estimativo, usando um segundo modelo que preencha as deficiências deste e combinando os resultados de ambos. Dentre os Ensemble Methods, estão alguns como o Bagging, o Stacking, o Boosting e o Voting.  
