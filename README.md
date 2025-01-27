# TCC-ZONE
![GitHub last commit](https://img.shields.io/github/last-commit/DoutorJP/TCC-ZONE)

Implementação de uma solução para o gerenciamento de estacionamentos. 🚗

O sistema contêm duas partes principais: cliente e servidor, estas, se conectam utilizando o ![Firebase](https://firebase.google.com/?hl=pt-br), que funciona como armazenamento de dados e ponte entre ambas as partes.

## Tecnologias Utilizadas 💻
![Firebase](https://img.shields.io/badge/firebase-a08021?style=for-the-badge&logo=firebase&logoColor=ffcd34)
![PHP](https://img.shields.io/badge/php-%23777BB4.svg?style=for-the-badge&logo=php&logoColor=white)
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)

## Documentação 📘
A documentação especifica para cada ferramenta deverá estar disponível em docs/

## Instalação
A Instalação é feita de forma manual, pela equipe de desenvolvimento do ZONE

### Dependências
O script que (por hora) instala apenas as dependências se encontra na raiz do projeto: ```install.sh```
#### SBC 🌐
##### PIP
 - certifi
 - charset-normalizer
 - idna
 - imutils
 - numpy
 - opencv-python
 - packaging
 - pillow
 - pytesseract
 - requests
 - urllib3
#### Cliente 📊
##### Composer
 - [firebase-php](https://github.com/kreait/firebase-php)

## TODO 📝
### SBC 🌐
 ~~- [ ] Criar um script de instalação~~
 - [x] Implementar o OCR no servidor 
 - [x] Implementar o sistema no servidor
 - [x] Refinar os resultados do OCR
 - [x] Melhorar tratamento das fotos
 - [x] Terminar a integração Python - Firebase
 - [x] Encontrar uma versão que funcione no Linux do Tesseract ou encontrar outro OCR

### Cliente 📊
 - [ ] Incluir resto das dependencias
 - [ ] Criar novas funcionalidades na interface
 - [ ] Criar um sistema de cadastro
 - [x] Revisar estrutura banco de dados
 ~~- [ ] Colher e mostrar estátisticas~~
 - [x] Desenvolver a interface PHP integrada com o Firebase

### Outro 📡
 - [ ] Criar o artigo
