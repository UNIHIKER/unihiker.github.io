
```bash
pip install sphinx sphinx-markdown-tables sphinx-rtd-theme recommonmark 

sphinx-quickstart

nano conf.py
    extensions = ['recommonmark','sphinx_markdown_tables']
    html_theme = 'sphinx_rtd_theme'

make html
make clean
```