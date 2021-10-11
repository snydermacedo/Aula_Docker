# Docker Instalação

# Docker no Windows

Pessoal desculpe pela informação equivocada, o Docker Deskop se tornou pago sim mas, o Docker Free se tornou o Docker Personal, abaixo a explicação do proprio site do Docker.

![docker-personal](https://github.com/snydermacedo/Aula_Docker/blob/main/img/docker-personal.png)

Galera nos meus testes, o Docker Desktop não foi satisfatorio, este video [Rodando Docker no WSL 2 sem Docker Desktop](https://youtu.be/wpdcGgRY5kk), eu achei a melhor forma de usar o Docker no Windows, direto do WSL2. Um ponto importante que o video mostra é o consumo de memoria para usar o Docker Desktop em media 3GB.

Abaixo vou deixar uns videos extra.

[Link 01](https://pureinfotech.com/install-windows-subsystem-linux-2-windows-10/) | [Link 02](https://youtu.be/05YN8F8ajBc) | [Link 03](https://youtu.be/np_vyd7QlXk)

Outras opções
-

Virtual Box
-

Nesta opção eu recomento a vocês baixarem a ISO do [Linux Mint XFCE](https://www.linuxmint.com/edition.php?id=290) e instalarem o Mint no Virtual Box.
Recomento o Mint XFCE devido a leveza, consume em média uns 500MB de memoria RAM, criando uma VM com uns 2GB pra os teste vai ser suficiente.

[Como INSTALAR o LINUX MINT 20 "Ulyana" de maneira FÁCIL](https://www.youtube.com/watch?v=QMdbSULEUXA) - O Site não esta atualizado mais os links são parecidos

Para instalar o Docker neste cenario é bem mais facil basta abrir o terminal e digital:
```shell
sudo apt install docker
```

Vagrant
-

Aqui continuaremos a usando o Virtual Box, mas não diretamente.

Para instalação vou link da Aula do Caio Delgado: [Docker DCA 00 - Preparação da Máquina (Windows / Linux)](https://www.youtube.com/watch?v=U-GGoWq26C4&t=386s)

# Linux - Instalação
!!! Aviso !!! Faça backup do seus Arquivos
-

Aqui podemos instalar o Linux diretamente no seu PC ou Note, com ou sem Dual Boot.

Instalação com Dual Boot:

[Como fazer DUAL BOOT com Windows 10 e Linux - Tutorial FÁCIL - 2021](https://www.youtube.com/watch?v=6D6L9Wml1oY) | O Grande Diolinux :)

[INSTALANDO o Linux Mint 20 em DUALBOOT com o Windows 10](https://www.youtube.com/watch?v=jg77APaMUlQ)

Instalação Nativa - Sem Dual Boot:

[VOCÊ CONSEGUE USAR LINUX? TUTORIAL DE FORMATAÇÃO! ](https://www.youtube.com/watch?v=WgJksOkfnTQ&t=0s) | O Grande Diolinux :)

Docker no Linux
-

Jeito fácil 😁 Automático
Execute o comando abaixo
```shell
curl -fsSL https://get.docker.com -o get-docker.sh
sudo sh get-docker.sh
```
