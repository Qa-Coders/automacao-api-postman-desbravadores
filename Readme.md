### Projeto de automação com Postman e Report com Newman

Projeto de automação com Postman.

## Instalação
```bash
    npm install -g newman
    npm install -g newman-reporter-htmlextra
```

## Execução com report html extra
```bash
    newman run signup.json -e env-automacao.json -g env-global.json
```