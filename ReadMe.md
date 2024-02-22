# basic python template

## [Python Interactive window](https://code.visualstudio.com/docs/python/jupyter-support-py#_convert-jupyter-notebooks-to-python-code-fil)



### Jupyter like code cells

You define Jupyter-like code cells within Python code using a ```# %%``` comment:

```
# %%
msg = "Hello World"
print(msg)

# %%
msg = "Hello again"
print(msg)
```

When the Python extension detects a code cell, it adds Run Cell and Debug Cell CodeLens adornments. The first cell also includes Run Below and all subsequent cells include Run Above:

