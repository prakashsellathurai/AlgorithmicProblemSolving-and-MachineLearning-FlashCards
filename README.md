### Algorithmic ProblemSolving and MachineLearning FlashCards

<!-- toc -->

## Description:
Flashcards for concepts programming ,machine learning and Deep Learning
## Installation:
- Install [Ankit](https://apps.ankiweb.net/) and [Latex](https://www.latex-project.org/) in your machine properly

## Usage:
- add new  card type for latex with Header
 ```
 \documentclass[50pt]{article} 

\usepackage{amssymb,amsmath,amsfonts,mathrsfs, graphicx} 
\special{papersize=3in,5in}
\usepackage{amssymb,amsmath}
\pagestyle{empty}
\setlength{\parindent}{0in}
\newcommand{\indep}{\perp\!\!\!\perp}

\newcommand{\CI}{\mathrel{\text{\scalebox{1.07}{$\perp\mkern-10mu\perp$}}}}

\newcommand{\nCI}{\centernot{\CI}}
\begin{document} 
```
- update Front as
 ```
 [latex]\normalsize {{Front}}[/latex]
 ```
- update Back as 
```
[latex]\normalsize  {{Front}}[/latex]

<br /><br />
<hr id=answer>
<br />

[latex]\normalsize  {{Back}}[/latex] 

```

- All flash card decks are stored in .apkg format
- import them in ankit with latex card type you created 
- and start using it:}

## Credits:
- [jessicayung/machine-learning-flashcards](https://github.com/jessicayung/machine-learning-flashcards)
