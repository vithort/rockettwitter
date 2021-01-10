# rockettwitter

Iniciando com AdonisJS, um framework completo para NodeJS

# Referência

Link: [Iniciando com AdonisJS, um framework completo para NodeJS]('https://www.youtube.com/watch?v=aysgHRmzG3w')

# Instalar o Cli do Adonis

```npm
npm i --global @adonisjs/cli
```

# Iniciar Projeto

```npm
adonis new PROJETO --api-only
```

- `--api-only`: ignora a parte de Views do MVC

# Iniciando o Servidor

```npm
adonis serve --dev
```

- `--dev`: executa o server na porta 3333

# Instalar Postgres

```npm
npm i pg --save
```

# Executar Migrations

```npm
adonis migration:run
```

# Criar Controller

```npm
adonis make:controller Auth
```

# Referência

Link: [CRUD e relacionamentos no AdonisJS]('https://www.youtube.com/watch?v=ESIQ6gWV80Y')

# Criando Modelo Tweet

```npm
adonis make:model Tweet -m -c
```

- `-m`: cria o migration
- `-c`: cria o controller

# Executar Migrations

```npm
adonis migration:run
```

# Listar Rotas

```npm
adonis route:list
```
