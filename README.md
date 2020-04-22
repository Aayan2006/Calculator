## Welcome to GitHub Pages

You can use the [editor on GitHub](https://github.com/Aayan2006/Calculator/edit/master/README.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/Aayan2006/Calculator/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.

<!DOCTYPE html>
<html>
    <head>
        <Title>Calculator</Title>
    </head>
    <body bgcolor= "#000000" text= "gold">
        <form name="calculator" >
        <input type="button" value="1" onClick="document.calculator.ans.value+='1'">
        <input type="button" value="2" onClick="document.calculator.ans.value+='2'">
        <input type="button" value="3" onClick="document.calculator.ans.value+='3'"><br>
        <input type="button" value="4" onClick="document.calculator.ans.value+='4'">
        <input type="button" value="5" onClick="document.calculator.ans.value+='5'">
        <input type="button" value="6" onClick="document.calculator.ans.value+='6'">
        <input type="button" value="7" onClick="document.calculator.ans.value+='7'"><br>
        <input type="button" value="8" onClick="document.calculator.ans.value+='8'">
        <input type="button" value="9" onClick="document.calculator.ans.value+='9'">
        <input type="button" value="-" onClick="document.calculator.ans.value+='-'">
        <input type="button" value="+" onClick="document.calculator.ans.value+='+'"><br>
        <input type="button" value="*" onClick="document.calculator.ans.value+='*'">
        <input type="button" value="/" onClick="document.calculator.ans.value+='/'">
        
        <input type="button" value="0" onClick="document.calculator.ans.value+='0'">
        <input type="reset" value="Reset">
        <input type="button" value="=" onClick="document.calculator.ans.value=eval(document.calculator.ans.value)">
        <br>Solution is <input type="textfield" name="ans" value="">
        </form>
    </body>
</html>
