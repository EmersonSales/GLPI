Disponibilizado código do canal Radamés Kremer do YouTube "Instalação do GLPI no Ubuntu 20.04,22.04 ou 24.04 só com um comando" (https://www.youtube.com/watch?v=s5ZFNMpbJT0), Testado em 10/03/2025.
O arquivo instala.sh possui o código para a instalação, se não tiver como colar ou baixar no seu servidor acesse via SSH:

O SSH (Secure Shell) é um protocolo que permite acesso remoto seguro a um servidor. Ao combinar SSH com o GitHub, você pode gerenciar seus repositórios de forma mais eficiente e segura. Aqui está um guia passo a passo sobre como usar SSH no Ubuntu Server com a ajuda do GitHub:

1. Gere um par de chaves SSH:

Abra o terminal no seu computador local.
Digite o seguinte comando, substituindo "seuemail@exemplo.com" pelo seu endereço de e-mail do GitHub:
ssh-keygen -t rsa -b 4096 -C "seuemail@exemplo.com"
Pressione Enter para aceitar o local padrão para salvar as chaves (~/.ssh/id_rsa).
Você pode definir uma senha para a chave ou deixar em branco.

2. Conecte-se ao seu Ubuntu Server via SSH:

No seu terminal local, digite o seguinte comando, substituindo "seu_usuario" e "seu_servidor" pelas informações do seu servidor:
ssh seu_usuario@seu_servidor
Se for a primeira vez que você se conecta ao servidor, você será solicitado a confirmar a impressão digital do servidor. Digite "yes" e pressione Enter.
Se você definiu uma senha para a chave SSH, digite-a.

Mantenha sua chave privada (id_rsa) segura. Não a compartilhe com ninguém.
Você pode gerar chaves SSH diferentes para diferentes servidores.
