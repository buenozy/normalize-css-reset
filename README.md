# normalize.css

Uma alternativa moderna para redefinições de CSS

[![npm](https://img.shields.io/npm/v/normalize.css.svg?style=flat-square)](https://www.npmjs.com/package/normalize.css) [![licença](https://img.shields.io/npm/l/normalize.css.svg?style=flat-square)](https://github.com/necolas/normalize.css/blob/HEAD/LICENSE.md) [![registro de alterações](https://img.shields.io/badge/changelog-md-blue.svg?style=flat-square)](https://github.com/necolas/normalize.css/blob/HEAD/CHANGELOG.md) [![agitar](https://img.shields.io/badge/chat-gitter-blue.svg?style=flat-square)](https://gitter.im/necolas/normalize.css)

```
npm install --save normalize.css
```

### Repositório

[github.com/necolas/normalize.css](https://github.com/necolas/normalize.css)

### Pagina inicial

[necolas.github.io/normalize.css](https://necolas.github.io/normalize.css)



**CDN**

Veja https://yarnpkg.com/en/package/normalize.css

**Download**

Veja https://necolas.github.io/normalize.css/latest/normalize.css

## O que isso faz?

- Preserva padrões úteis, ao contrário de muitas redefinições de CSS.
- Normaliza estilos para uma ampla variedade de elementos.
- Corrige bugs e inconsistências comuns do navegador.
- Melhora a usabilidade com modificações sutis.
- Explica o que o código faz usando comentários detalhados.

## Suporte ao navegador

- cromada
- Borda
- Firefox ESR+
- Internet Explorer 10+
- Safári 8+
- Ópera

## Detalhes estendidos e problemas conhecidos

Detalhes adicionais e explicação das partes esotéricas do normalize.css.

#### `pre, code, kbd, samp`

O `font-family: monospace, monospace`hack corrige a herança e o dimensionamento do tamanho da fonte para texto pré-formatado. A duplicação de `monospace`é intencional. [Fonte](https://en.wikipedia.org/wiki/User:Davidgothberg/Test59) .

#### `sub, sup`

Normalmente, usar `sub`ou `sup`afeta a altura da caixa de linha do texto em todos os navegadores. [Fonte](https://gist.github.com/413930) .

#### `select`

Por padrão, o Chrome no OS X e o Safari no OS X permitem um estilo muito limitado de `select`, a menos que uma propriedade de borda seja definida. O peso da fonte padrão nos `optgroup` elementos não pode ser alterado com segurança no Chrome no OSX e no Safari no OS X.

#### `[type="checkbox"]`

É recomendável que você não estilize entradas de caixa de seleção e rádio, pois a implementação do Firefox não respeita tamanho de caixa, preenchimento ou largura.

#### `[type="number"]`

Certos valores de tamanho de fonte aplicados a entradas numéricas fazem com que o estilo do cursor do botão de diminuição mude de `default`para `text`.

#### `[type="search"]`

A entrada de pesquisa não é totalmente estilizável por padrão. No Chrome e Safari no OSX/iOS você não pode controlar `font`, `padding`, `border`, ou `background`. No Chrome e Safari no Windows você não pode controlar `border`corretamente. Ele será aplicado `border-width`, mas mostrará apenas uma cor de borda (que não pode ser controlada) para o 1px externo dessa borda. A aplicação `-webkit-appearance: textfield` aborda esses problemas sem remover os benefícios das entradas de pesquisa (por exemplo, mostrar pesquisas anteriores).

## Contribuindo

Por favor, leia as [diretrizes](https://github.com/necolas/normalize.css/blob/HEAD/CONTRIBUTING.md) de contribuição para tornar o processo de contribuição fácil e eficaz para todos os envolvidos.