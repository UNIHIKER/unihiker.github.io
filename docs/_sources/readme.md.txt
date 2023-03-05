
```bash
pip install sphinx sphinx-markdown-tables sphinx-rtd-theme recommonmark sphinx-autobuild

sphinx-quickstart

nano conf.py
    extensions = ['recommonmark','sphinx_markdown_tables']
    html_theme = 'sphinx_rtd_theme'

make html
make clean

sphinx-autobuild -b html ./ build/html

#https://www.codenong.com/88a32d94d700b33dc3ea/
```