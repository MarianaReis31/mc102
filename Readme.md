Caderno de Aulas de MC102 - Algoritmos e Programação de Computadores

## O que será necessário para utilizar o caderno:

Vocês vão precisar ter acesso a uma aplicação chamada \\textit{Terminal}.
Talvez seja a aplicação mais útil, porque vocês poderão usar o mesmo para
dizer ao seu computador que faça praticamente tudo o que vocês quiserem.
Usuários de Mac e Linux provavelmente estão familiarizados com este
aplicativo. No Windows isso é um pouco mais complicado, já que a Microsoft é
um tanto rebelde. Vocês podem instalar um emulador de terminal mais amigável
do que o \"Prompt de Comando\" ou mesmo o \"PowerShell\" que acompanham o
Windows. Eu sugiro instalar o [Git Bash](ttps://git-scm.com/downloads).
Durante a instalação, certifique-se de selecionar a opção \"Use Windows'
default console window\". Uma outra opção, recomendado principalmente para
quem quer iniciar no mundo Linux, é instalar o Shell Bash do Linux no Windows
através do subsistema Windows para o Linux, presente nas versões mais atuais
do Windows 10.
[Aqui](http://www.techtudo.com.br/dicas-e-tutoriais/noticia/2016/04/como-instalar-e-usar-o-shell-bash-do-linux-no-windows-10.html)
vocês encontrarão um dos muitos tutoriais de como fazer isto.

Para criar um programa, utilizamos um editor de texto para escrever o código
do programa (e.g., [Vim](http://www.vim.org/), [Atom](https://atom.io/)) ou
um IDE -- Ambiente de Desenvolvimento Integrado (e.g.,
[PyCharm](https://www.jetbrains.com/pycharm/),
[WingIDE](http://wingware.com/)) e um compilador/interpretador python. O
compilador é o que transforma o código em um programa executável.  O
interpretador é um programa que executa diretamente os comandos da linguagem.
Será preciso instalar o compilador/interpretador python da versão 3.  Vocês
poderão baixá-lo do site (https://www.python.org/downloads)

## Jupyter Notebook

Um dos avanços mais significativos na arena de computação científica está em
andamento com a explosão de interesse na tecnologia Jupyter (anteriormente,
IPython) Notebook. A publicação científica Nature apresentou recentemente um
artigo sobre os benefícios dos notebooks Jupyter para pesquisas científicas.
Jupyter Notebook nada mais é do que uma aplicação WEB de código aberto que
permite criar e compartilhar documentos que contenham código, equações,
visualizações e texto narrativo.

Vocês precisarão instalar o Jupyter Notebook e algumas extensões para poder
usar o material do curso. Depois de instalar o Python3, execute no terminal:

```sh
    "$ pip3 install jupyter\n",
    "$ pip3 install jupyter_contrib_nbextensions\n",
    "$ pip3 install tutormagic\n",
    "$ jupyter contrib nbextension install --user"
```

Para usar as extensões necessárias, você também precisará ativá-las. Para fazer
isso, você pode usar um subcomando Jupyter:

```sh
    "$ jupyter nbextension enable codefolding/main\n",
    "$ jupyter nbextension enable latex_envs/latex_envs\n",
    "$ jupyter nbextension enable python-markdown/main\n",
    "$ jupyter nbextension enable toc2/main"
```

Depois de instalar o Jupyter Notebook e as extensões em seu computador, você
está pronto para executar o servidor do notebook. Você pode iniciar o servidor
do notebook a partir da linha de comando (usando Terminal no Mac/Linux ou
prompt de comando no Windows) executando:

```sh
    "$ jupyter notebook"
```

Isso imprimirá algumas informações sobre o servidor do notebook em seu
terminal, incluindo o URL do aplicativo da Web (por padrão,
http://localhost:8888):

```sh
    "$ jupyter notebook\n",
    "[I 10:31:03.540 NotebookApp] Serving notebooks from local directory: /Users/marcio/Unicamp/MC102/Python/lectures\n",
    "[I 10:31:03.541 NotebookApp] 0 active kernels\n",
    "[I 10:31:03.541 NotebookApp] The Jupyter Notebook is running at:\n",
    "[I 10:31:03.541 NotebookApp] http://localhost:8888/?token=046cfa3064f0b118f56f6ef8859c4ab68d1d202d79445759\n",
    "[I 10:31:03.541 NotebookApp] Use Control-C to stop this server and shut down all kernels (twice to skip confirmation)."
```

Em seguida, abrirá seu navegador da Web padrão para este URL. Quando o notebook
abrir no seu navegador, você verá o Notebook Dashboard, que mostrará uma lista
dos cadernos, arquivos e subdiretórios no diretório onde o servidor do notebook
foi iniciado. Na maioria das vezes, você deseja iniciar um servidor de caderno
no diretório que contém os cadernos do curso MC102. Muitas vezes, este será o
seu diretório inicial.

## Extras

   - Livro \"Practical Vim, second edition - Edit Text at the Speed of Thought\" [The Pragmatic Bookshelf](https://pragprog.com/book/dnvim2/practical-vim-second-edition),
   - Videos de Derek Wyatt sobre o editor Vim no Vimeo [Derek Wyatt](https://vimeo.com/user1690209),
   - Livro (online) sobre o editor Atom [Atom Flight Manual](http://flight-manual.atom.io/),
   - YouTube Video \"Setting up a Python Development Environment in Atom\" [Corey Schafer](https://www.youtube.com/watch?v=DjEuROpsvp4)