# Dicas do terminal
Vou listar alguns comandos que estou aprendendo

- `cd` (navega entre pastas)

Exemplo para entrar em uma pasta:
```
cd nomeDaPasta
```

Exemplo par sair de uma pasta
```
cd ..
``` 

- mkdir (criar pasta)

Exemplo de como criar uma pasta
```
mkdir nomeDaPasta
```

# Dicas do Git

- `git init` (começar a seguir as pastas e arquivos de um projeto)

Esse comando utilizamos par começar um projeto no Git. Chamamos a pasta do projeto de repositório ou só repo.
Para usar ele, basta entrar na pasta do projeto e executar assim:
```
git init
```

- `git status` (informa o estado do repo)

Usando o comando acima você terá como resultado informações de como está o estado dos arquivos e pastas, na verdade você receberá informações apenas dos arquibos e pastas novos, removidos  ou alterados.

- `git add` (segue os arquvivos ou pastas no momento atual)

Com o comando `git status`você fica sabendo do rolê dos arquivos e pastas e com o com o `git add`você guarda esse momento dos arquivos e pastas para em seguida realizar o commmit (não lembra o que é commit? Vê abaixo)

Se você quer guardar o momento de todos os arquivos e pasta só executar o comenando abaixo:
```
git add .
```
Mas se você quer pegar apenas alguns arquivos, você pode deixar o comando mais direto dessa forma:
```
git add pasta/arquivo
```

- `git commit`(esse comando guarda o momento atual)

Com o `commit` não é mais necessário ficar criando pastas old ou com datas bizaras. Ele é o cara que guarda o mmento do seu repo. A parte legal é que você deve e pode informar uma mensagem junto com o momento atual para ficar mais fácil de achar esse estado se um pia precisar voltar nele. Exemplo:

```
git commit -m "Anotações go git até o commit""
```

- `git log` (lista de estados que guardamos `commit˜)

Com esse comando conseguimos ver todos os commit`s que já fizemos na vida do repo que você estiver. 




