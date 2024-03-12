# Masima Links

This is a static hugo side to deploy an masima link tree to github pages.

- https://mxklb.github.io/masima-links


## Initial Hugo Setup

Create from scratch new hugo page structure with [hugo-wrapper](https://github.com/khos2ow/hugo-wrapper):

    ./hugow new site lynx

### Setup Lynx Theme

    cd lynx
    mkdir -p themes/lynx/
    curl -L https://github.com/jpanther/lynx/archive/refs/tags/v1.3.1.tar.gz | tar -xz -C themes/hugo-geekdoc/ --strip-components=1

For further details refer to [lynx](https://github.com/jpanther/lynx)


## Development

Initial setup above is needed only once to completely start from scratch.

This page is already prepared and edits just happen inside `lynx` folder. 

To start this page on local docker host for development:

    docker-compose up

Now visit [localhost:1313](http://localhost:1313) to view page & do changes .. 