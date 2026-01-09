---
kernelspec:
  name: python3
  display_name: Python 3
  language: python
---

**Renders as a citation when added directly to the markdown file:**

Tropical rainforest [@kress2003checklist], Lowland evergreen rainforest [@connette2016mapping]

**DOES NOT render as a citation when evaluating a variable:**

```{code-cell} python
:tags: [remove-input]
test_md = 'Tropical rainforest [@kress2003checklist], Lowland evergreen rainforest [@connette2016mapping]'
```

{eval}`test_md`