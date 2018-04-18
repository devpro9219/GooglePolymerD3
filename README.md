# Polymer+ D3 Library

## Running the tutorial code

Using Technology.
Polymer 2.0
D3.js 1.0

1.  Download and install Node version 6.x or 7.x from [https://nodejs.org/](https://nodejs.org/). Node includes the node package manager command, `npm`.

2.  Install `bower` and the Polymer CLI:

        npm install -g bower polymer-cli

3.  Clone this repo:

        https://github.com/PolymerLabs/polymer-2-first-element.git
        
4.  Change directory to your local repo and install dependencies with `bower`:

        cd polymer-2-first-element
        bower install
        
5.  To preview your element, run the Polymer development server from the repo directory:

        polymer serve
        
    Open `localhost:8080/components/icon-toggle/integrate/` in your browser. (Note that the path uses `icon-toggle`—the 
    component name listed in this element's `bower.json` file—rather than the actual directory name.) 
