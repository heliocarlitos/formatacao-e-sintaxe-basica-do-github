# Introdução
Quando eu comecei a usar o GitHub tinha muita dificuldade em formatar e organizar melhor os meus README, mas depois de algumas pesquisas eu descobri como fazer isso, e para que você não sofra como eu, decidi fazer essa pequena documentação para ti guiar a personalizar os seu README.

<details>

<summary> Índice </summary> 

- <a href='#1-como-adicionar-t%C3%ADtulos'>1. Como adicionar títulos</a>

- <a href='#2-como-formatar-textos'>2. Como formatar textos</a>

- <a href='#3-como-adicionar-listas'>3. Como Adicionar Listas</a>

- <a href='#4-como-adicionar-links'>4. Como Adicionar Links</a>

- <a href='#5-como-adicionar-uma-imagem-adequada-para-os-visitantes'>5. Como Adicionar Uma Imagem Adequada Para os Visitantes</a>

- <a href='#6-como-adicionar-texto-de-refer%C3%AAncia'>6. Como adicionar Texto de Referência</a>

- <a href='#7-como-citar-c%C3%B3digo'>7. Como Citar Código</a>

- <a href='#8-como-adicionar-c%C3%B3digo'>8. Como Adicionar Código</a>

- <a href='#9-como-adicionar-alertas-ou-notas'>9. Como Adicionar Alertas ou Notas</a>

- <a href='=#10-como-ocultar-o-conte%C3%BAdo-com-coment%C3%A1rios'>10. Como Ocultar o conteúdo com comentários</a>

- <a href='#11-como-criar-uma-tabela'>11. Como Criar Uma Tabela</a>

- <a href='#12-como-adicionar-uma-sec%C3%A7%C3%A3o-recolhida'>12. Como Adicionar Uma Secção Recolhida</a>

- <a href='#13-como-adicionar-bot%C3%B5es-de-linguagens'>13. Como Adicionar Botões de Linguagens</a>

</details>


##

<div align='center'>

### <a href='#fundo'>Ir ao Fundo</a>
  
</div>

##

## 1. Como adicionar títulos
Os títos são categorizados em três categorias, **Primário**, **Secundário** e **Terceário**. Para usar os títulos você deve adicionar um cardinal/jogo da velha `#` no início da linha seguido por um espaço.

- **a) Primário**:
  
Apenas um cardinal/jogo da velha `#`

Escrita:
```
# Seu Título Primário
```
Resultado:
# Seu Título Primário

- **b) Secundário**:
  
Apenas dois cardinal/jogo da velha `##`

Escrita:
```
## Seu Título Secundário
```
Resultado:
## Seu Título Secundário

- **c) Terceário**:
  
Apenas três cardinal/jogo da velha `###`

Escrita:
```
### Seu Título Terceário
```
Resultado:

### Seu Título Terceário

##

> [!NOTE]
> Repare que o número de cardinais/jogo da velha define o tamanho/importância do título, quanto mais cardinal/jogo da velha tiver o título será menenor ou menos inportante.

##

<div align='center'>

### <a href='#introdu%C3%A7%C3%A3o'>Ir ao topo</a>
  
</div>

##

## 2. Como Formatar Textos

| Estilo  |     Código           |          Escrita         |        Resultado          |
|  :---:  |      :---:           |           :---:          |        :---:         |
| Negrito |  `** **` ou `__ __`  |  `**Texto em Negrito**`  | **Texto em Negrito** |
| Itálico |  `* *` ou `_ _`      |  `_Texto em Itálico_`    | _Texto em Itálico_   |
| Riscado |  `~~ ~~`             |  `~~Texto em Riscado~~`  | ~~Texto em Riscado~~ |
| Sup     |  `<sup> </sup>`      |  `Texto <sup>sup</sup>`  | Texto <sup>sup</sup> |
| Sub     |  `<sub> </sub>`      |  `Texto <sub>sup</sub>`  | Texto <sub>sub</sub> |

<br/>

> Você também pode fazer combinações.

