# Common-Service-Showcase
Website for user documentation and marketing of the common services built by the Common Service Showcase Team.  

#### GitHub Pages
We are using [GitHub Pages](https://pages.github.com) with [gh-pages branch](https://help.github.com/en/github/working-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site#choosing-a-publishing-source) publishing source.  We have set gh-pages as the default branch and we require that all changes are done via Pull Requests.  However, in order to review/preview the changes, one must run the site locally.  

## Content
The site is built with [Jekyll](https://jekyllrb.com), so start by reviewing their documentation.  Jekyll in turn uses [Markdown](https://daringfireball.net/projects/markdown/), [Liquid](https://github.com/Shopify/liquid/wiki), HTML & CSS to generate the static site.  

#### Cards
[_cards](./_cards) is a collection that is iterated over and used to build the single page site.  See index.md for how the collection is rendered.

#### Publishing

GitHub Pages understands Jekyll and will build and deploy sites automatically, do **not** check in the *_site* directory.

1. Fork the [Common Service Showcase repository](https://github.com/bcgov/common-service-showcase)  
1. Checkout gh-pages branch  
1. Create branch from gh-pages  
1. Add new Cards, or other content  
1. Build with Jekyll   
1. Review your changes  
1. Commit and push your changes to your fork.  
1. Make a [pull request](https://github.com/bcgov/common-service-showcase/pulls) in Common Service Showcase repository.  
1. Ask for a review and approval of changes.    


## Build with Jekyll
1. Install a full Ruby development environment (2.6 works).
For Windows users, visit https://rubyinstaller.org/downloads/ and download latest version WITH Devkit option. Install the installer (when prompted, just tap enter to use defaults - may happen twice)

1. Install [Jekyll](https://jekyllrb.com) and bundler gems.
Open a console window with directory at root of this repo and run:
    ```
    gem install bundler
    gem install jekyll
    bundle install
    ```
1. Build and serve site (locally)
    ```
    bundle exec jekyll build
    bundle exec jekyll serve
    ```

1. Go to site: http://localhost:4000/common-service-showcase
