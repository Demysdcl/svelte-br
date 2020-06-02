<p>
  <a href="https://svelte.dev">
	<img alt="Cybernetically enhanced web apps: Svelte" src="https://sveltejs.github.io/assets/banner.png">
  </a>

  <a href="https://www.npmjs.com/package/svelte">
    <img src="https://img.shields.io/npm/v/svelte.svg" alt="npm version">
  </a>

  <a href="https://github.com/sveltejs/svelte/blob/master/LICENSE">
    <img src="https://img.shields.io/npm/l/svelte.svg" alt="license">
  </a>
</p>


## O que é Svelte?

Svelte é uma nova forma de desenvolver aplicações web. É um compilador que converte seus componentes em um JavaScript eficiente que atualiza o DOM de forma precisa.

Saiba mais no [Website do Svelte](https://br.svelte.dev), ou na nossa [Comunidade no Discord](https://br.svelte.dev/chat).


## Desenvolvimento

*Pull requests* são bem-vindos e encorajados. [Escolha uma Issue](https://github.com/sveltejs/svelte/issues?q=is%3Aissue+is%3Aopen+sort%3Aupdated-desc) e ajude o projeto.

Para instalar e trabalhar com Svelte localmente:

```bash
git clone https://github.com/sveltejs/svelte.git
cd svelte
npm install
```

> Não use o Yarn para instalar as dependências, pois as versões especificadas no `package-lock.json` são usadas para criar e testar o Svelte.

Para compilar todos os modulos inclusos:

```bash
npm run build
```

Para rodar em modo de desenvolvimento e ficar observando todas as mudanças (isso é útil se você estiver usando o [link npm](https://docs.npmjs.com/cli/link.html) para testar localmente as alterações em um projeto):


```bash
npm run dev
```

O compilador é escrito em [TypeScript](https://www.typescriptlang.org/), mas não deixe isto te indimidar — É apenas JavaScript com tipagem. Você entenderá rápido. Se você utilizar outro editor diferente do [Visual Studio Code](https://code.visualstudio.com/), precisará instalar um plugin para que ele entenda a syntax e faça o highlight do código e dê sugestões.


### Running Tests

```bash
npm run test
```

Para filtrar os testes, use `-g` (como `--grep`). Por exemplo, para rodar testes envolvendo apenas transições:

```bash
npm run test -- -g transition
```


## br.svelte.dev

O código-fonte do http://br.svelte.dve, incluindo toda a documentação, encontra-se na pasta [site](site). O site é desenvolvido com [Sapper](https://sapper.svelte.dev). Para desenvolver localmente:

```bash
cd site
npm install && npm run update
npm run dev
```

### O br.svelte.dev caiu?

Provavelmente não, mas é possível. Se você não conseguir acessar nenhum site `.dev`, consulte este [FAQ](https://superuser.com/q/1413402).

## Licença

[MIT](LICENSE)