Exemplo
| Estilo            |     Código           |          Escrita                      |        Resultado                   |
|  :---:            |      :---:           |           :---:                       |        :---:                       |
| Negrito e Itálico |  `** **` e `_ _`     |  `**_Texto em Negrito e Itálico_**`   | **_Texto em Negrito e Itálico_**   |
| Negrito e Riscado |  `** **` e `~~ ~~`   |  `**~~Texto em Negrito e Riscado~~**` | **~~Texto em Negrito e Riscado~~** |
| Itálico e Riscado |  `* *` e `~~ ~~`     |  `*~~Texto em Itálico e Riscado~~*`   | *~~Texto em Itálico e Riscado~~*   |
| Riscado e Negrito |  `~~ ~~` e `** **`   |  `~~**Texto Riscado e Negrito**~~*`   | ~~**Texto Riscado e Negrito**~~*   |

<br/>

## Como Alinhar Texto, Imagens ou GIF

Para alinha qualquer conteúdo à esquerda, no centro ou à direita você deve adicionar o seu conteúdo dentro da tag `<div>` do HTML com a propriedade do CSS `align` e o valor `left` para esquerda. `center` para centralizar e `right` para direita.

### - Alinhando à Esquerda

Escrita:

```
<div align='left'>

Este é um exemplo de um texto alinhado à esquerda

</div>
```

Resultado:

<div align='left'>

Este é um exemplo de um texto alinhado à esquerda

</div>

### - Alinhando no Centro

  Escrita:

```
<div align='center'>

Este é um exemplo de um texto alinhado no Centro

</div>
```

Resultado:

<div align='center'>

Este é um exemplo de um texto alinhado no Centro

</div>  

### - Alinhando à Direita

  Escrita:

```
<div align='right'>

Este é um exemplo de um texto alinhado à Direita

</div>
```

Resultado:

<div align='right'>

Este é um exemplo de um texto alinhado à Direita

</div>  

> [!NOTE]
> Lembrando que você pode alinhar qualquer tipo de conteúdo (textos, imagens e GIF) desde que estejam dentro da `<div> </div>` e use a propriedade `align` com o seu respectivo valor `left`
, `center` ou `right`

<br/>

## Como fazer quebra de linha

Para fazer quebra de linhas você só precisa adicionar a tag do HTML `<br/>` onde quer passar passar para nova linha.

Escrita:
```
Aqui o texto foi <br/> quebrado uma vesz
```
Resultado:

Aqui o texto foi <br/> quebrado uma vesz

<br/>

Se você deseja quebrar a linha mais de uma vez é só repetira várias vezes a tag `<br/>`

Escrita:

```
Aqui o texto foi <br/> <br/> quebrado duas vezes.
```

Resultado:

Aqui o texto foi <br/> <br/> quebrado duas vezes.

>  Ao adicionarmos dois `<br/>`, a primeira vez o texto pulou para nova linha, ao adicionar o segundo `<br/>` é adicionada uma linha em branco.

##

<div align='center'>

### <a href='#introdu%C3%A7%C3%A3o'>Ir ao topo</a>
  
</div>

##

## 3. Como Adicionar Listas
**a) Lista Normal**

Para fazer a uma lista de ítens você pode usar os seguintes sinais: hífen `-` , asterisco  `*` ou sinal de mais `+`.

Escrita:
```
- Hélio
* Carlitos
+ António
```

Resultado:
- Hélio
* Carlitos
+ António
  
**b) Lista Ordenada**

Para ordenar a lista, coloque um número na frente de cada linha.

Escrita:
```
1. Hélio
1. Carlitos
1. António
```

Resultado:
1. Hélio
1. Carlitos
1. António

**c) Listas aninhadas**

Escrita:
```
1. Nomes
   - Hélio
     - Carlitos
       - António
```
> [!NOTE]
> Respeitando as identções.

Resultado:
1. Nomes
   - Hélio
     - Carlitos
       - António
    
**d) Lista de tarefas**

Para criar uma lista de tarefas, coloque um hífen e um espaço seguidos de [ ] antes dos itens de lista. Para marcar uma tarefa como concluída, use [x].

Escrita:
```
- [x] Pão
- [ ] Alface
- [ ] Tomate :tada:
```

Resultado:
- [x] Pão
- [ ] Alface
- [ ] Tomate :tada:


Se a descrição de um item da lista de tarefas começar com parênteses (carater especial), você precisará fazer escape dele com 

Escrita:
```
- [ ] \(Optional) Open a followup issue
```

Resultado:

- [ ] \(Optional) Open a followup issue


##

<div align='center'>

