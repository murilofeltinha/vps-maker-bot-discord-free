Olá sou o feltinha conhecido por Apolinário, vim ensinar como ligar o bot VPS MAKER BOT DISCORD FREE Gerador de Vps

Primeiro clone o repositorio:
``git clone https://github.com/murilofeltinha/vps-maker-bot-discord-free``

Depois acesse o repositorio clonado:
``cd ubuntu-22.04``

Agora vamos buildar o docker:
``docker build -t ubuntu-22.04-with-tmate .``

Estamos quase ligando o bot agora vamos instalar as dependencias do bot:
``apt install pip -y && pip install discord && pip install docker``

Configure o main.py e depois execute o ULTIMO comando:
``apt install python3 -y && python3 main.py``
