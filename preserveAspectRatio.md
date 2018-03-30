# PreserveAspectRatio
Esse atributo preserva o tamanho da imagem de dentro do SVG, ele recebe alguns parâmetros.

```xml
<svg width="300" height="100" viewBox="0 0 600 200" preserveAspectRatio="none">
	...
<svg>
```

Caso esteja `none` e aumente o tamanho do SVG, a imagem de dentro irá esticar. Ele funciona de forma parecida que o `background-size`.

`xMin`, `xMid`, `xMax`… Diz em que ponto que vai começar a imagem. Usando com o `slice`. Cortando assim a imagem.

`YMin`, `YMid`, `YMax`… Diz em que ponto que vai terminar a imagem.
é referente a Top, middle e bottom.

[Exemple](https://github.com/nathpaiva/svg-study/blob/master/preserveAspectRatio.html)
