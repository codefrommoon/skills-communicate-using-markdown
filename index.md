# Learning the markdown langage for GitHub
## A header smaller than the big first

This is a paragraph maybe.\
Because the file is a _.md_ file (markdown), this file may appear enriched by markdown.

###### The _smallest_ of __header__ in italic

Above is the smallest title. Don't forget to had a __space__ before the title.</br>
</br>

## Add Header
We can had an title from `#` to `######`
```md
# My title in big letters
```
## Add Image
We can had an image :

```markdown
![An image representing Yaktocat, a github mascot](https://octodex.github.com/images/yaktocat.png)
```

Ex :</br>
![An image representing Yaktocat, a github mascot](https://octodex.github.com/images/yaktocat.png)</br>

## Add Code block
We can had code block for a choosen langage :

<pre>
```langage
mycode()
    {
        another_code...
    }
```
</pre>

Ex :

```python
# comment in python
import csv
df = os.open("mycsv.csv")
```

```c
#include <stdio>
int main()
{
    /* comment in C */
    int my_var = 18;
    return(0)
}
```

## Add Task List
We can had a task list, especially in body of __issue__ or __pull request__ : it had a progress bar !

```md
- [x] First task
- [ ] Second task
- [ ] Third task
```
Ex :
- [x] Mise en page (deja fait)
- [ ] Contenus, articles
- [ ] Bannières

## Add Link
We can had link like this :
```md
[Description](http://lien_url.com/page)
```
Ex : 
[Visit my page](https://github.com/codefrommoon)

## Mise page Image
We can had image with html tag :
```md
<img src=https://octodex.github.com/images/welcometocat.png alt=celebrate width=300 align=right>
```
Ex :
<img src=https://octodex.github.com/images/welcometocat.png alt=celebrate width=300 align=right>
Hey my text is at left side, and my image should be on the right side... At least i hope the text fill the left side automatically.

Et voila !

## Mise page HTML
We can had html tag :
Exemple with the footer page :
```md
<footer>

<!--
     html comment blabla
-->

<!-- Big line -->
---

&copy; 2025 Code From Moon &bull; Every day is a learning day &bull;
</footer>
```
<footer>

<!--
     html comment blabla
-->

<!-- Big line -->
---

&copy; 2025 Code From Moon &bull; Every day is a learning day &bull; [More Markdown](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax) &bull; [More more Markdown](https://github.github.com/gfm/)
</footer>


_Moon_
