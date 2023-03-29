# P O S T M A N
<br/><br/>

## PRVNÍ VĚC
>Musíme stáhnout Matějův Twitter-Lite. (ideálně plocha, ať si pamatujete umístění)
```
git clone https://github.com/matej-kaska/twitter-lite.git
```
>Zapneme Docker.
><p>Otevřeme terminál ve složce Twitter-Lite.
><p>("C:\Users\kubik\Desktop\twitter-lite") - bude trvat x minut
```
docker compose up
```
  
<br/><br/>
## REGISTER
https://identity.getpostman.com/signup

<br/><br/>
### DOWNLOAD*
https://www.postman.com/downloads/

>Windows
```
powershell.exe -NoProfile -InputFormat None -ExecutionPolicy AllSigned -Command "[System.Net.ServicePointManager]::SecurityProtocol = 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://dl-cli.pstmn.io/install/win64.ps1'))"
```

>MAC (M+)
```
curl -o- "https://dl-cli.pstmn.io/install/osx_arm64.sh" | sh
```

>MAC (Intel)
```
curl -o- "https://dl-cli.pstmn.io/install/osx_64.sh" | sh
```

>Linux
```
curl -o- "https://dl-cli.pstmn.io/install/linux64.sh" | sh
```

 <br/><br/>
### NEWMAN*
>Inslatace
>>Nutno mít nainstalovaný Node.js s NPM.
```
npm install -g newman
```
>Spuštění
```
newman run cesta_ke_kolekci -e cesta_k_prostredi
```

<br/><br/>
### SWAGGER*
>Instalace
>>Nutno mít nainstalovaný Node.js s NPM.
```
npm install -g http-server
git clone https://github.com/swagger-api/swagger-editor.git
http-server -p 8080 swagger-editor
```


