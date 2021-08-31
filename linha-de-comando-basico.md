Linha de comando (básico)
Windows
    cmd, tabby ou power shell - console para digitar comandos
    dir - visualizar conteúdo dos diretórios

    diretórios . e .. - 
    caminho relativo e caminho completo3

    cd - muda de diretório
        C:\Users\alan.formagi> cd Documents
        C:\Users\alan.formagi\Documents> cd ..
        C:\Users\alan.formagi> cd Documents
        C:\Users\alan.formagi\Documents>

    mkdir - cirar ditetórios
        C:\Users\alan.formagi\Documents> mkdir teste-20210827
        C:\Users\alan.formagi\Documents> dir
        C:\Users\alan.formagi\Documents> cd teste-20210827
        C:\Users\alan.formagi\Documents\teste-20210827> 

    cls - limpa a tela do console
    echo - imprime um conteúdo na tela
        C:\Users\alan.formagi\Documents\teste-20210827> echo Siscobra Sistemas
        Siscobra Sistemas
        C:\Users\alan.formagi\Documents\teste-20210827> echo %date%
        27/08/2021

    date
        C:\Users\alan.formagi\Documents\teste-20210827> date /t
        27/08/2021
        C:\Users\alan.formagi\Documents\teste-20210827> date

    > >> - redirecionamentos

    echo digiteseutextoaqui > arquivo.txt - cria um arquivo em branco
        C:\Users\alan.formagi\Documents\teste-20210827> echo alan formagi > arquivo.txt
        C:\Users\alan.formagi\Documents\teste-20210827> echo siscobra sistemas > arquivo.txt
        C:\Users\alan.formagi\Documents\teste-20210827> echo empadao cheiroso >> arquivo.txt
    type 
        C:\Users\alan.formagi\Documents\teste-20210827> type arquivo.txt
        siscobra sistemas
        empadao cheiroso

    copy - copiar arquivos
    move - mover ou renomear arquivos

    netstat -na
    netstat -na | find "LISTEN" | find "5432"

    cd C:\Program Files\PostgreSQL\13\bin\
    psql -V
    psql -h 127.0.0.1 -p 5432 -U postgres -l
    psql -h 192.168.0.206 -p 5432 -U siscobraweb -l
    psql -h 192.168.0.206 -p 5432 -U siscobraweb -d siscobra_manager -c "select count(*) from acoes"
    psql -h 192.168.0.206 -p 5432 -U siscobraweb -d siscobra_manager -c "select * from acoes"
    psql -h 192.168.0.206 -p 5432 -U siscobraweb -d siscobra_manager

Linux
