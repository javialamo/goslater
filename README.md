
Goslater: Free Google Translate API for romanized translations
##############################################################

.. contents:: :local:

``goslater`` provides you *free* python API to google translation service by querying google translation website.

It is mainly a copy of goslate with minor changes to provide a romanized translation version, since I have find there is no way to get it in an official or unofficial way.

The author of goslate is ZHUO Qiang and you can obtain goslate here: https://bitbucket.org/zhuoqiang/goslate 


Usage
======

.. sourcecode:: python

 >>> import goslater
 >>> gr = goslater.Goslater()
 >>> print gr.translate('hello world', 'zh')
 Nǐ hǎo shìjiè

 
Install
========

goslater support both Python2 and Python3. You could install it via:


.. sourcecode:: bash
  
  $ pip install goslate

 
Just download `latest goslateR.py <https://github.com/javialamo/goslater/goslater.py>`_ directly and use

`futures <https://pypi.python.org/pypi/futures>`_ is optional but recommended to install for best performance.


