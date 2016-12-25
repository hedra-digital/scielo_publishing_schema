.. _elemento-date:

<date>
======

Aparece em:

  :ref:`elemento-history`

Atributos obrigatórios:

  1. ``@date-type``

Ocorre:

  Uma ou mais vezes


``<date>`` deve conter obrigatoriamente o elemento :ref:`elemento-year`. Usa-se o atributo ``@date-type`` para especificar o tipo da ação envolvida.

Os valores possíveis para o atributo ``@date-type`` são:

+------------+------------+
| Valor      | Descrição  |
+============+============+
| received   | recebido   |
+------------+------------+
| accepted   | aceito     |
+------------+------------+
| rev-recd   | revisado   |
+------------+------------+

Exemplo:

.. code-block:: xml

    ...
    <article-meta>
        ...
        <history>
            <date date-type="received">
                <day>15</day>
                <month>03</month>
                <year>2013</year>
            </date>
            <date date-type="rev-recd">
                <day>06</day>
                <month>11</month>
                <year>2013</year>
            </date>
            <date date-type="accepted">
                <day>12</day>
                <month>05</month>
                <year>2014</year>
            </date>
        </history>
        ...
    </article-meta>
    ...


.. {"reviewed_on": "20160623", "by": "gandhalf_thewhite@hotmail.com"}

LaTeX
-----

  .. code-block:: tex

      ...
 
      % Defined at scielostyle.sty
       \renewcommand{\xmldatestyle}{\color{out}\bfseries}
       \RenewDocumentCommand{\xmldate}{ O{} O{} O{} m }{{\xmldatestyle%
                               \ifx#1\relax\else #1-\fi % <day> (non mandatory)
                               \ifx#2\relax\else #2-\fi    % <month> (non mandatory)
                               #4    % <year>
                               \ifx#3\relax\else (#3)\fi}}  % <date date-type="received"> (non mandatory)

      ...

      \xmldate{2015}                % year

      \xmldate[12]{2015}            % month-year

      \xmldate[12][25]{2015}        % day-month-year

      \xmldate[][][received]{2015}  % year+@date-type
      ...

.. {"reviewed_on": "20161223", "by": "jorge@hedra.com.br"}


