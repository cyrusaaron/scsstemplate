~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
~~~~~~   SCSS Structure/Template   ~~~~~~~~
~~~~~~~~~~~~   by Cyrus Aaron   ~~~~~~~~~~~
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

## How to run SASS? ##

    Launch CMD on your file directory. The main format of the command is 

    "sass --watch mainsassfilepath:compiledcssfilepath"

    Example:
    "sass --w scss/main.scss:css/style.css"  
    "sass --watch foldername/scss/main.scss:css/main.css"



## FILES BREAKDOWN ##
    
    Note: Folder structure usually depends on your project archintecture. This is the format I use as base structure on my projects. 

    1. 'main.scss'

        This is the main SCSS file. All partial scss files are compiled here.

    2. 'base'

        This folder contains scss files where global variables are declared. Usually, it contains typography, colors, etc etc.

    3. 'components'

        This folder contains components styles that are used in the website. This usually contains styles for sliders, carousels, etc.

    4. 'layout'
    
        This folder contains scss files that are used for website layout. This usually contains both header and footer, forms, and navigation layout.

    5. 'pages'

        This folder contains all the scss files for all the pages. 

    6. 'vendors'

        This folder contains scss files that has elements from external frameworks. One of the most common files is Bootstrap.




~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
~~~~~~~~~  cyruuusdev@gmail.com   ~~~~~~~~~
~~~~~~~~~~~~~   April 2018   ~~~~~~~~~~~~~~
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~