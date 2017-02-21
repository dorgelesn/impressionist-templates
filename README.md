# impressionist-templates
Templates to create [impress.js](https://github.com/henrikingo/impress.js) presentations from.
Used also by the [Impressionist creator](https://github.com/henrikingo/impressionist).

## Usage

    git clone https://github.com/henrikingo/impressionist-templates.git
    cd impressionist-templates
    git submodule init
    git submodule update

* Each directory is its own self contained impress.js presentation.
* The main presentation file is index.html
* The impress.js file is under impress/js/impress.js
** This is to allow for various forms of indirections, such as git submodules, symlinks or http
   redirects for the impress/ directory.
* Other than this, the directory contains css files, images and other supporting files as needed.

To create a new presentation, you'd typically just copy the directory of your favorite template,
and then edit index.html.
