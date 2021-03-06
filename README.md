
==============================
SciELO Publishing Schema + TeX
==============================

This project is a SciELO Docs code fork. We plan to parse SPC, Jats and Bits XML Schemata to LaTeX, 
using pandoc and pandoc-jats.  

Bits, Jats and SPS tags to be described:


| BITS                            | JATS                            | SCIELO (SPS 1.5)                |
|---------------------------------|---------------------------------|---------------------------------|
| abbrev                        | abbrev                        |                                 |
|                                 | abbrev-journal-title          | abbrev-journal-title          |
| abstract                      | abstract                      | abstract                      |
|                                 | access-date                   |                                 |
| ack                           | ack                           | ack                           |
| addr-line                     | addr-line                     | addr-line                     |
| address                       | address                       |                                 |
| aff-alternatives              | aff-alternatives              |                                 |
| aff                           | aff                           | aff                           |
|                                 | ali:free_to_read              |                                 |
|                                 | ali:license_ref               |                                 |
| alt-text                      | alt-text                      |                                 |
| alt-title                     | alt-title                     |                                 |
| alternatives                  | alternatives                  |                                 |
| annotation                    | annotation                    |                                 |
| anonymous                     | anonymous                     |                                 |
| answer-set                    |                                 |                                 |
| answer                        |                                 |                                 |
| app-group                     | app-group                     |                                 |
| app                           | app                           | app                           |
| array                         | array                         |                                 |
|                                 | article                       | article                       |
|                                 | article-categories            | article-categories            |
|                                 | article-id                    | article-id                    |
|                                 | article-meta                  | article-meta                  |
| article-title                 | article-title                 | article-title                 |
| attrib                        | attrib                        | attrib                        |
| author-comment                | author-comment                |                                 |
| author-notes                  | author-notes                  | author-notes                  |
| award-group                   | award-group                   | award-group                   |
| award-id                      | award-id                      | award-id                      |
| back                          | back                          | back                          |
| bio                           | bio                           |                                 |
| body                          | body                          | body                          |
| bold                          | bold                          |                                 |
| book-back                     |                                 |                                 |
| book-body                     |                                 |                                 |
| book-id                       |                                 |                                 |
| book-meta                     |                                 |                                 |
| book-part-id                  |                                 |                                 |
| book-part-meta                |                                 |                                 |
| book-part-wrapper             |                                 |                                 |
| book-part                     |                                 |                                 |
| book-title-group              |                                 |                                 |
| book-title                    |                                 |                                 |
| book-volume-id                |                                 |                                 |
| book-volume-number            |                                 |                                 |
| book                          |                                 |                                 |
| boxed-text                    | boxed-text                    | boxed-text                    |
| break                         | break                         |                                 |
| caption                       | caption                       | caption                       |
| chapter-title                 | chapter-title                 | chapter-title                 |
| chem-struct-wrap              | chem-struct-wrap              |                                 |
| chem-struct                   | chem-struct                   |                                 |
| citation-alternatives         | citation-alternatives         |                                 |
|                                 | city                          |                                 |
| code                          | code                          |                                 |
| col                           | col                           |                                 |
| colgroup                      | colgroup                      |                                 |
| collab-alternatives           | collab-alternatives           |                                 |
| collab                        | collab                        | collab                        |
| collection-id                 |                                 |                                 |
| collection-meta               |                                 |                                 |
| comment                       | comment                       | comment                       |
| compound-kwd-part             | compound-kwd-part             |                                 |
| compound-kwd                  | compound-kwd                  |                                 |
| compound-subject-part         | compound-subject-part         |                                 |
| compound-subject              | compound-subject              |                                 |
| conf-acronym                  | conf-acronym                  |                                 |
| conf-date                     | conf-date                     | conf-date                     |
| conf-loc                      | conf-loc                      | conf-loc                      |
| conf-name                     | conf-name                     | conf-name                     |
| conf-num                      | conf-num                      |                                 |
| conf-sponsor                  | conf-sponsor                  |                                 |
| conf-theme                    | conf-theme                    |                                 |
| conference                    | conference                    |                                 |
| contrib-group                 | contrib-group                 | contrib-group                 |
| contrib-id                    | contrib-id                    | contrib-id                    |
| contrib                       | contrib                       | contrib                       |
| copyright-holder              | copyright-holder              | copyright-holder              |
| copyright-statement           | copyright-statement           | copyright-statement           |
| copyright-year                | copyright-year                | copyright-year                |
| corresp                       | corresp                       | corresp                       |
| count                         | count                         |                                 |
| country                       | country                       | country                       |
| counts                        | counts                        | counts                        |
| custom-meta-group             | custom-meta-group             |                                 |
| custom-meta                   | custom-meta                   |                                 |
| date-in-citation              | date-in-citation              | date-in-citation              |
|                                 | data-title                    |                                 |
| date                          | date                          | date                          |
| day                           | day                           | day                           |
| dedication                    |                                 |                                 |
| def-head                      | def-head                      |                                 |
| def-item                      | def-item                      |                                 |
| def-list                      | def-list                      | def-list                      |
| def                           | def                           |                                 |
| degrees                       | degrees                       |                                 |
| disp-formula-group            | disp-formula-group            |                                 |
| disp-formula                  | disp-formula                  | disp-formula                  |
| disp-quote                    | disp-quote                    | disp-quote                    |
| edition                       | edition                       | edition                       |
| element-citation              | element-citation              | element-citation              |
| elocation-id                  | elocation-id                  | elocation-id                  |
| email                         | email                         | email                         |
| equation-count                | equation-count                |                                 |
| era                           | era                           |                                 |
| etal                          | etal                          | etal                          |
| event-desc                    |                                 |                                 |
| event                         |                                 |                                 |
| explanation                   |                                 |                                 |
| ext-link                      | ext-link                      | ext-link                      |
| fax                           | fax                           |                                 |
| fig-count                     | fig-count                     |                                 |
| fig-group                     | fig-group                     | fn-group                      |
| fig                           | fig                           | fig                           |
| fixed-case                    | fixed-case                    |                                 |
| floats-group                  | floats-group                  |                                 |
| fn-group                      | fn-group                      |                                 |
| fn                            | fn                            | fn                            |
| foreword                      |                                 |                                 |
| fpage                         | fpage                         | fpage                         |
|                                 | front                         | front                         |
| front-matter-part             |                                 |                                 |
| front-matter                  |                                 |                                 |
|                                 | front-stub                    | front-stub                    |
| funding-group                 | funding-group                 | funding-group                 |
| funding-source                | funding-source                | funding-source                |
| funding-statement             | funding-statement             | funding-statement             |
| given-names                   | given-names                   | given-names                   |
| glossary                      | glossary                      | glossary                      |
| glyph-data                    | glyph-data                    |                                 |
| glyph-ref                     | glyph-ref                     |                                 |
| gov                           | gov                           |                                 |
| graphic                       | graphic                       |                                 |
|                                 | history                       | history                       |
| hr                            | hr                            |                                 |
| index-div                     |                                 |                                 |
| index-entry                   |                                 |                                 |
| index-group                   |                                 |                                 |
| index-term-range-end          |                                 |                                 |
| index-term                    |                                 |                                 |
| index                         |                                 |                                 |
| inline-formula                | inline-formula                | inline-formula                |
| inline-graphic                | inline-graphic                | inline-graphic                |
| inline-supplementary-material | inline-supplementary-material | inline-supplementary-material |
| institution-id                | institution-id                |                                 |
| institution-wrap              | institution-wrap              |                                 |
| institution                   | institution                   | institution                   |
| isbn                          | isbn                          | isbn                          |
| issn-l                        | issn-l                        |                                 |
| issn                          | issn                          | issn                          |
| issue-id                      | issue-id                      |                                 |
| issue-part                    | issue-part                    |                                 |
| issue-sponsor                 | issue-sponsor                 | issue-sponsor                 |
| issue-title                   | issue-title                   |                                 |
| issue                         | issue                         | issue                         |
| italic                        | italic                        |                                 |
| journal-id                    | journal-id                    | journal-id                    |
|                                 | journal-meta                  | journal-meta                  |
|                                 | journal-subtitle              |                                 |
|                                 | journal-title                 | journal-title                 |
|                                 | journal-title-group           | journal-title-group           |
| kwd-group                     | kwd-group                     | kwd-group                     |
| kwd                           | kwd                           | kwd                           |
| label                         | label                         | label                         |
| license-p                     | license-p                     |                                 |
| license                       | license                       | license                       |
| list-item                     | list-item                     |                                 |
| list                          | list                          | list                          |
| long-desc                     | long-desc                     |                                 |
| lpage                         | lpage                         | lpage                         |
| media                         | media                         | media                         |
| meta-name                     | meta-name                     |                                 |
| meta-value                    | meta-value                    |                                 |
| milestone-end                 | milestone-end                 |                                 |
| milestone-start               | milestone-start               |                                 |
| mixed-citation                | mixed-citation                | mixed-citation                |
| mml:math                      | mml:math                      |                                 |
| monospace                     | monospace                     |                                 |
| month                         | month                         | month                         |
| name-alternatives             | name-alternatives             |                                 |
| name                          | name                          | name                          |
| named-book-part-body          |                                 |                                 |
| named-content                 | named-content                 | named-content                 |
| nav-pointer-group             |                                 |                                 |
| nav-pointer                   |                                 |                                 |
|                                 | nlm-citation                  |                                 |
| nested-kwd                    | nested-kwd                    |                                 |
| note                          | note                          |                                 |
| notes                         | notes                         |                                 |
| object-id                     | object-id                     |                                 |
| on-behalf-of                  | on-behalf-of                  | on-behalf-of                  |
| open-access                   | open-access                   |                                 |
| overline-end                  |                                 |                                 |
| overline-start                |                                 |                                 |
| overline                      | overline                      |                                 |
| p                             | p                             | p                             |
| page-count                    | page-count                    |                                 |
| page-range                    | page-range                    | page-range                    |
| part-title                    | part-title                    |                                 |
| patent                        | patent                        | patent                        |
| permissions                   | permissions                   | permissions                   |
| person-group                  | person-group                  | person-group                  |
| phone                         | phone                         |                                 |
|                                 | postal-code                   |                                 |
| preface                       |                                 |                                 |
| prefix                        | prefix                        | prefix                        |
| preformat                     | preformat                     |                                 |
| price                         | price                         |                                 |
| principal-award-recipient     | principal-award-recipient     |                                 |
| principal-investigator        | principal-investigator        |                                 |
| private-char                  | private-char                  |                                 |
| product                       | product                       | product                       |
| pub-date                      | pub-date                      | pub-date                      |
| pub-history                   |                                 |                                 |
| pub-id                        | pub-id                        | pub-id                        |
| publisher-loc                 | publisher-loc                 | publisher-loc                 |
| publisher-name                | publisher-name                | publisher-name                |
| publisher                     | publisher                     | publisher                     |
| question-wrap                 |                                 |                                 |
| question                      |                                 |                                 |
| rb                            | rb                            |                                 |
| ref-count                     | ref-count                     |                                 |
| ref-list                      | ref-list                      | ref-list                      |
| ref                           | ref                           | ref                           |
| related-article               | related-article               | related-article               |
| related-object                | related-object                |                                 |
|                                 | response                      | response                      |
| role                          | role                          | role                          |
| roman                         | roman                         |                                 |
| rp                            |                                 |                                 |
| rt                            | rt                            |                                 |
| ruby                          | ruby                          |                                 |
| sans-serif                    | sans-serif                    |                                 |
| sc                            | sc                            |                                 |
| season                        | season                        | season                        |
| sec-meta                      | sec-meta                      |                                 |
| sec                           | sec                           | sec                           |
| see-also-entry                |                                 |                                 |
| see-also                      |                                 |                                 |
| see-entry                     |                                 |                                 |
| see                           |                                 |                                 |
| self-uri                      | self-uri                      |                                 |
| series                        | series                        |                                 |
|                                 | series-text                   |                                 |
|                                 | series-title                  |                                 |
| sig-block                     | sig-block                     | sig-block                     |
| sig                           | sig                           |                                 |
| size                          | size                          | size                          |
| source                        | source                        | source                        |
| speaker                       | speaker                       |                                 |
| speech                        | speech                        |                                 |
|                                 | state                         |                                 |
| statement                     | statement                     |                                 |
| std-organization              | std-organization              |                                 |
| std                           | std                           |                                 |
| strike                        | strike                        |                                 |
| string-conf                   |                                 |                                 |
| string-date                   | string-date                   |                                 |
| string-name                   | string-name                   |                                 |
| styled-content                | styled-content                |                                 |
| sub                           | sub                           |                                 |
|                                 | sub-article                   | sub-article                   |
| subj-group                    | subj-group                    | subj-group                    |
| subject                       | subject                       |                                 |
| subtitle                      | subtitle                      |                                 |
| suffix                        | suffix                        | suffix                        |
| sup                           | sup                           |                                 |
| supplement                    | supplement                    |                                 |
| supplementary-material        | supplementary-material        | supplementary-material        |
| surname                       | surname                       | surname                       |
| table-count                   | table-count                   |                                 |
| table-wrap-foot               | table-wrap-foot               | table-wrap-foot               |
| table-wrap-group              | table-wrap-group              |                                 |
| table-wrap                    | table-wrap                    | table-wrap                    |
| table                         | table                         | table                         |
| target                        | target                        |                                 |
| tbody                         | tbody                         |                                 |
| td                            | td                            |                                 |
| term-head                     | term-head                     |                                 |
| term                          | term                          |                                 |
| tex-math                      | tex-math                      |                                 |
| textual-form                  | textual-form                  |                                 |
| tfoot                         | tfoot                         |                                 |
| th                            | th                            |                                 |
| thead                         | thead                         |                                 |
|                                 | time-stamp                    |                                 |
| title-group                   | title-group                   | title-group                   |
| title                         | title                         |                                 |
| toc-div                       |                                 |                                 |
| toc-entry                     |                                 |                                 |
| toc-group                     |                                 |                                 |
| toc                           |                                 |                                 |
| tr                            | tr                            |                                 |
| trans-abstract                | trans-abstract                | trans-abstract                |
| trans-source                  | trans-source                  |                                 |
| trans-subtitle                | trans-subtitle                |                                 |
| trans-title-group             | trans-title-group             | trans-title-group             |
| trans-title                   | trans-title                   | trans-title                   |
| underline-end                 |                                 |                                 |
| underline-start               |                                 |                                 |
| underline                     | underline                     |                                 |
| unstructured-kwd-group        |                                 |                                 |
| uri                           | uri                           |                                 |
|                                 | version                       |                                 |
| verse-group                   | verse-group                   | verse-group                   |
| verse-line                    | verse-line                    |                                 |
| volume-id                     | volume-id                     |                                 |
| volume-in-collection          |                                 |                                 |
|                                 | volume-issue-group            |                                 |
| volume-number                 |                                 |                                 |
| volume-series                 | volume-series                 |                                 |
| volume-title                  |                                 |                                 |
| volume                        | volume                        | volume                        |
| word-count                    | word-count                    |                                 |
| x                             |                                 |                                 |
| xi:fallback                   |                                 |                                 |
| xi:include                    |                                 |                                 |
| xref                          | xref                          | xref                          |
| year                          | year                          | year                          |





========================
SciELO Publishing Schema
========================

See http://docs.scielo.org/projects/scielo-publishing-schema


The JATS Standard is copyrighted by NISO, but all of the non-normative 
information found on this repository is in the CC BY-NC 4.0 

More info at http://creativecommons.org/licenses/by-nc/4.0/.

