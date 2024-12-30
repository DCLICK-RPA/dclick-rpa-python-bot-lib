# dclick-rpa-python-bot-lib
Pacote com funcionalidades gerais para criação de Bots  
> **❗Python necessário: >= 3.12❗**  
> Repositório original contendo o código [python-bot-lib](https://github.com/AlexLanes/python-bot-lib)

<br>

## Sobre a instalação
Escolher a versão baseado no release + tag desejado do repositório
> Exemplo que será utilizado a seguir: **v2.4**  
> Releases: https://github.com/DCLICK-RPA/dclick-rpa-python-bot-lib/releases

<br>

Em máquina sem o GIT instalado (Útil para a máquina do cliente), informar o link completo para a build do arquivo **.whl**
- **pip install https://github.com/DCLICK-RPA/dclick-rpa-python-bot-lib/releases/download/v2.4/bot-2.4-py3-none-any.whl**

<br>

Existe a dependência opcional **[ocr]** que utiliza o pacote EasyOCR para reconhecimento de caracteres em imagem. Para sua instalação, é necessário:
- Instalar o bot normalmente na máquina
- **pip install bot[ocr]**

## requirements.txt
Para criar o arquivo **requirements.txt** corretamente, colocar o mesmo link utilizado para instalar o **bot** junto com a versão desejada.  
Caso deseje instalar o **[ocr]**, colocar **bot[ocr]** após o link principal
