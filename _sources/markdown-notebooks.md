---
jupytext:
  formats: md:myst
  text_representation:
    extension: .md
    format_name: myst
    format_version: 0.13
    jupytext_version: 1.11.5
kernelspec:
  display_name: Python 3
  language: python
  name: python3
---

# Markdown Notebook

Hier könnte ihre tolle Erklärung zu einem Thema stehe, wenn Sie `Code` erklären wollen oder $\text{mathe}$.

Eine Aufgabe, wenn wir es schaffen das *Exercise* verschwinden zu lassen.

:::{exercise} Aufgabe 1
:nonumber:
Sie können Sie können Befehle ausführen, indem Sie in einer Codezeile die gewünschte Eingabe laufen lassen. Nutzen Sie dazu den Knopf `x = A[:, 0]`.
:::

Und hier Plan B:

:::{admonition} Aufgabe 1
Sie können Sie können Befehle ausführen, indem Sie in einer Codezeile die gewünschte Eingabe laufen lassen. Nutzen Sie dazu den Knopf `x = A[:, 0]`.
:::

```{code-cell}
print(2 + 2)
```

:::{admonition} Hinweis
:class: note dropdown

Hier kann auch `Code` stehen oder auch ein bisschen Latex 

$$
\begin{aligned}
    \begin{pmatrix} 1 & 2 & 3 \end{pmatrix}
\end{aligned}
$$

:::

:::{admonition} Lösung
:class: tip dropdown

``` python
x = 0
for i in range(3,300):
    x + i

print(x)
```
:::

## Create a notebook with MyST Markdown

MyST Markdown notebooks are defined by two things:

1. YAML metadata that is needed to understand if / how it should convert text files to notebooks (including information about the kernel needed).
   See the YAML at the top of this page for example.
2. The presence of `{code-cell}` directives, which will be executed with your book.

That's all that is needed to get started!

## Quickly add YAML metadata for MyST Notebooks

If you have a markdown file and you'd like to quickly add YAML metadata to it, so that Jupyter Book will treat it as a MyST Markdown Notebook, run the following command:

```
jupyter-book myst init path/to/markdownfile.md
```
