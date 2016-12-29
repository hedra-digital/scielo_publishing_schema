.. _elemento-article-meta:

<article-meta>
==============

Aparece em:

  :ref:`elemento-front`

Ocorre:

  Uma vez


Contém os metadados do artigo, cujos elementos básicos são:

* :term:`DOI`;
* seção (de acordo com o sumário do periódico);
* título(s) do artigo;
* autor(es);
* afiliação e notas de autor ``*``;
* data de publicação;
* volume ``*``;
* número ``*``;
* paginação do artigo ``*``;
* resumo(s) ``*``;
* palavras-chave ``*``;
* histórico ``*``;
* indicação da licença de uso :term:`Creative Commons`;
* contagem de elementos ``*``; e
* dados de financiamento  ``*``.

.. note:: Os itens identificados com asterisco devem ser inseridos no :term:`documento` somente se aplicável.


.. {"reviewed_on": "20160728", "by": "gandhalf_thewhite@hotmail.com"}

LaTeX
-----



  .. code-block:: tex

% Defined at scielostyle.sty
\renewcommand{\articleidpubidtypedoi}[1]{#1}
\renewcommand{\volume}[1]{#1}
\renewcommand{\issue}[1]{#1}
\renewcommand{\fpage}[1]{#1}
\renewcommand{\lpage}[1]{#1}
\renewenvironment{articlemeta}{\begin{tcolorbox}[title=<article-meta>]}{\end{tcolorbox}}

		...

        % <article-meta>
        \begin{articlemeta}
        %      <article-id pub-id-type="doi">
              \articleidpubidtypedoi{10.1590/1677-3225v14n4a01}

        %      <article-categories> ...
        %      <title-group> ...
        %      <contrib-group> ...
        %      <author-notes> ...
        %      <pub-date> ...
        %      <volume>
                \volume{14}

        %      <issue>
                \issue{4}

        %      <fpage>
                \fpage{256}

        %      <lpage>
                \lpage{261}

        %      <history> ...
        %      <permissions> ...
        %      <abstract> ...
        %      <kwd-group> ...
        %      <counts> ...
        % </article-meta>
        \end{articlemeta}


.. {"reviewed_on": "20161224", "by": "jorge@hedra.com.br"}