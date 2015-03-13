Quickstart
==========

Summary how to get started with toertchen in under five minutes


Installing
----------

 * Windows: Currently not supported.
 * installation: Currently not possible.

Just checkout the svn::
    svn checkout http://toertchen.googlecode.com/svn/trunk/ toertchen-read-only


And put toertchen-read-only/bin into your PATH.

Or run it as /.../toertchen-read-only/bin/toertchen.

Usage
-----


    mkdir my_awesome_presentation # Create an empty directory where your presentation related files will be stored

    cd my_awesome_presentation

    # Put a bg.svg into your directory - it will be rendered for every page. $pn will be substituted with the current page number
    # for example use this one:
    wget http://toertchen.googlecode.com/svn-history/r15/trunk/doc/example0/bg.svg

    mkdir src # Create a subdir "src"


Now the only thing left is writing your presentation into text files within the "src" folder.

Syntax
------


    Page Heading

    * First bullet point
     * Sub point
     * Another point

    ---
    Second Slide

    Some text with no meaning...

    * more text...


Running::

    $ toertchen


see [http://toertchen.googlecode.com/svn-history/r15/trunk/doc/example0/output.pdf output.pdf]

or

    toertchen --single


see [http://toertchen.googlecode.com/svn-history/r15/trunk/doc/example0/output-single.pdf output.pdf]


The full example is in the svn at [https://code.google.com/p/toertchen/source/browse/trunk/doc/example0/ doc/example0]
