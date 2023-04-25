# Passo a passo da versão
- 1 - npx create-nx-workspace@latest <Nome projeto>
- 2 - Escolher o y
- 3 - Ir no integrado
- 4 - Ir em App
- 5 - Pode se colocar yes ou no
- 6 - code <nomeRepo> -r //Para abrir um pasta na mesma
- 7 - ctrl + shift p
- 8 - library
- 9 - Escolher a library
- 10 - Colocar o nome da biblioteca
- 11 - Teste vai ser em jest
- 12 - Bundler tsc // bundler quem vai ser o que vai executar
- 13 - copiar o comando e digitar
- 14 - nx generate @nrwl/js:library <nome biblioteca> --unitTestRunner=jest --directory=user

## Criando o back end
- 15 - npx nx list //Lista de comando
- 16 - Achar a extensão @nrwl/express
- 17 - npm i -D @nrwl/express
- 18 - Ir em generate na extensão
- 19 - ir em @nrwl/express aplication
- 20 - colar o comando nx generate @nrwl/express:application back-end

## Criar um repo front-end
- 21 - npm i -D @nrwl/web
- 22 - Ir generate no web
- 23 - Escolher o @nrwl/web Aplication
- 24 - Colocar o nome copiar o comando e dar run
- 25 - Escolher webpack se aparecer

## Para saber mais
- 0 - crt + p nome da pata // Para encontrar a pasta mais facilmente 
- 0 - npx nx dep-graph // Para ver o grafico de dependencia
- npx nx generate @nrwl/js:library data-access --unitTestRunner=jest --directory=user
- npm i -D @nrwl/express
- npx nx generate @nrwl/express:application back-end
- npm i -D @nrwl/web
- npx nx generate @nrwl/web:application front-end

## Designe patters 
- É necessario criar interfaces abstratas e classes para utilizar a interface.
### Shared serve para arquivos compartilhado 
- npx nx generate @nwl/js:library data-acess --directory shared

## Curiosidades importantes
- Para utilizar os caminhos mapeados é necessário exportar no index.ts 
- Comando no start nx run-many --target serve --parallel
- provider.use(quem vai utilizar, quem vai implementar, o que ele depende)
