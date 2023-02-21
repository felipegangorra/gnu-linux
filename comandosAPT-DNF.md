# Comando do Gerenciador de Pacotes

- **apt update:** atualizar as informações dos pacotes.

- **apt search:** pesquisa nome do pacote, pode ser por palavras chaves ou funcionalidade.

- **apt install (nome):** instalar o pacote.

- **apt remove (nome):** remover o pacote.

- **apt purge (nome):** hard remove, remove todos os arquivos de configração do pacote.

- **apt upgrade:** atualiza as versões dos pacotes e instalar novas depedencias (se existir).

- **apt full-update:**  hard atualização, podendo remover arquivos julgados não necessários depois da atualização. Mais profundo, porém mais arriscado.

- **dpkg -l:** lista todos os pacotes que há no sistema.

- **dpkg -L (nome):** saber quais os arquivos especificos que o pacote colocou na maquina. 