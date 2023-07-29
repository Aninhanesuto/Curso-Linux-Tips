# Curso Linux Essential - Resumo

---

# ***# O que é Linux? GNU? BSD, Licenças e DFSG?***

- Linux:
Linux é um sistema operacional de código aberto, baseado no kernel Linux, desenvolvido em 1991 por Linus Torvalds. O kernel é a parte central do sistema operacional que gerencia recursos do hardware e permite a comunicação entre o hardware e o software. Embora o kernel seja chamado Linux, o sistema operacional completo é geralmente referido como distribuições Linux, que incluem o kernel Linux, além de utilitários e programas desenvolvidos por outras pessoas ou projetos.

![                                Linux Torvalds, criador do kernel Linux.](https://techstart.xyz/wp-content/uploads/2019/02/18-curiosidades-sobre-Linus-Torvalds-o-pai-do-Linux.jpg)

                                                  Linux Torvalds, criador do kernel Linux.

Exemplos populares de distribuições Linux incluem Ubuntu, Fedora, Debian e CentOS.

![](https://teclinux.com/wp-content/uploads/2022/06/flatpak-distros-1024x497.png)

- GNU:
GNU é um acrônimo recursivo para "GNU's Not Unix", um projeto lançado em 1983 pela Free Software Foundation (FSF), liderada por Richard Stallman. O objetivo do projeto GNU era criar um sistema operacional completo e livre, composto inteiramente por software livre. A FSF desenvolveu muitas ferramentas e utilitários, incluindo o GCC (GNU Compiler Collection) e o Emacs, que são amplamente utilizados em sistemas GNU/Linux.

![                                Richard Stallman, o gênio craidor do GNU](https://upload.wikimedia.org/wikipedia/commons/f/f3/Richard_Stallman_by_Anders_Brenna_01.jpg)

                                                   Richard Stallman, o gênio craidor do GNU

- BSD:
BSD (Berkeley Software Distribution) é uma família de sistemas operacionais de código aberto baseados no UNIX desenvolvida na Universidade da Califórnia, em Berkeley. Existem várias variantes do BSD, incluindo FreeBSD, OpenBSD, NetBSD e outras. O BSD é conhecido por sua ênfase em licenças de software permissivas e segurança.
- Licenças de Software:
As licenças de software descrevem os termos e condições sob os quais o software pode ser usado, modificado e redistribuído. Existem duas principais categorias de licenças de software em relação ao software livre:
    - Licenças de Software Livre: Permitem aos usuários executar, copiar, modificar e redistribuir o software livremente. Alguns exemplos de licenças de software livre incluem a Licença Pública Geral GNU (GPL) e a Licença MIT.
    - Licenças de Software Proprietário: Impõem restrições ao uso, cópia, modificação ou redistribuição do software. Os usuários geralmente precisam adquirir uma licença ou permissão específica do detentor dos direitos autorais para usar o software.
- DFSG (Debian Free Software Guidelines):
As Diretrizes de Software Livre do Debian são um conjunto de critérios estabelecidos pelo projeto Debian para determinar se um programa ou software é considerado "software livre" e, portanto, adequado para inclusão nas distribuições do Debian. Essas diretrizes ajudam a garantir que o Debian permaneça uma distribuição inteiramente composta por software livre.

Em resumo, Linux é um sistema operacional que usa o kernel Linux, GNU é um projeto de software livre que contribuiu com muitas ferramentas e utilitários para sistemas GNU/Linux, BSD é uma família de sistemas operacionais de código aberto baseados no UNIX, Licenças de Software definem os termos de uso do software e as DFSG são diretrizes para determinar se um software é livre o suficiente para ser incluído na distribuição Debian.

---

## ***# O que é Bash?***

Bash (Bourne Again SHell) é um shell de linha de comando, ou seja, é um interpretador de comandos que fornece uma interface de texto para interagir com o sistema operacional. Ele é uma evolução do shell original do Unix, chamado Bourne Shell (sh), desenvolvido por Stephen Bourne.

O Bash é amplamente utilizado em sistemas operacionais baseados em Unix e Linux devido à sua funcionalidade poderosa, flexibilidade e facilidade de uso. Ele é o shell padrão em muitas distribuições Linux e também é amplamente suportado em outros sistemas operacionais Unix-like.

---

## *Comandos Bash Principais:*

 Abaixo estão alguns dos principais comandos do Bash:

- Navegação de diretórios:
    - `cd`: Mudar o diretório atual.
    - `pwd`: Mostrar o diretório atual.
    - `ls`: Listar arquivos e diretórios.
    - `mkdir`: Criar um novo diretório.
    - `rmdir`: Remover um diretório vazio.
    - `rm`: Remover arquivos ou diretórios.
    - `cp`: Copiar arquivos ou diretórios.
    - `mv`: Mover ou renomear arquivos ou diretórios.
- Manipulação de arquivos:
    - `touch`: Criar um novo arquivo vazio.
    - `cat`: Exibir o conteúdo de um arquivo.
    - `less` ou `more`: Exibir o conteúdo de um arquivo página por página.
    - `head`: Exibir as primeiras linhas de um arquivo.
    - `tail`: Exibir as últimas linhas de um arquivo.
- Redirecionamento e tubulação:
    - `>`: Redirecionar a saída para um arquivo (sobrescrever).
    - `>>`: Redirecionar a saída para um arquivo (anexar).
    - `|`: Encaminhar a saída de um comando para outro.
- Permissões de arquivos:
    - `chmod`: Alterar as permissões de acesso de um arquivo ou diretório.
    - `chown`: Alterar o proprietário de um arquivo ou diretório.
    - `chgrp`: Alterar o grupo proprietário de um arquivo ou diretório.
- Gerenciamento de processos:
    - `ps`: Exibir os processos em execução.
    - `kill`: Encerrar um processo.
    - `bg`: Colocar um processo em execução em segundo plano.
    - `fg`: Trazer um processo em segundo plano para o primeiro plano.
- Variáveis e ambiente:
    - `echo`: Exibir uma mensagem ou valor de uma variável.
    - `export`: Definir uma variável de ambiente.
    - `$VAR`: Acessar o valor de uma variável (onde VAR é o nome da variável).
- Estruturas de controle:
    - `if`, `else`, `elif`: Estruturas condicionais.
    - `for`: Loop for.
    - `while`: Loop while.
    - `case`: Estrutura de seleção de casos.
- Comandos de ajuda:
    - `man`: Exibir o manual de um comando específico.
    - `help`: Exibir informações de ajuda para comandos internos do Bash.

Esses são apenas alguns dos comandos básicos do Bash. Existem muitos outros comandos e opções disponíveis, e você pode aprender mais sobre eles consultando a documentação do Bash ou executando o comando `man bash` no terminal para acessar o manual completo.

Link: https://quiver-thorn-c78.notion.site/Curso-Linux-Essential-Resumo-7b5860f1f12d4c599d0b411f947fab45
---
