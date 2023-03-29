# P O S T M A N

## PRVNÍ VĚC
>Musíme stáhnout Matějův Twitter-Lite. (ideálně plocha, ať si pamatujete umístění)
```
git clone https://github.com/matej-kaska/twitter-lite.git
```
>Otevřeme terminál ve složce Twitter-Lite.
><p>Musíme spustit docker (na Windowsu spustit Docker Desktop app před příkazem).
><p>("C:\Users\kubik\Desktop\twitter-lite") - bude trvat x minut
```
docker compose up
```


### REGISTER
https://identity.getpostman.com/signup


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

### SWAGGER*
>Instalace
>>Nutno mít nainstalovaný Node.js s NPM.
```
npm install -g http-server
git clone https://github.com/swagger-api/swagger-editor.git
http-server -p 8080 swagger-editor
```


