Markdown対応
=================
SphinxはreStructuredTextだけでなくMarkdownも利用できます。
Markdownを利用できるにするにはrecommonmarkをインストールする必要があります。 ::

  pip install recommonmark

インストール後、conf.pyを下記のように修正することでMarkdownが利用可能なります。 ::

  extensions = ['recommonmark']

  source_suffix = {
    '.rst': 'restructuredtext',
    '.txt': 'markdown',
    '.md': 'markdown',
  }
