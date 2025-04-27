# Comandos para commit no GitHub

## 1. Inicializar o repositório Git
```bash
# Inicializa um novo repositório Git no diretório atual
git init
```

## 2. Configurar o repositório remoto
```bash
# Adiciona o repositório remoto com o nome 'origin'
git remote add origin https://github.com/fbiluoficial/ters44

# Se já existir um remote 'origin', use este comando para atualizar a URL
git remote set-url origin https://github.com/fbiluoficial/ters44
```

## 3. Adicionar arquivos ao stage
```bash
# Adiciona o arquivo index.html para ser commitado
git add index.html
```

## 4. Criar o commit
```bash
# Cria um commit com a mensagem especificada
git commit -m "Adiciona index.html inicial"
```

## 5. Enviar para o GitHub
```bash
# Renomeia a branch atual para 'main'
git branch -M main

# Faz o push para o GitHub e configura o tracking
git push -u origin main
```

## Observações
- Certifique-se de ter configurado seu usuário e email do Git antes de fazer commits
- Você precisará ter acesso ao repositório no GitHub para fazer o push
- Se for a primeira vez usando o Git no computador, você precisará autenticar com o GitHub