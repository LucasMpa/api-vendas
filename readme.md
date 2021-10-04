# Comandos Úteis

### Startando Contaienr

```
  docker start postgres
```

### Criando migrations

```
  yarn typeorm migration:create -n NomeDaMigration
```

### Revertendo migrations

```
yarn typeorm migration:revert
```

### Rodando migrations

```
  yarn typeorm migration:run
```

### Checklist ao criar uma nova coluna

[ ] - Startar docker

[ ] - Criar Migration

[ ] - Rodar Migration

[ ] - Criar Entidade

[ ] - Criar Repository

[ ] - Criar Services

[ ] - Criar Controller

[ ] - Criar Rotas
