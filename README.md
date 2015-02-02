RefBib
======

A construção do conhecimento cientítico passa, obrigatóriamente, pela publicaçãoacadêmica. Toda nova publicação acadêmica precisa ser contextualizada perante o corpo de conhecimentos já existente, o qual costuma estar formalizado também na forma de publicações acadêmicas. São as nossas referências bibliográficas!

Depois de algum tempo de atividade, todo pesquisador constrói um banco de referências bibliográficas (RefBib) com algumas centenas de items. E como é fácil perder-se em meio a esse amontoado de RefBib! Não bastasse isso, a etapa mais enfadonha da elaboração de qualquer publicação acadêmica é a formatação da lista de RefBib. Cada periódico, instituição e evento científico com suas próprias normas, algumas vezes absurdas. A situação é ainda pior no caso de dissertações e teses, onde o número de itens pode chegar facilmente a algumas centenas.

A organização eficiente de um banco de RefBib e a otimização da sua formatação em publicações acadêmicas exige o uso de um gerenciador de [RefBib](pt.wikipedia.org/wiki/Gerenciador_de_refer%C3%AAncias_bibliogr%C3%A1ficas). Um gerenciador de RefBib consiste em um software de manipulação de um banco de dados onde são armazenadas informações básicas sobre as RefBib. Os gerenciadores podem ser integrados a processadores de texto, como o [LibreOffice Writer](http://pt-br.libreoffice.org/) e o [Microsoft Office Word](http://office.microsoft.com/pt-br/), permitindo a adequada formatação das citações e da lista de RefBib automaticamente. 

Existem [vários](http://en.wikipedia.org/wiki/Comparison_of_reference_management_software) softwares de gerenciamento de RefBib, cada um melhor adaptação a diferentes situações e exigências do usuário, o que torna difícil a escolha do gerenciador a ser utilizado. A minha escolha atual é o JabRef.

# JabRef

Eu considero o JabRef um dos melhores gerenciadores de RefBib devido à sua simplicidade e eficiência, mas sobretudo por fazer parte da família dos softwares livres e de código aberto (Free and Open Source Software – FOSS).

O JabRef foi lançado em 29 de novembro de 2003 sob a licença GPL (General Public Licence). Escrito na linguagem de programação Java, está disponível em várias línguas, entre elas o português. Possui suporte para a maioria dos sistemas operacionais (Windows, Linux, Mac OS X, BSD, Unix) e integração com a maioria dos editores de texto (Microsoft Office Word, LibreOffice Writer, OpenOffice Writer, LyX, Kile, Emacs, Vim e WinEdt). Está entre aqueles com maior capacidade de importação e exportação arquivos de diferentes formatos. Ainda oferece a possibilidade de edição, pesquisa e visualização das referências, pesquisa em bancos de dados na internet (PubMed, IEEEXplore, CiteSeer, JSTOR, BibSonomy), links para fontes externas (URL, DOI, PDF, PS), customização de filtros de exportação (arquivos de estilo), abreviação do nome de periódicos e muito mais.

Se essas informações já foram suficientes para convencê-lo a usar o JabRef, então acesse a página do projeto no [SourceForge](http://sourceforge.net/projects/jabref/files/jabref/) e instale a última versão mais estável para seu sistema operacional.

# BibTeX

Outra grande vantagem do JabRef é que o mesmo utiliza o formato [BibTeX](http://pt.wikipedia.org/wiki/Bibtex) como formato nativo para gerenciamento das RefBib. Assim, a entrada de RefBib no banco de dados do JabRef pode ser realizada usando a interface gráfica ou arquivos BibTeX (arquivo no formato `*.bib`).

A maioria dos bancos de dados de referências bibliográficas na Internet permite exportar arquivos BibTeX, como o [Google Scholar](scholar.google.com.br) e [ScienceDirect](http://www.sciencedirect.com/). Assim, não é necessário entrar manualmente todas as informações de uma RefBib. Basta descarregar o arquivo BibTeX. O quadro abaixo mostra como exemplo o conteúdo do arquivo BibTeX de um artigo publicado na Revista Brasileira de Ciência do Solo.

```
@ARTICLE{PedronEtAl2012,
    author    = {Pedron, Fabrício Araújo and Alessandro Samuel-Rosa and Ricardo
                 Simão Diniz Dalmolin},
    title     = {Variation in pedological characteristics and the taxonomic
                 classification of Argissolos (Ultisols and Alfisols) derived
                 from sedimentary rocks},
    journal   = {Revista Brasileira de Ciência do Solo},
    year      = {2012},
    volume    = {36},
    pages     = {1-9},
    doi       = {10.1590/S0100-06832012000100001},
    file      = {PedronEtAl2012.pdf:PedronEtAl2012.pdf:PDF},
    keywords  = {sandy soils; numeric classification; SiBCS},
    owner     = {Alessandro Samuel Rosa},
    timestamp = {2012.06.25},
    url       = {http://dx.doi.org/10.1590/S0100-06832012000100001}
  }
```

Se você não quiser iniciar seu banco de RefBib do zero, clique aqui para descarregar um arquivo `*.bib` contendo uma centena de RefBib na área de pedometria e mapeamento digital do solo.

# Arquivo de estilo

A utilização do JabRef para a inserção de citações e formatação da lista de RefBib em um documento de texto do LibreOffice Writer depende de duas ferramentas. Primeiro, do plugin que faz a conexão do JabRef com o LibreOffice Writer. Para descarregar o plugin basta acessar a página do projeto [clicando aqui](http://jabref.sourceforge.net/OOPlugin-jabref.php). O plugin para conexão do JabRef com o Microsoft Office Word pode ser descarregado [clicando aqui](http://www.ee.ic.ac.uk/hp/staff/dmb/perl/index.html).

A segunda ferramenta é o arquivo de estilo `*.jstyle`. Um arquivo de estilo contém as informações necessárias para a formatação das RefBib que são exportadas para o arquivo de texto no LibreOffice Writer (Note que o arquivo de estilo para documentos do Microsoft Office Word possui formato diferente daquele usado para o LibreOffice Writer. [Clique aqui](https://docs.google.com/file/d/0B7xsLbrOA23oMndPR0lSdXl2Y0k/edit?usp=sharing) para descarregar o modelo do resumo do Congresso Brasileiro de Ciência do Solo no formato do LibreOffice Writer). O JabRef possui uma série de arquivos de estilo em seu [banco de dados](https://docs.google.com/file/d/0B7xsLbrOA23oMndPR0lSdXl2Y0k/edit?usp=sharing). Mas como cada periódico, instituição e evento científico possuem normas próprias de formação das RefBib, pode-se customizar os arquivos de estilo. O quadro abaixo mostra parte do arquivo de estilo elaborado para exportação e formatação das RefBib conforme as normas da Revista Brasileira de Ciência do Solo ([RBCS](http://www.sbcs.org.br/revista/a-revista/)).

```
NAME
Revista Brasileira de Ciência do Solo

JOURNALS
XXXIV Congresso Brasileiro de Ciência do Solo
Revista Brasileira de Ciência do Solo

PROPERTIES
Title="REFERÊNCIAS"
IsSortByPosition="false"
IsNumberEntries="false"
ReferenceParagraphFormat="References"
ReferenceHeaderParagraphFormat="Reference Head"

CITATION
AuthorField="author/editor"
YearField="year"
MaxAuthors="2"
MaxAuthorsFirst="2"
AuthorSeparator=", "
AuthorLastSeparator=" & "
AuthorLastSeparatorInText=" & "
EtAlString=" et al."
CitationSeparator="; "
MultiCiteChronological="true"
BracketBefore="("
BracketAfter=")"
BracketBeforeInList="["
BracketAfterInList="]"
MinimumGroupingCount="3"
CitationCharacterFormat="Text body"
GroupedNumbersSeparator="-"
UniquefierSeparator=", "
InTextYearSeparator=" "
YearSeparator=", "
FormatCitations="false"
ItalicCitations="false"
BoldCitations="false"
SuperscriptCitations="false"
SubscriptCitations="false"

LAYOUT
article=\begin{author}\format[Authors(LastFirst, sep=; ), AuthorAndsReplacer,
        NoSpaceBetweenAbbreviations, ToUpperCase]{\author}\end{author}\title.
        \format[JournalAbbreviator]{\journal}, \volume:\begin{pages}
        \format[FormatPagesForHTML]{\pages}\end{pages}, \year\uniq.
```

O arquivo de estilo possui cinco campos: `NAME`, `JOURNALS`, `PROPERTIES`, `CITATION` e `LAYOUT`. O campo `NAME` define o nome do arquivo de estilo, e o campo `JOURNALS` identifica a quais eventos científicos e periódicos o arquivo de estilo se aplica. Essas informações são mostradas na interface do JabRef quando é solicitada a visualização da lista de arquivos de estilo disponíveis. O campo `PROPERTIES` possui informações gerais sobre a formatação das RefBib como, por exemplo, o título (Title) exportado para o documento de texto. Em seguida, o campo `CITATION` define a formatação das citações no texto. Por fim, o campo `LAYOUT` define a formatação da lista de RefBib.

Um arquivo de estilo (`*.jstyle`), contendo as regras de formatação das citações e da lista de RefBib conforme as normas da Revista Brasileira de Ciência do Solo, pode ser descarregado [clicando aqui](https://docs.google.com/file/d/0B7xsLbrOA23oLWs3Wm1ERnNzUk0/edit?usp=sharing), para a versão em português, ou [clicando aqui](https://docs.google.com/file/d/0B7xsLbrOA23oZk5lVU5SUlRVMXM/edit?usp=sharing) para a versão em inglês.

# Abreviação do nome de periódicos

Outra importante funcionalidade do JabRef é o comando JournalAbbreviator, através do qual os nomes dos periódicos são abreviados de modo automático. Para isso é necessário um arquivo onde estejam definidos os nomes dos periódicos e as respectivas abreviações. O quadro abaixo mostra parte do arquivo contendo informações para a abreviação automática do nome de periódicos científicos que elaboramos para exportação e formatação das RefBib conforme as normas da Revista Brasileira de Ciência do Solo adotadas pela Comissão Organizadora do XXXIV Congresso Brasileiro de Ciência do Solo.

```
Aaas Selected Symposia Series = Aaas Select
Aace Bulletin = Aace Bull
Aall Publications Series = Aall Publ S
Aapg Bulletin = Aapg Bull
Aapg Bulletin-american Association of Petroleum Geologists = Aapg Bull
Aapg Memoirs = Aapg Memoir
Aapg Studies in Geology = Aapg Stud Geol
Aaps Journal = Aaps J
Aaps Pharmsci = Aaps Pharmsci
Aaps Pharmscitech = Aaps Pharmscitech
Aas History Series = Aas Hist S
Aascu Issues = Aascu Iss
Aatcc Review = Aatcc Rev
Aatcc Symposium = Aatcc Symp
```

Um arquivo o nome e abreviação do nome de centenas de periódicos científicos de todo o mundo, conforme a Web of Science, pode ser descarregado [clicando aqui](https://docs.google.com/file/d/0B7xsLbrOA23obFBhWGkzWVlkb1k/edit?usp=sharing).
