# sensor-iot-app

Essa é uma aplicação web desenvolvida em react que possibilita a comunicação, via MQTT, com uma SBC que centraliza os dados lidos de sensores a partir de uma Node MCU (ESP8266).

Para clonar o repositório, utilize o comando:

```git
git clone https://github.com/antonyaraujo/sensor-iot-app.git
```

Após clonar a pasta, acesse-a no diretório clonado com:

```
cd sensor-iot-app
```

Acessado a pasta é necessário realizar o download e instalação dos módulos que permitem a sua compilação, para isso:

```
yarn
```
ou
```
yarn i
```

após a instalação dos módulos (node), basta apenas executar a aplicação, com:
```
yarn run start
```

A partir desse comando será inicializado um servidor web local na porta 3000 (ou conseguintes, se a porta 3000 já estiver em uso), para acessar, basta acessar o endereço:

```
http://localhost:3000
```


