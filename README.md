# Instalar em NAND
Instalar o Cubian no NAND é muito fácil.

Primeiro, você precisa instalá-lo em seu cartão Micro-SD usando o tutorial acima, então inicialize e faça o login em seu Cubieboard. o nome de usuário e senha padrão é cubie

Uma vez logado, se você tiver uma versão anterior, você executará o seguinte comando

  sudo ~/nandinstall/install.sh
No entanto, se você tiver a versão mais recente, a pasta ~/nandinstall não estará lá. Nesse caso, você precisa instalar a ferramenta por conta própria e depois executá-la, da seguinte forma:

    sudo apt-get update
    sudo apt-get install cubian-nandinstall
    sudo cubian-nandinstall
Nota: Se você receber o erro 'Método /usr/lib/apt/methods/ não foi iniciado corretamente', tente executar apt-get update primeiro. Isso acontece porque o apt-get tenta instalar uma versão antiga do cubian-nandinstall de packages.cubian.org.

