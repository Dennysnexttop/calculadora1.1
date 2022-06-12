## Welcome to GitHub Pages

You can use the [editor on GitHub](https://github.com/Dennysnexttop/calculadora1.1/edit/gh-pages/index.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Mi codigo
# <abc Crea 2021> - <04/06/21>

import sys

n1 = 0
n2 = 0

menu = """
1.- Sumar
2.- Restar
3.- Multiplicar
4.- Dividir
5.- Potencia
6.- Raiz
9.- Salir
"""

def Sumar():
    print("Ingresa el primer sumando: ")
    n1 = float(input())
    print("Ingresa el segundo sumando: ")
    n2 = float(input())
    print("El resultado es: ", n1 + n2)

def Restar():
    print("Ingresa el minuendo: ")
    n1 = float(input())
    print("Ingresa el sustraendo: ")
    n2 = float(input())
    print("El resultado es: ", n1 - n2)

def Multiplicar():
    print("Ingresa el primer coeficiente: ")
    n1 = float(input())
    print("Ingresa el segundo coeficiente: ")
    n2 = float(input())
    print("El resultado es: ", n1 * n2)

def Dividir():
    print("Ingresa el dividendo: ")
    n1 = float(input())
    print("Ingresa el divisor: ")
    n2 = float(input())
    print("El resultado es: ", n1 / n2)

def Potencia():
    print("Ingresa la base: ")
    n1 = float(input())
    print("Ingrese el exponente: ")
    n2 = float(input())
    print("El resultado es: ",n1 ** n2)

def Raiz():
    print("Ingresa el radicando: ")
    n1 = float(input())
    print("Ingresa el indice: ")
    n2 = float(input())
    print("El resultado es: ", n1 ** (1/n2) )

print("Bienvenido, Calculadora Basica...")
while True:
    print(menu)
    opc = int(input())
    if opc == 1:
        Sumar()
    elif opc == 2:
        Restar()
    elif opc == 3:
        Multiplicar()
    elif opc == 4:
        Dividir()
    elif opc == 5:
        Potencia()
    elif opc == 6:
        Raiz()
    elif opc == 9:
        sys.exit()
    
## Codigo Python
### Calculadora

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[https://solo.to/dennysnexttop](url) and ![https://www.solbyte.com/blog/wp-content/uploads/desarrollo-web-a-medida.png](src)
```

For more details see [Basic writing and formatting syntax](https://docs.github.com/en/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/Dennysnexttop/calculadora1.1/settings/pages). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.
