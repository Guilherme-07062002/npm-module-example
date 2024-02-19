# Exemplo de módulo npm para teste

Este é um exemplo criado para compreender a criação de módulos globais no npm.

## Instalação

Para testar se o seu módulo global está funcionando na sua máquina execute o comando:

```bash
  npm install -g /home/<caminho_do_modulo>
```

Após isso execute os comandos definidos presentes em `bin` do package.json no seu terminal.

## Exemplo

Neste caso você poderá executar:

```bash
  my-module
```

E o resultado da execução desse comando será a criação de um arquivo de texto na pasta aonde ele foi executado.

Lembrando que ao instalar esse módulo globalmente, você poderá executar o comando `my-module` em qualquer diretório do seu sistema.
