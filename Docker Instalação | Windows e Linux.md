# Docker Instalação

# Docker no Windows

~~Pessoal, uma notícia para quem usa Windows: o aplicativo Docker Desktop agora é pago, para contornar isso vamos usar o WSL2.~~

Pessoal, desculpe pela informação equivocada, o Docker Deskop se tornou pago sim mas, o Docker Free se tornou o Docker Personal, abaixo a explicação do próprio site do Docker.

![docker-personal](https://github.com/snydermacedo/Aula_Docker/blob/main/img/docker-personal.png)

Galera, nos meus testes o Docker Desktop não foi satisfatório, neste vídeo [Rodando Docker no WSL 2 sem Docker Desktop](https://youtu.be/wpdcGgRY5kk), eu achei a melhor forma de usar o Docker no Windows, direto do WSL2. Um ponto importante que o video mostra é o consumo de memoria para usar o Docker Desktop em media 3GB.

Abaixo vou deixar uns vídeos extra.

[Link 01](https://pureinfotech.com/install-windows-subsystem-linux-2-windows-10/) | [Link 02](https://youtu.be/05YN8F8ajBc) | [Link 03](https://youtu.be/np_vyd7QlXk)

Outras opções:
-

Virtual Box
-

Nesta opção eu recomento a vocês baixarem a ISO do [Linux Mint XFCE](https://www.linuxmint.com/edition.php?id=290) e instalarem o Mint no Virtual Box.
Recomento o Mint XFCE devido a leveza, consome em média uns 500MB de memória RAM, criando uma VM com uns 2GB; para os testes vai ser suficiente.

[Como INSTALAR o LINUX MINT 20 "Ulyana" de maneira FÁCIL](https://www.youtube.com/watch?v=QMdbSULEUXA) - O Site não esta atualizado mais os links são parecidos

Para instalar o Docker neste cenário é bem mais fácil, basta abrir o terminal e digitar:
```shell
# Docker Installation Command
sudo apt install docker
# Add user to docker group
sudo usermod -aG docker
# Restart your system
sudo reboot
```

Vagrant
-

Aqui continuaremos usando o Virtual Box, mas não diretamente.

Para instalação vou deixar o link da Aula do Caio Delgado: [Docker DCA 00 - Preparação da Máquina (Windows / Linux)](https://www.youtube.com/watch?v=U-GGoWq26C4&t=386s)

# Linux - Instalação
!!! Aviso !!! Faça backup dos seus Arquivos
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
sudo usermod -aG docker
```

Ou siga a documentação da sua distro
[Docker Instalação](https://docs.docker.com/engine/install/)
