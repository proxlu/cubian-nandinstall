# Instalar em NAND
Instalar o Cubian no NAND é muito fácil.

Primeiro, você precisa instalá-lo em seu cartão Micro-SD usando o balenaEtcher, então inicialize e faça o login em seu Cubieboard. o nome de usuário e senha padrão é cubie

Uma vez logado, você executará os seguintes comandos

    git clone https://github.com/proxlu/cubian-nandinstall.git
    cd cubian-nandinstall/
    sudo ./install.sh

Após, desligue o sistema e remova o cartão Micro-SD, ligue-o e ja estará com o Cubian iniciando pela NAND.
