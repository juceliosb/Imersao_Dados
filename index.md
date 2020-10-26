# Imersão Dados
## 1 Primeira Análise em Dados de Educação
O que precisamos para começar a trabalhar com Ciências de Dados. Poderiamos instalar todos os softwares necessário para rodar em seu computador e uma boa interfaçe gráfica para plotagem de gráficos. Porém existe uma segunda opção que facilita muito a vida de todos, principalmente quem não tem um computador tão poderoso, onde podemos utilizar ferramentas que não irar ficar instaladas em seu computador, bastando somente ter um bom navegador e uma conta no Google para utilizar, uma dessas ferramentas se chamada **Colaboratory** mais popularmente conhecida como [Colab](https://colab.research.google.com/) que permite escrever código Python em seu navegador e criar varios notebooks.

### Dados
A base de dados exploratória é uma pequena parte dos dados do INEP ENEN 2019 que será encontrada nesse link [Microdados Enen 2019](https://github.com/alura-cursos/imersao-dados-2-2020/blob/master/MICRODADOS_ENEM_2019_SAMPLE_43278.csv), por limitações de hardwere na plataforma *Colab*. Logo ao iniciar usaremos uma biblioteca chamada pandas.
```bash
import pandas as pd
fonte = "https://github.com/alura-cursos/imersao-dados-2-2020/blob/master/MICRODADOS_ENEM_2019_SAMPLE_43278.csv?raw=true"
dados = pd.read_csv(fonte)
dados.head()

```
## 2 Análise Exploratória

You can use the [editor on GitHub](https://github.com/juceliosb/Imersao_Dados/edit/gh-pages/index.md) to maintain and preview the content for your website in Markdown files.

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

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/juceliosb/Imersao_Dados/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
