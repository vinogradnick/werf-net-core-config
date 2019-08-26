### Инструкции для сборки проекта 

```bash
werf build --stages-storage :local
```

### Инструкции для сборки запуска проекта 

```bash
werf run --stages-storage :local --docker-options="-d --name nginx-server" nginx-server  &&
werf run --stages-storage :local --docker-options="-d --name netcore" netcore
```