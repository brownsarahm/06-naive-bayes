---
jupyter:
  jupytext:
    formats: ipynb,md
    text_representation:
      extension: .md
      format_name: markdown
      format_version: '1.2'
      jupytext_version: 1.6.0
  kernelspec:
    display_name: Python 3
    language: python
    name: python3
---



```python
import pandas as pd
import seaborn as sns
from sklearn.model_selection import train_test_split
from sklearn.naive_bayes import GaussianNB
```

# Dataset 1

```python
df1 = pd.read_csv('data/dataset1.csv')
sns.pairplot(data =df1, hue='char')
```


```python


```

```python

```

```python

```

# Dataset 2

```python
df2 = pd.read_csv('data/dataset2.csv')
sns.pairplot(data =df2, hue='char')
```

```python

```

```python

```

```python

```

# Dataset 3

```python
df3 = pd.read_csv('data/dataset3.csv')
sns.pairplot(data =df3, hue='char')
```

```python

```

```python

```

```python

```

# Dataset 4

```python
df4 = pd.read_csv('data/dataset4.csv')
sns.pairplot(data =df4, hue='char')
```

```python

```

```python

```

```python

```
