GIT Intruções:

conectar o git(bash)(do que ja foi feito) 
ao github(repositorio):

criar um repositorio no github
e conectar usando o endereço
git remote add origin git@github.com:renatomorenoagudo/dataops-jornadadedados-lgalvao.git
git remote add origin https://github.com/renatomorenoagudo/dataops-jornadadedados-lgalvao.git
se der erro fatal na publicação, pode usar o pedido de 
nao rastreio:
git push --set-upstream origin master

se nao tiver conectado à porta 22 do github ele tbm dara erro, 
ai so conectar ao lado do prompt (Ports) e colocar a porta apontada
no erro.
  
apos use o publicar:

git push --set-upstream origin master 

para que os arquivos fiquem somente na pasta externa do programa:
source .venv/Scripts/activate

 e agora sim instala os arquivos(packet) :
pip install streamlit

precisa entrar no ambiente python para reconhecer a import streamlit
clicando no ícune que tem duas setas no canto direito ao lado (open changes)
ele ja vai reconhecer, ou então pode aparecer um aviso na parte abaixo com python e versao (.venv)...
..perceba q a cor do import streamlit muda e fica igual aos outros imports. ai reconheceu;.

