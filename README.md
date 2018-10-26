# EDITOR VIM - DICAS 
Dicas de uso do editor de textos VIM.  
## COMANDOS BASICOS 
- :q : sair do VIM
- :q! : sair do VIM sem salvar
- :wq : sair do VIM depois de salvar o arquivo
- h : andar com o cursor para esquerda
- j : andar com o cursor para baixo
- k : andar com o cursor para cima
- l : andar com o cursor para a direita
- x : apagar para frente (equivalente ao delete) 
- X : apagar para tras (equivalente ao basckspace) 
- dw : remove a palavra em que o cursor estiver em cima
- d^^ : apagar a partir do curso ate o inicio da linha
- d$ : apagar a partir do cursor até o fim da linha
- yy | Y : copiar linha 
- d : exclui / recorta palavras
- p : colar linha copiada/recortada na linha abaixo
- a : começar a digitar na proxima coluna
- i : começar a editar
- o : começar a digitar na linha abaixo
- O : começar a digital na linha acima
- esc : cancelar a edição do texto
- u : volta atras na edição da linha (undo ou desfazer)
- r : refaz a edição (redo ou refazer)
- v : entra no modo de selecao. Nesse modo o cursor vai pintando tudo por onde passar, permitindo copiar todo texto
## COMANDOS COMPLEXOS
- Substituir textos
```sh
:s/antigo/novo/ 
```
irá substituir o texto "antigo" pelo texto "novo" na linha do cursor
```sh
:% s/antigo/novo/ 
```
irá substituir o texto "antigo" pelo texto "novo" em todo o arquivo
- Pesquisar textos
```sh
:/texto_pesquisado
```
apos executar a pesquisar, o "n" vai para a proxima ocorrencia e o "N" vai para a ocorrencia anterior
