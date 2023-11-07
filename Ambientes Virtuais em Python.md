# Trabalhando com Ambientes Virtuais Python no Visual Studio Code

## Criar e Ativar um Ambiente Virtual Python

Se você está desenvolvendo em Python no Visual Studio Code, é uma prática recomendada trabalhar em um ambiente virtual. Isso ajuda a isolar as dependências do projeto e a manter a compatibilidade.

### Criar um Ambiente Virtual Python

Para criar um ambiente virtual Python, siga estes passos:

1. Abra o terminal no Visual Studio Code. Use o atalho `Ctrl` + `` no Windows ou `Cmd` + `` no macOS.

2. Navegue até a pasta raiz do seu projeto, onde deseja criar o ambiente virtual.

3. Execute o seguinte comando para criar um ambiente virtual Python com `virtualenv`:

   No Windows:

   ```powershell
   python -m venv nome_do_ambiente

## Ativar um Ambiente Virtual Python com PowerShell no Visual Studio Code

Para ativar um ambiente virtual Python usando o PowerShell no Visual Studio Code, siga os seguintes passos:

1. Abra o terminal no Visual Studio Code. Você pode usar o atalho `Ctrl` + `` no Windows ou `Cmd` + `` no macOS.

2. Navegue até a pasta raiz do seu ambiente virtual ou forneça o caminho completo para a pasta do ambiente virtual.

3. Use o comando `.\nome_do_ambiente\Scripts\Activate.ps1` para ativar o ambiente virtual. Certifique-se de substituir `nome_do_ambiente` pelo nome real do ambiente virtual.

4. Se a execução de scripts estiver desabilitada no PowerShell, você pode permiti-la executando o seguinte comando:

   ```powershell
   Set-ExecutionPolicy RemoteSigned
