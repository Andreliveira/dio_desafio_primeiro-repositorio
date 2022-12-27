# Introdução ao GIT_GITHUB - DIO 



## Comandos Básicos do GIT:

-  Dir > Mostra os diretórios;

- cd > Abre as pastas desejadas;

- cd .. > Volta para pasta anterior;

- crtl + l > Limpa tela;

- Tecla Tab > Auto completa palavras e facilita na escrita;

- mkdir > Usado para criar pastas; 

- del > Exclui pastas ou arquivos;

- rmdir + pasta /s /q > Apaga diretório completo;

  

## Dentro do GIT existem objetos internos chamados:



1. ### Blobs (bolhas) que armazenam;

   - Meta dados;

   - Tipos de objetos;

   - Tamanho do arquivo entre outros;

      

Além de guardar o chá do arquivo.

2. ### Trees (árvores) que armazenam;

   - Os blobs

   - Apontam para tipos de blols diferentes;

   - Armazenam os nomes dos arquivos;

     

3. ### Commits - o mais importante ele aponta para;

   - Tree -> arquivos;
   - Parente -> commit anterior (última atualização);

   Armazena:

   - Autor - quem fez o projeto;
   - Mensagem - o que foi armazenado;
   - Timestamp - quando inicia e quando termina.

Os commits armazenam blobs e trees quando se altera algo dentro de algum deles todos se modificam como numa reação em cascata.



 

###  *SHÁ 1 desse commit é o hash de toda essa informação, ou seja, é uma espécie de identidade do commit e cada um possui um diferente para identificação do mesmo.*









