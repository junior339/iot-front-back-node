instale o nodejs se nao tiver instalado
instale o vscode
instalar o python
fazer com que o python fique em uma variavel de ambiente
  
  tente o comando a baixo
npm --add-python-to-path install --global --production windows-build-tools
 
 se nao der certo instale o caminho do seu python 
 na variavel de ambiente no path dentro das variaveis de sistema

no cmd coloque
  npm install -g node-gyp

  e tambem

  npm install johnny-five --msvs_version=2012


  pra  se comunicar com o arduino use o stamdartfreemata

  coloque seu arduino 
  em arquivos 
  exemplos
  firmata
  standartfirmata

  entre na pasta app
  abra um terminal
  digite node app.js

  se inicializado 
  conecte um led de teste na porta 13
  se nao tiver mude a porta no app.js


  inicializado
   led.on()
   led.off()
   teste e me de um retorno no whats

