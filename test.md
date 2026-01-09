---
kernelspec:
  name: python3
  display_name: Python 3
  language: python
---

# Test out rendering citations

## Added directly to the markdown file

:::{hint} Markdown
```markdown
Tropical rainforest [@kress2003checklist], Lowland evergreen rainforest [@connette2016mapping]
```
:::

:::{note} Output
Tropical rainforest [@kress2003checklist], Lowland evergreen rainforest [@connette2016mapping]
:::

## As the result of evaluating a variable

:::{hint} Markdown
````markdown
```{code-cell} python
:tags: [remove-input]
test_md = 'Tropical rainforest [@kress2003checklist], Lowland evergreen rainforest [@connette2016mapping]'
```

{eval}`test_md`
````
:::

```{code-cell} python
:tags: [remove-input]
test_md = 'Tropical rainforest [@kress2003checklist], Lowland evergreen rainforest [@connette2016mapping]'
```

:::{error} Output
{eval}`test_md`
:::