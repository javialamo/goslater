Goslater
========

Free Google Translate API for romanized translations

``goslater`` provides you *free* python API to google  romanizedtranslation service by querying google translation website.

It is mainly a copy of goslate with minor changes to provide a romanized translation version, since I have find there is no way to get it in an official or unofficial way. It's also modified in order to made it work with goslate without interferences.

The author of goslate is ZHUO Qiang and you can obtain goslate here: https://bitbucket.org/zhuoqiang/goslate 


Usage
--

  import goslater
  gr = goslater.Goslater()
  print gr.translate('hello world', 'zh')
  Nǐ hǎo shìjiè

 
Install
--

Just download `latest goslater.py <https://github.com/javialamo/goslater/blob/master/goslater.py>`_ directly and use

`futures <https://pypi.python.org/pypi/futures>`_ is optional but recommended to install for best performance.


