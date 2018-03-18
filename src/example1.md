# Chapter {#sec:foochapter}
## Section {#sec:sectionlabel}
### Sub Section
#### Sub*2 Section

You can reference any Section: [@sec:sectionlabel]

You can suppress the prefix using [-@sec:foochapter]. This is useful when you want to name a chapter as Chapter [-@sec:foochapter], not [@sec:foochapter].

You can reference any label, even those that are in different files [@sec:barchapter]

#### Math Block
$$
  \begin{pmatrix}
    person_{1} \\
    person_{2} \\
    \vdots \\
    person_{n}
  \end{pmatrix}
  =
  \begin{pmatrix}
    1997 & 1 \\
    1943 & 0 \\
    \vdots  & \vdots \\
    year_{n} & genre_{n}
  \end{pmatrix}
$$ {#eq:mathblock}

or

$$
  p_{i|j} = \frac{exp(-|x_{i}-x_{j}|^2/2
  \sigma _{i}^2)}{\sum_{k\neq i}
  exp(-|x_{i}-x_{k}|^2/2 \sigma _{i}^2)},
$$ {#eq:simgauss}

You can reference the math block [@eq:mathblock] or [@eq:simgauss].

#### Table

|Object|Color|
|:---:|:---:|
|A|Blue|
|B|Yellow|
|C|Red|
:Table caption {#tbl:rep1}

You can reference the table [@tbl:rep1]

#### Text

foo bar foo bar foo bar foo bar foo bar foo bar foo bar foo bar foo bar foo bar foo bar foo bar foo bar foo bar foo bar foo bar foo bar foo bar foo bar foo bar

(jump two lines to create the next paragraph)

foo bar foo bar foo bar foo bar foo bar foo bar foo bar foo bar foo bar foo bar foo bar foo bar foo bar foo bar foo bar foo bar foo bar foo bar foo bar foo bar you can create a bulletslist:

* **bold foo**: foo bar foo bar;

* _italic foo_: foo bar foo bar;

* normal foo: foo bar foo bar.

#### Listing

```
foo bar foo bar
Repeat:
  Foo bar
  Foo bar
Foo
```
: captions {#lst:alg}

You can reference lists [@lst:alg]

#### Figures

To include figure save the image file in the "images/" directory and type

![captions](images/example.png){#fig:figure}

You can reference the figure [@fig:figure]

#### Citation

> _"bla bla bla bla bla bla bla bla"_

#### Link

[Our manual](https://github.com/luanguimaraesla/pandocker-blank)
