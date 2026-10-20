# cursorgen

Gerador simples de arquivos Xcursor em C.

## Estrutura do Projeto

```text
.
├── Makefile
├── README.md
└── src/
    └── main.c
```

## Pré-requisitos

- Compilador C (`clang` ou `gcc`)
- `make`

## Como Compilar e Executar

### Compilar o projeto

```bash
make
```

O binário será gerado em `bin/cursorgen`.

### Compilar e executar

```bash
make run
```

Para passar argumentos de linha de comando ao executar via `make`:

```bash
make run ARGS="arg1 arg2"
```

Ou execute o binário diretamente:

```bash
./bin/cursorgen
```

### Limpar arquivos de build

Remove os diretórios `build/` e `bin/`:

```bash
make clean
```
