[https://unihiker.github.io](https://unihiker.github.io)



```bash
pip install sphinx sphinx-markdown-tables sphinx-rtd-theme recommonmark sphinx-autobuild

sphinx-quickstart

nano conf.py
    extensions = ['recommonmark','sphinx_markdown_tables']
    html_theme = 'sphinx_rtd_theme'

make html
make clean

#https://www.codenong.com/88a32d94d700b33dc3ea/

#- build to docs
nano make.bat
    +:html
    +%SPHINXBUILD% -b html %SOURCEDIR% "docs" %SPHINXOPTS% %O%
    +goto end

#- generate .nojekyll:
nano conf.py
    +extensions = ['sphinx.ext.githubpages']


    
```
