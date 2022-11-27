# find *script*

**pt-BR** ⚡ Ferramenta de busca em layers de texto do After Effects ⚡

<br/>

# 📟 Interface
![busca](/images/busca.png)

---
  
  <br/>

## 🔎 Busca
Basta digitar o termo a ser buscado e pressionar *'ENTER'* ou clicar no ícone da lupa 🔎.
> A busca varrerá todas as composições do projeto retornando os layers de texto que testam positivo para os parâmetros selecionados.\
A busca suporta múltiplos *'keyframes'* no *'Source Text'* e leva em consideração se a propriedade possui ou não uma expressão.\
Caso precise, utilize as opções a baixo para refinar a busca.

1. ### ![visibilidade](/images/checkBoxIcon.png)  **`visibilidade`**

    Inclui apenas layers visíveis no resultado da busca.

2. ### ![caixa de texto](/images/checkBoxIcon.png)  **`Tt`**

    Força a busca a respeitar letras maiúsculas e minúsculas.
    > Por padrão, buscar por **'UVA'**, **'Uva'** ou **'uva'** retornam o mesmo resultado.

3. ### ![acentuação](/images/checkBoxIcon.png)  **`àê`**

    Força a busca a respeitar acentuação.
    > por padrão, buscar por **'você'** ou **'voce'** retornam o mesmo resultado.

4. ### ![inverter](/images/checkBoxIcon.png)  **`!=`**

    Retorna todos os resultados que **NÃO CONTÉM** o termo buscado.

5. ### ![regExp](/images/checkBoxIcon.png)  **`RegExp`**

    Habilita o uso de [Regular Expressions](https://www.w3schools.com/jsref/jsref_obj_regexp.asp).
    > ex: **'[0-9]'** retorna todos os textos que contém números.\
    > ex: **'\n|\r'** retorna todos os textos que contém mais de 1 linha.\
    > ex: **'\s{2,}'** retorna todos os textos que contém 2 ou mais espaços consecutivos.\

## 📑 Resultados

Os resultados são exibidos na seção inferior da janela.

![busca](/images/resultados.png)

A seção dos resultados contém:
- A **'composição'** em que o layer de texto está contido.
- Os layers de texto.

> Ao selecionar um item do resultado, ele será aberto e selecionado no *'Composition Viewer'*.