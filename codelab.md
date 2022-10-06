# Workshop

## Step 1
Duration: 0:02:00

Are you trying to create easy to use, visually appealing content for the tech community? This CodeLab will show you how to quickly create your own Google CodeLab just like the one you're using right now. 
When creating a Codelab you have two authoring options: 
1. Using a Google Doc
1. Using a markdown file

## Code embedding
Duration: 0:03:00

No language set
```
function fibLike(one, two, length) {
  const result = [one, two];
  for (let i = 2; i < length; i++) {
    result.push(result[result.length - 1] + result[result.length - 2]);
  }
  return result;
}

```

JavaScript (js)
```js
function fibLike(one, two, length) {
  const result = [one, two];
  for (let i = 2; i < length; i++) {
    result.push(result[result.length - 1] + result[result.length - 2]);
  }
  return result;
}

```

iframe
<iframe width="100%" height="500px" src="https://stackblitz.com/edit/jfgreffier-coding-dojo-h73jcl?embed=1&file=src/roman-numerals/roman.js&hideExplorer=1&view=editor"></iframe>
