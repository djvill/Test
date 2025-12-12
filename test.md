# Untitled


## Quarto

Quarto enables you to weave together content and executable code into a
finished document. To learn more about Quarto see <https://quarto.org>.

## Running Code

When you click the **Render** button a document will be generated that
includes both content and the output of embedded code. You can embed
code like this:

``` r
1 + 1
```

    [1] 2

You can add options to executable code like this

    [1] 4

The `echo: false` option disables the printing of code (only output is
displayed).

``` r
iris[iris$Sepal.Length > 7,]
```

|     | Sepal.Length | Sepal.Width | Petal.Length | Petal.Width | Species   |
|:----|-------------:|------------:|-------------:|------------:|:----------|
| 103 |          7.1 |         3.0 |          5.9 |         2.1 | virginica |
| 106 |          7.6 |         3.0 |          6.6 |         2.1 | virginica |
| 108 |          7.3 |         2.9 |          6.3 |         1.8 | virginica |
| 110 |          7.2 |         3.6 |          6.1 |         2.5 | virginica |
| 118 |          7.7 |         3.8 |          6.7 |         2.2 | virginica |
| 119 |          7.7 |         2.6 |          6.9 |         2.3 | virginica |
| 123 |          7.7 |         2.8 |          6.7 |         2.0 | virginica |
| 126 |          7.2 |         3.2 |          6.0 |         1.8 | virginica |
| 130 |          7.2 |         3.0 |          5.8 |         1.6 | virginica |
| 131 |          7.4 |         2.8 |          6.1 |         1.9 | virginica |
| 132 |          7.9 |         3.8 |          6.4 |         2.0 | virginica |
| 136 |          7.7 |         3.0 |          6.1 |         2.3 | virginica |


![](image/dammu.png)
