一份面向软件开发人员的单页、单栏简历。它使用基本的LaTeX模板和字体，在尝试更新简历时提供易用性和安装。不同的部分都有明确的文档记录，并使用自定义命令来提供一致的格式。简历中的三个主要部分是教育、经验和项目。
### Motivation

我创建这个模板是因为在Google Docs上管理简历很难，而且更改任何格式都太难了，因为它必须在多个地方应用。

目前大多数可用的模板要么集中在两栏上，要么多页长，不适合招聘会或在线申请。
### Quick start

Get started quickly using [Overleaf](https://www.overleaf.com/latex/templates/software-engineer-resume/gqxmqsvsbdjf) template.

### Build using Docker

```sh
docker build -t latex .
docker run --rm -i -v "$PWD":/data latex pdflatex sourabh_bajaj_resume.tex
```

### Preview

![Resume Screenshot](/resume_preview.png)

### License

Format is MIT but all the data is owned by Sourabh Bajaj.
