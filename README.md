# Comunicação em IoT
Repositório criado para versionamento da atividade sobre comunicação em IoT da residência em software embarcado, com implementação de um projeto de monitoramento ambiental.


## Descrição do Funcionamento do programa 
No WebServer é mostrado botões para acionamento da bomba d’água simulada e um botão para atualização dos sensores, que são mostrados na parte inferior da página, com a temperatura em °C e o nível percentual do reservatório. O botão B pode ser utilziado para colocar a placa em modo BOOTSEL

## Compilação e Execução
**OBS: Nas linhas 15 e 16 do arquivo `main.c`é necessário inserir as credenciais da rede ao qual objetiva-se a conexão**


1. Certifique-se de que o SDK do Raspberry Pi Pico está configurado no seu ambiente.
2. Compile o programa utilizando a extensão **Raspberry Pi Pico Project** no VS Code:
   - Abra o projeto no VS Code, na pasta COMUNICA-O-EM-IOT tem os arquivos necessários para importar 
   o projeto com a extensão **Raspberry Pi Pico Project**.
   - Vá até a extensão do **Raspberry pi pico project** e após importar (escolher sdk de sua escolha) os projetos  clique em **Compile Project**.
3. Coloque a placa em modo BOOTSEL e copie o arquivo `Projeto_webserver.uf2`  que está na pasta build, para a BitDogLab conectado via USB.

**OBS: Devem importar os projetos para gerar a pasta build, pois a mesma não foi inserida no repositório**

## Colaboradores
- [PauloCesar53 - Paulo César de Jesus Di Lauro ] (https://github.com/PauloCesar53)

