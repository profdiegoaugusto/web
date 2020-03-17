# Github


## Antes de Começar 

* Instale o [Git](https://git-scm.com/)
* Crie uma nova conta no [Github](https://github.com/join)
* Abra a interface de linha de comando (Terminal) do seu Sistema Operacional:
    * **Windows**: *Command Prompt* ou *Powershell*
    * **Mac OS**: Terminal
    * **Linux**: Terminal

### Verifique a Instalação do Git

```bash
git --version
```

### Configure Suas Informações

```bash
git config --global user.name "Coloque o seu nome aqui"
git config --global user.email "email@exemplo.com"
```

A primeira coisa que você deve fazer após instalar o [Git](https://git-scm.com/) é configurar o seu nome de usuário e endereço de email. Isso é importante porque todo *commit* do Git usará essas informações para identificar você como autor dos arquivos. A opção `--global` serve para você fazer essa configuração apenas uma única vez, desta forma o Git sempre usará suas informações (e.g. nome e e-mail) de identificação para qualquer coisa que você fizer no sistema. Caso queira mudar seu nome ou email para um projeto específico, basta entrar na pasta do projeto e digitar o mesmo comando, porém, sem a opção `--global`.

```bash
git config user.name "Coloque o seu nome aqui"
git config user.email "email@exemplo.com"
```

#### Verifique Suas Configurações 

Se você quiser verificar suas configurações, use o comando abaixo:

```bash
git config --list
```

Ou verifique individualmente digitando o comando `git config <key>` onde `<key>` é o nome do atributo que deseja visualizar, por exemplo, caso queira visualizar seu e-mail cadastrado, use o comando abaixo:

```bash
git config user.name
```
