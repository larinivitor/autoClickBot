## Instalação

Você precisará baixar e instalar o Python, linguagem de programação.<br/>
Baixe a última versão pelo [link]( https://www.python.org/downloads/).<br/> 
No processo de instalação, marque a opção "Add Python to PATH".<br/>
Baixe o conteudo deste repositorio.<br/>
Abra o CMD (Windows + R -> cmd -> Enter) e execute os comandos abaixo:
```
pip install pyautogui
pip install pillow
pip install pywin32
```
Antes do próximo passo, tenha certeza que seu lol esta em modo janela!
Vá na pasta onde esta os arquivos baixados, clique em arquivo -> abrir o Windows PowerShell, digite o comando a baixo:
```
python mouse.py
```
Esse programa mostra as coordenadas do seu mouse e usaremos o dados aqui informados para configurar o programa.
Abra o arquivo Tokens.py com algum editor de texto e configure as coordenadas que estão na primeira parte do arquivo, que vão de "xProcurarPartida" até "yPixelDesktop". Basta você colocar o mouse em cima do local indicado e atualizar as coordenadas do arquivo Tokens.py, de acordo com seu computador.
Salve o arquivo. Pronto, configurado!

## Execução

Feche todos os programas que não sejam o bot e o LoL, abre o powershell na pasta do arquivo, mover essa tela azul de preferência para cima na esquerda (deixe ela menor para não interferir) e, estando no lobby do TFT normal game, digite no PowerShell:

```
python Tokens.py
```

O programar deverá começar a trabalhar. Quando quiser parar, basta fechar a janela do PowerShell.

## Importante

*O cliente e o jogo não podem ser movidos durante a operação do bot, e nem o mouse, de preferência.*
