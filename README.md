# SauceDemo Robot

Projeto para testar entrar em uma página web, usando a ferramenta [RobotFramework](https://robotframework.org/).

## Ambiente

### [Python](https://www.python.org/)

Como linguagem de programação iremos usar Python na versão 3.12.

### [Poetry](https://python-poetry.org/)

Para gerenciar as dependências do projeto iremos usar Poetry.

### Ferramentas

#### Análise estática

Para análise estática dos códigos `.robot`, usaremos [Robocop](https://github.com/MarketSquare/robotframework-robocop).

```bash
robocop <diretório ou arquivo>
```

#### Formatação

Para formatação automática dos script `.robot`, usaremos [Robotidy](https://github.com/MarketSquare/robotframework-tidy).

```bash
robotidy <diretório ou arquivo>
```

#### Git

Para ajuda a padronizar mensagens de commit para no projeto.
Usaremos o [commitizen](https://github.com/commitizen-tools/commitizen).
Podendo gerar versões, changelog e até mesmo publicar para o pip.

Inicializar as configurações no projeto

```bash
cz init
```

Fazer commits

```bash
cz commit
```

#### Markdown

Para formatar usaremos o [mdformat](https://github.com/executablebooks/mdformat).

```bash
mdformat README.md 
```

Para verificar se a formatação está correta usaremos [pymarkdown](https://github.com/jackdewinter/pymarkdown).

```bash
pymarkdown scan README.md 
```
