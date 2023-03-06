# Development


## Conda environment

Create the environment:

```
conda env create
# Faster: mamba env create
```

Activate it:

```
conda activate zhixing-website
```


### Locking

```
conda env export | grep -v "^prefix: " > environment-lock.yml
```


## Creating new content

_TODO_


### Preview your changes

From the `content/` directory:

```
quarto preview
```
