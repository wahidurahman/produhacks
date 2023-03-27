# `Produhacks'

`null` 

### Installation

```bash
pip install git+https://github.com/wahidurahman/produhacks/.git
```

### Usage

> **NOTE:** 

```bash
$  <prompt>
```

For example:

```
$ please create a standard gitignore for a python package in the current directory

echo "# Byte-compiled / optimized / DLL files" >> .gitignore
echo "__pycache__/" >> .gitignore
echo "*.py[cod]" >> .gitignore
echo "*$py.class" >> .gitignore
echo "*.so" >> .gitignore
echo "*.egg-info/" >> .gitignore
echo "dist/" >> .gitignore
echo "build/" >> .gitignore
echo "pip-wheel-metadata/" >> .gitignore
echo "*.egg" >> .gitignore
echo "*.egg-info" >> .gitignore
echo ".eggs/" >> .gitignore


Creating a .gitignore file and adding rules to ignore various types of files and directories.
```

### Features

* If a script fails, `please` pipes stderr back into the LLM
to create a revised script. This is especially useful when a file
or dependency doesn't exist, etc.

* If the prompt isn't specific enough, `please` prompts the user for
extra information, which gets inserted into the script before it's run.

* `please` will print the command(s) being executed, and summarizes
the command(s) of the script in natural language after execution.



### Roadmap

* description

* null
* null
* null
