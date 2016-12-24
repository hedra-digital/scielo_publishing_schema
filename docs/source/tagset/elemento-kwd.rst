.. _elemento-kwd:

<kwd>
=====

Aparece em:

  :ref:`elemento-kwd-group`

Ocorre:

  Uma ou mais vezes


Elemento obrigatório dentro de :ref:`elemento-kwd-group` que identifica cada palavra-chave individualmente.

Exemplo:

.. code-block:: xml

    ...
    <article-meta>
        ...
        <kwd-group xml:lang="pt">
            <title>Palavras-chave</title>
            <kwd>Broncoscopia</kwd>
            <kwd>Curvas de fluxo-volume expiratório máximo</kwd>
            <kwd>sensibilidade e especificidade</kwd>
            <kwd>Neoplasias pulmonares</kwd>
        </kwd-group>
        <kwd-group xml:lang="en">
            <title>Keywords</title>
            <kwd>Bronchoscopy</kwd>
            <kwd>Maximal expiratory flow-volume curves</kwd>
            <kwd>Sensitivity and specificity</kwd>
            <kwd>Lung neoplasms</kwd>
        </kwd-group>
        ...
    </article-meta>
    ...


LaTeX
-----

  .. code-block:: tex
 
      % Defined at scielostyle.sty
      \renewcommand{\kwdgroupstyle}{\itshape}
      \renewcommand{\kwdgrouptitle}{Keywords:}
      \renewcommand{\kwdgrouptitlestyle}{\noindent\bfseries}
      \renewcommand{\kwdgroupbeforeskip}{\medskip}
      \renewcommand{\kwdgroup}[1]{{\kwdgroupbeforeskip
                                    \kwdgrouptitlestyle
                                    \kwdgrouptitle} 
                                    \kwdgroupstyle #1}
      ...
      \kwdgroup{Chagas disease, Quality of life, Health-related quality of life, Cardiomyopathy, Determining factors}
      ...

.. {"reviewed_on": "20161223", "by": "jorge@hedra.com.br"}

.. {"reviewed_on": "20160627", "by": "gandhalf_thewhite@hotmail.com"}
