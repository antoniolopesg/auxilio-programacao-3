# Projeto de auxílio para Programação III
### Por usar **windows** em minha máquina tive bastante problemas para iniciar projetos em rails, por isso decidi criar esse esquema que utiliza docker para gerar e rodar minhas aplicações.
<br/>

Caso queira utilizar esse esquema os requisitos são:
  - Docker (recomendo usar o WSL2)
  - Docker-compose
  - Um terminal de sua preferência

## Começar

:warning: **Garanta que todos arquivos do diretório do projeto estão utilizando LF como [EOL](https://pt.wikipedia.org/wiki/Nova_linha)**

Clone o repositório:
```
git clone https://github.com/antoniolopesg/auxilio-programacao-3.git
```

No diretório do projeto gere o projeto no container:
```
docker-compose run --no-deps web rails new . --force --database=mysql
```

🔧 Tem alguma dica para o projeto ou encontrou algum problema ?
 **Faça uma issue**
