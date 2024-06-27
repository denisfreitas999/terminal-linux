# Linux

Compilado de informações sobre o Linux

# VI

## 1. Iniciando o VIM:
Para abrir e editar um arquivo, use:

`vi <nome_do_arquivo.tipo>`


## 2. Modos do VIM:

### Modo de Inserção
Permite que você escreva no arquivo. Para entrar no modo de inserção:
- Pressione `i` para começar a escrever onde o cursor está.
- Pressione `A` para começar a escrever no final da linha.

### Modo Normal
Usado para navegar e emitir comandos. Para sair do modo de inserção e voltar ao modo normal, pressione `ESC`.

## 3. Salvando e Saindo:

### Para salvar as alterações:
- Primeiro, pressione `ESC` para sair do modo de inserção.
- Então, digite `:w <nome_do_arquivo.tipo>` e pressione `Enter`.

### Para sair do VIM:
- Sem salvar alterações, digite `:q!` e pressione `Enter`.
- Salvando alterações e saindo, digite `:wq` ou `:x` e pressione `Enter`.

## 4. Navegação e Edição:

### Copiar e Colar:
- Para copiar uma linha, posicione o cursor na linha e pressione `yy`.
- Para colar a linha copiada, pressione `p`.

### Cortar e Colar:
- Para cortar (recortar) uma linha, pressione `dd`.
- Para colar a linha cortada, pressione `p`.

### Criar nova linha:
- Para criar uma nova linha abaixo da linha atual, pressione `o`.

## 5. Localização e Substituição:

### Localizar:
- Para localizar uma palavra ou expressão, digite `:/<termo>` e pressione `Enter`.

### Substituir:
- Para substituir um termo na linha atual, use `:s/nome_do_item/nome_substituto`.
- Para substituir em todo o arquivo, use `:%s/nome_do_item/nome_substituto/g`.

## 6. Comandos Úteis Adicionais:

### Desfazer e Refazer:
- Para desfazer a última ação, pressione `u`.
- Para refazer a ação desfeita, pressione `Ctrl + r`.

### Movimentação:
- Use as setas do teclado ou `h`, `j`, `k`, `l` para mover o cursor (esquerda, baixo, cima, direita, respectivamente).
- Para mover-se rapidamente entre palavras, use `w` (próxima palavra) e `b` (palavra anterior).

### Indentar:
- Para indentar uma linha, pressione `>>`.
- Para desindentar, pressione `<<`.


# Comandos Linux

## `pwd`
Exibe o diretório atual de trabalho.

## `ls`
Lista o conteúdo do diretório atual.

## `ls -a`
Lista todos os arquivos, incluindo os ocultos (aqueles que começam com um ponto).

## `ls -la`
Lista todos os arquivos, incluindo os ocultos, com detalhes adicionais como permissões, número de links, proprietário, tamanho e data de modificação.

## `cd` *path* || *nome_diretorio*
Muda para o diretório especificado pelo *path* ou *nome_diretorio*.

## `cd..`
Muda para o diretório pai (um nível acima na hierarquia de diretórios).

## `clear`
Limpa a tela do terminal.

## `mkdir` *nome_diretorio*
Cria um novo diretório com o *nome_diretorio* especificado.

## `rmdir` *nome_diretorio*
Remove um diretório vazio com o *nome_diretorio* especificado.

## `touch` *nome_arquivo.tipo*
Cria um novo arquivo vazio com o *nome_arquivo.tipo* especificado ou atualiza a data de modificação de um arquivo existente.

## `cat`
Exibe o conteúdo de um arquivo.

## `echo` *descricao* > *nome_arquivo.tipo*
Escreve a *descricao* no arquivo especificado. Se o arquivo já existir, ele será sobrescrito.

## `echo` *descricao* >> *nome_arquivo.tipo*
Acrescenta a *descricao* ao final do arquivo especificado. Se o arquivo não existir, ele será criado.

## `rm` *nome_arquivo.tipo*
Remove o arquivo especificado.

## `rm -r` *nome_diretorio*
Remove o diretório especificado e todo o seu conteúdo de forma recursiva.

## `mv` *nome_arquivo.tipo a renomear* *novo_nome.tipo*
Move ou renomeia o arquivo especificado.

## `cp` *nome_arquivo.tipo* *path*
Copia o arquivo especificado para o *path* especificado.

## `cp` **.tipo* *path*
Copia todos os arquivos do tipo especificado para o *path* especificado.

## `mv` **.tipo* *path*
Move todos os arquivos do tipo especificado para o *path* especificado.

## `uniq -c` *nome_arquivo.tipo*
Exibe as linhas únicas no arquivo especificado, precedidas pelo número de ocorrências de cada linha.

## `nano`
Abre o editor de texto Nano.

## `vi` *nome_arquivo.tipo*
Abre o editor de texto Vi com o arquivo especificado.

## `zip -r` *nome_arquivo.zip* *nome_diretorio*
Cria um arquivo zip do diretório especificado de forma recursiva.

## `less` *nome_arquivo.tipo*
Exibe o conteúdo do arquivo especificado uma página de cada vez.

## `unzip` *nome_arquivo.zip*
Extrai o conteúdo do arquivo zip especificado.

## `unzip -q` *nome_arquivo.zip*
Extrai o conteúdo do arquivo zip especificado em modo silencioso (sem exibir detalhes).

## `tar -czf` *nome_arquivo.tar.gz* *nome_diretorio*
Cria um arquivo tar gzipado do diretório especificado.

## `tar -xzf` *nome_arquivo.tar.gz*
Extrai o conteúdo do arquivo tar gzipado especificado.

## `chmod`