### <a href='#introdu%C3%A7%C3%A3o'>Ir ao topo</a>
  
</div>

##

<span id='links'></span>

## 4. Como Adicionar Links

Para adicionar um link você deve adicionar o texto do link entre parenteses rectos e o link entre parenteses curvos.

Escrita:
```
[GitHub Hélio Carlitos](https://github.com/heliocarlitos/)
```

Resulatado:

[GitHub Hélio Carlitos](https://github.com/heliocarlitos/)

Você também pode adicionar um texto antes do texto do link.

Escrita:
```
Para acessar o meu perfil, click [aqui](https://github.com/heliocarlitos/)
```

Resultado:

Para acessar o meu perfil, click [aqui](https://github.com/heliocarlitos/)


Se deseja adicionar um link em uma imagem você deve usar a tag de links do HTML `<a>` e a taga de imagens `<img>`

Escrita:

```
<a href="ADICIONA-SEU-LINK-AQUI" target="_blank"><img src='ADICIONA-O-LINK-DA-IMAGEM-AQUI'/></a>
```

Resultado:

<a href="javascript:void(0)" target="_blank"><img src='https://github.com/heliocarlitos/formatacao-e-sintaxe-basica-do-github/blob/main/Imagens/demo%20btn.png?raw=true'/></a>

> Para o meu exemplo eu usei um link de uma imagem de um botão. Sem nenhum direccionamento para quando for clicado.

##

<div align='center'>

### <a href='#introdu%C3%A7%C3%A3o'>Ir ao topo</a>
  
</div>

##

## 5. Como Adicionar Uma Imagem Adequada Para os Visitantes

Você pode incluir imagens em sua comunicação no GitHub. Aqui, você adicionará uma imagem responsiva, como uma faixa, à parte superior do LEIAME do perfil.

Usando o elemento HTML `<picture>` com o recurso de mídia `prefers-color-scheme`, você pode adicionar uma imagem que muda de acordo com o modo claro ou escuro usado pelo visitante. Para obter mais informações.

Escrita:

```
<picture>
     <source media="(prefers-color-scheme: dark)" srcset="YOUR-DARKMODE-IMAGE">
     <source media="(prefers-color-scheme: light)" srcset="YOUR-LIGHTMODE-IMAGE">
     <img alt="YOUR-ALT-TEXT" src="YOUR-DEFAULT-IMAGE">
</picture>
```

Substitua os espaços reservados na marcação pelas URLs das imagens escolhidas. Como alternativa, para experimentar o recurso primeiro, copie as URLs do exemplo abaixo.

- Substitua `YOUR-DARKMODE-IMAGE` pela URL de uma imagem a ser exibida para visitantes que usam o modo escuro.
- Substitua `YOUR-LIGHTMODE-IMAGE` pela URL de uma imagem a ser exibida para visitantes que usam o modo claro.
- Substitua `YOUR-DEFAULT-IMAGE` pela URL de uma imagem a ser exibida caso nenhuma das outras imagens seja correspondida, por exemplo, se o visitante estiver usando um navegador sem suporte ao recurso prefers-color-scheme.
- 
Para tornar a imagem acessível a visitantes que estejam usando um leitor de tela, substitua `YOUR-ALT-TEXT` por uma descrição da imagem.

Resultado:

<div align='center'>
  
<picture>
    <source media="(prefers-color-scheme: dark)" srcset="[YOUR-DARKMODE-IMAGE](https://github.com/heliocarlitos/formatacao-e-sintaxe-basica-do-github/blob/main/Imagens/demo%20img%20pc.png?raw=true)">
    <source media="(prefers-color-scheme: light)" srcset="[YOUR-LIGHTMODE-IMAGE](https://github.com/heliocarlitos/formatacao-e-sintaxe-basica-do-github/blob/main/Imagens/demo%20img%20pc.png?raw=true)">
    <img alt="Imagem de PC" src="https://github.com/heliocarlitos/formatacao-e-sintaxe-basica-do-github/blob/main/Imagens/demo%20img%20pc.png?raw=true">
</picture>

</div>

##

<div align='center'>

### <a href='#introdu%C3%A7%C3%A3o'>Ir ao topo</a>
  
</div>

##

## 6. Como adicionar Texto de Referência
Você pode citar um texto com `>` .

Escrita:

```
Isso não é uma nota.
> Seu texto de citação aqui.
```

Resultado:

Isso não é uma nota.
> Seu texto de citação aqui.

##

<div align='center'>

### <a href='#introdu%C3%A7%C3%A3o'>Ir ao topo</a>
  
</div>

##

## 7. Como Citar Código
Para citar um código você deve adicionar o código entre duas crases ( `` ).

Escrita:

```
Este é um exemplo de um código citado `<body></body>` essa é uma tag do HTML.
```
Resultado:

Este é um exemplo de um código citado `<body></body>` essa é uma tag do HTML.

##

<div align='center'>

### <a href='#introdu%C3%A7%C3%A3o'>Ir ao topo</a>
  
</div>

##

## 8. Como Adicionar Código

Para formatar código ou texto no próprio bloco distinto, use crases triplas ( ``` ).

Escrita:

````
```
<!doctype html>
<html>
<head>
    <meta charset="utf-8" />
    <meta name="viewport" content="width=device-width" />
    <title>Minha página de teste</title>
</head>
<body>
    <img src="images/firefox-icon.png" alt="minha página de teste" />
</body>
</html>
```
````

Resultado:

```
<!doctype html>
<html>
<head>
    <meta charset="utf-8" />
    <meta name="viewport" content="width=device-width" />
    <title>Minha página de teste</title>
</head>
<body>
    <img src="images/firefox-icon.png" alt="minha página de teste" />
</body>
</html>
```

Se deseja colorir o seu código use o tema `ruby` ou a extensão da linguagem, depois das primeiras três crases:

Escrita:

````
```html
    <!doctype html>
    <html>
    <head>
        <meta charset="utf-8" />
        <meta name="viewport" content="width=device-width" />
        <title>Minha página de teste</title>
    </head>
    <body>
        <img src="images/firefox-icon.png" alt="minha página de teste" />
    </body>
    </html>
```
````

Resultado:

```html
<!doctype html>
<html>
<head>
    <meta charset="utf-8" />
    <meta name="viewport" content="width=device-width" />
    <title>Minha página de teste</title>
</head>
<body>
    <img src="images/firefox-icon.png" alt="minha página de teste" />
</body>
</html>
```

##

<div align='center'>

### <a href='#introdu%C3%A7%C3%A3o'>Ir ao topo</a>
  
</div>

##

## 9. Como Adicionar Alertas ou Notas

Os alertas são uma extensão da sintaxe blockquote que você pode usar para enfatizar informações críticas. Em GitHub, eles são exibidos com cores e ícones distintos para indicar a importância do conteúdo. A sintaxe de alertas é compatível com:

- Discussões
- Gists
- Problemas
- Arquivos Markdown
- Solicitações pull
- Versões

O GitHub Recomenda restrições do uso de alertas a um ou dois por artigo para evitar sobrecarregar o leitor. As anotações consecutivas devem ser evitadas.

Há três tipos de alertas disponíveis. Você pode adicionar um alerta com uma linha de blockquote especial que especifica o tipo de alerta e, em seguida, adicionar as informações de alerta em um blockquote padrão imediatamente depois.

Escrita:

```
> [!NOTE]
> Adiciona aqui o seu texto de aviso informando alguma coisa.

> [!IMPORTANT]
> Adiciona aqui o seu texto de aviso informando alguma coisa.

> [!WARNING]
> Adiciona aqui o seu texto de aviso informando alguma coisa.
```

Resultado:

> [!NOTE]
> Adiciona aqui o seu texto de aviso informando alguma coisa.

> [!IMPORTANT]
> Adiciona aqui o seu texto de aviso informando alguma coisa.

> [!WARNING]
> Adiciona aqui o seu texto de aviso informando alguma coisa.

##

<div align='center'>

### <a href='#introdu%C3%A7%C3%A3o'>Ir ao topo</a>
  
</div>

##

## 10. Como Ocultar o conteúdo com comentários

Para ocultar um conteúdo ou código você deve adiciona-lo entre esse sinais `<!--` e `-->`

Escrita:

```
Esta palavra <!-- não --> será oculta o código <!--- HTML --> também será oculto.
```

Resultado:

Esta palavra <!-- não --> será oculta o código <!--- HTML --> também será oculto.

> Nota que a palavra "não" e "HTML" foram ocultos.

##

<div align='center'>

### <a href='#introdu%C3%A7%C3%A3o'>Ir ao topo</a>
  
</div>

##

## 11. Como Criar Uma Tabela

Você pode criar tabelas com pipes `|` e hífens `-`. Hifens são usados para criar o cabeçalho de cada coluna, enquanto as barras verticais separam cada coluna. Você deve incluir uma linha em branco antes da tabela para ela ser construída corretamente.

Escrita:

```
| Cabeçalho | Cabeçalho |
| --------- | --------- |
|   Texto   |   Texto   |
|   Texto   |   Texto   |
```

Resultado:

| Cabeçalho | Cabeçalho |
| --------- | --------- |
|   Texto   |   Texto   |
|   Texto   |   Texto   |

As barras verticais em cada extremo da tabela são opcionais.

As células podem ter largura variada e não precisam estar alinhadas perfeitamente com as colunas. Deve ter no mínimo três hifens em cada coluna da linha do cabeçalho.

Escrita:

```
| Cabeçalho     | Cabeçalho |
| ----- | ---
|   Texto       |   Texto   
|Texto   |   Texto   |
```

Resultado:

| Cabeçalho     | Cabeçalho |
| ----- | --- 
|   Texto       |   Texto   
|Texto   |   Texto   |

Você pode alinhar o texto à esquerda, à direita ou no centro de uma coluna incluindo dois pontos `:` à esquerda, direita ou nos dois lados dos hifens que estão dentro da linha de cabeçalho.

Escrita:

```
| Texto Alinhanho à Esquerda | Texto Centralizado | Texto Alinhanho à Direita |
|            :---            |         :---:      |            ---:           |
|            Texto           |         Texto      |           Texto           |
|            Texto           |         Texto      |           Texto           |
|            Texto           |         Texto      |           Texto           |
|            Texto           |         Texto      |           Texto           |
```

Resultado:

| Texto Alinhanho à Esquerda | Texto Centralizado | Texto Alinhanho à Direita |
|            :---            |         :---:      |            ---:           |
|            Texto           |         Texto      |           Texto           |
|            Texto           |         Texto      |           Texto           |
|            Texto           |         Texto      |           Texto           |
|            Texto           |         Texto      |           Texto           |

##

<div align='center'>

### <a href='#introdu%C3%A7%C3%A3o'>Ir ao topo</a>
  
</div>

##

## 12. Como Adicionar Uma Secção Recolhida

Você pode obscurecer temporariamente seções do seu Markdown criando uma seção expandida que o leitor pode optar por expandir. Por exemplo, quando você deseja incluir detalhes técnicos em um comentário do problema que pode não ser relevante ou interessante para todos os leitores, você pode colocar esses detalhes em uma seção recolhida.

Qualquer Markdown dentro do bloco `<details>` estará recolhido até que o leitor clique em  para expandir os detalhes.

No bloco `<details>`, use a marca `<summary>` para que os leitores saibam o que está dentro dele. O rótulo aparece à direita de ▶.

Escrita:

````
<details>

<summary>Dicas para seções recolhidas</summary>

### Você pode adicionar um título

Você pode adicionar texto em uma seção recolhida.

Você também pode adicionar uma imagem ou um bloco de código.

```ruby
   print("Olá Mundo")
```

</details>
````

Resultado:

<details>

<summary>Dicas para seções recolhidas</summary>

### Você pode adicionar um título

Você pode adicionar texto em uma seção recolhida.

Você também pode adicionar uma imagem ou um bloco de código.

```ruby
   print("Olá Mundo")
```

</details>

##

<div align='center'>

### <a href='#introdu%C3%A7%C3%A3o'>Ir ao topo</a>
  
</div>

##

## 13. Como adicionar Botões de Linguagens

**Asana**

Escrita:

```
![Asana](https://img.shields.io/badge/asana-E44C30?style=for-the-badge&logo=asana&logoColor=white)&nbsp;
```

Resulatado:

![Asana](https://img.shields.io/badge/asana-E44C30?style=for-the-badge&logo=asana&logoColor=white)&nbsp;

### [Ver todos markdown de badges...](https://github.com/hcadeveloper/markdown-badges/)

<p align='center'>
<a href='https://docs.github.com/' taget='_blanck'>Fonte da Documentação</a>
</p>

<a href='#' id='fundo'></a>
