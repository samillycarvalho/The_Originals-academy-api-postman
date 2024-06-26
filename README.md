# Testes de Api com postman

Projeto de teste de api do Academy T11.

## Tecnologias utilizadas

- postman
- Git 
- Nodejs
- newman

### Instalando as dependencias
```bash
   npm install -g newman
  npm install -g newman-reporter-htmlextra

```

## Execução com Newman

```bash
 newman run users.json -e QA.json -g globals.json 

```
## Execução com htmlextra

```bash
 newman run users.json -e QA.json -g globals.json -r htmlextra

```
## Git e Github
No Git e Github, realize as etapas abaixo:
Clone o repositório
```bash
 git clone git@github.com:samillycarvalho/The_Originals-academy-api-postman.git

```
##### Verifique se há alterações no repositório git para baixar ao repositório local

```bash
 git pull

```
##### Traferindo arquivos do repositório local para o repositório do git
1 - adicionar todos os arquivos alterados
```bash
 git add .

```
2 - Colocar na área de "preparação do computador"
```bash
 git commit -d "nome ou descrição"
```
3 - Criar nome das versões
```bash
 git tag -a vx.x -m "Version x.x"
```
4 - Para carregar as alterações do Git
```bash
 git push
```        
## Projeto desenvolvido por:
- [@samillycarvalho](https://www.linkedin.com/in/s%C3%A2milly-carvalho-444638226/)
- [@TainaLourenco](https://www.linkedin.com/in/taina-louren%C3%A7o-costa-da-silva/)
- [@WalterJorge](https://www.linkedin.com/in/walter-jorge-5079915a/)
- [@EduardoNunes](https://www.linkedin.com/in/eduardonunesdossantos/)
### Tech lead
Luis Eduardo