# Documentação POS Digital
## Introdução

O objetivo deste documento é apresentar tecnicamente como integrar aplicativos Android com a plataforma de pagamento da GETNET, assim como, requisitos de software e hardware, boas práticas de desenvolvimento e a forma de submeter o aplicativo para certificação e publicação.

Essa especificação pode ser alterada no futuro e a Getnet poderá solicitar que o aplicativo seja adaptado, principalmente com o surgimento de novos hardwares.

Juntamente com este documento, você terá acesso também aos arquivos abaixo:

```Rebatedor.apk```: aplicativo que simula as chamadas (deeplinks) de pagamento.

```Getnet_service```: é o serviço do SDK que fica rodando no terminal que se comunica com os recursos de hardware;

```Libposdigital```: é a interface do SDK que deve ser compilado com o seu app para se comunicar com o serviço

```Devkit```: é um app de ajuda que acessa os serviços e tem alguns exemplos. Com ele, você consegue validar se os serviços de hardware estão funcionando corretamente.

![image] https://github.com/leonardogiovelli/leonardogiovelli.github.io/blob/master/gpos700front.png

You can use the [editor on GitHub](https://github.com/leonardogiovelli/leonardogiovelli.github.io/edit/master/README.md) to maintain and preview the content for your website in Markdown files.

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

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/leonardogiovelli/leonardogiovelli.github.io/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
