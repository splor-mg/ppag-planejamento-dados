# PPAG Planejamento

## Pré-requisitos

Esse projeto utiliza Docker para gerenciamento das dependências. Para fazer _build_  da imagem execute:

```bash
docker build --tag ppag-planejamento .
```

## Uso

Para executar o container

```bash
docker run -it --rm --mount type=bind,source=$(PWD),target=/project ppag-planejamento bash
```

Uma vez dentro do container execute os comandos do make

```bash
make all
```
