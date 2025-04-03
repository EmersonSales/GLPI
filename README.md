Disponibilizado código do canal Radamés Kremer do YouTube "Instalação do GLPI no Ubuntu 20.04,22.04 ou 24.04 só com um comando" (https://www.youtube.com/watch?v=s5ZFNMpbJT0), Testado em 10/03/2025.
O arquivo instala.sh possui o código para a instalação, se não tiver como colar ou baixar no seu servidor acesse via clone GIT

sudo apt update

sudo apt install git

Escolha onde você quer colocar os arquivos do repositório.
cd /caminho/do/diretorio/desejado

Faça o clone do repositório:
git clone https://github.com/EmersonSales/GLPI

Navegue até a pasta que está o script:
cd GLPI

Dê permissão de execução para o script
chmod +x instala.sh

execute o script
./instala.sh
