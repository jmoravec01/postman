**  P O S T M A N **

## REGISTER
```
https://identity.getpostman.com/signup
```

## DOWNLOAD*
```
https://www.postman.com/downloads/

```## Linux
powershell.exe -NoProfile -InputFormat None -ExecutionPolicy AllSigned -Command "[System.Net.ServicePointManager]::SecurityProtocol = 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://dl-cli.pstmn.io/install/win64.ps1'))"
```

```## MAC (M+)
curl -o- "https://dl-cli.pstmn.io/install/osx_arm64.sh" | sh
```
```## MAC (Intel)
curl -o- "https://dl-cli.pstmn.io/install/osx_64.sh" | sh
```

```## Linux
curl -o- "https://dl-cli.pstmn.io/install/linux64.sh" | sh
```
```

## SELECTS
```
SELECT AVG(`information_schema`.`tables`.`TABLE_ROWS`) AS `prumerny_pocet_zaznamu`
FROM `information_schema`.`TABLES`
WHERE (`information_schema`.`tables`.`TABLE_SCHEMA` = 'properties');
```
