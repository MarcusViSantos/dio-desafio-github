### Estudos sobre Git/Github

- **Comandos básicos**

  - **git Init** cria um novo repositório do Git. Ele pode ser usado para converter um projeto existente e não versionado em um repositório do Git ou inicializar um novo repositório vazio.

  - **git add** adiciona uma alteração no diretório ativo à área de staging. Ele diz ao Git que você quer incluir atualizações a um arquivo específico no próximo commit. No entanto, git add não tem efeito real e significativo no repositório — as alterações não são gravadas mesmo até você executar git commit
  
  - **git commit -m** pode ser utilizado de múltiplas formas para comitar as alterações para o repositório**, porém todo commit necessita de uma mensagem para logar, já que esta o identificará. Para isso basta utilizar o comando git commit -m "mensagem de exemplo". A mensagem pode ser qualquer string válida
  
  - **git push main** é usado para enviar o conteúdo do repositório local para um repositório remoto. O comando push transfere commits do repositório local a um repositório remoto. É o oposto do comando git fetch , que importa commits para branches locais, enquanto o comando push exporta commits para branches remotos.
  
  - **git status**  exibe as condições do diretório de trabalho e da área de staging. Ele permite que você veja quais alterações foram despreparadas, quais não foram e quais arquivos não estão sendo monitorados pelo Git
  
    

