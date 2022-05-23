# Comandos para geração da chave ssh windows

 Abrir o terminal e digitar o comando abaixo:

```sh
ssh-keygen -t ed25519 -C "meu@email.github"
```

Navegar ate o local da geração da chave: geralmente:

```sh
cd /c/Users/meuusuario/.ssh/
```

Digitar o comando :

```sh
cat id_chavegerada.pub
```


Copiar a chave gerada
Entrar no GitHub navegar até configurações/ ssh e keys
```sh
Add new ssh
```

### Colar a chave e confirmar o processo


