The numfig.py and numsec.py Sphinx Extensions
===============================================

I found that these two extensions were useful in writing Sphinx documentation with numbered figures and sections. 
To use these extensions, copy these two files into the source/ext directory of your Sphinx documentation project. You can create an empty project with the *sphinx-quickstart* command if you don't have one already. 

Then edit your source/conf.py to include these two extensions. Here is the extensions from my conf.py. These can be found near the top of your conf.py file. 

	extensions = ['sphinx.ext.todo','sphinx.ext.imgmath', 'numfig', 'numsec']
	imgmath_latex = '/Library/TeX/texbin/latex'
	imgmath_dvipng = '/Library/TeX/texbin/dvipng'

I use anaconda as my version of Python since that includes sphinx among many other packages. However, any Python3 distribution should work. You can pip install the sphinx package if necessary.

Happy writing!
