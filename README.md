 1  apt-get update
 2  apt-get install curl -y
 11  sudo curl -sl http://deb.nodesource.com/setup_10.x | bash
   14  apt-get install nodejs -y
   17  cd opt
   20  mkdir node-app
   21  cd node-app
   22  nano index.js
   23  vi index.js
   24  vim index.js
   25  echo 'console.log("nodejsapp from ubuntu...");' > index.js
   
   28  node index.js
   29  history
