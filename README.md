##HOWTO install statismo for debian using this repository:

###Add  the statismo repository to your debian sources list:

As root edit /etc/apt/sources.list and add the following line:

    deb http://zarquon42b.github.io/debian <jessie|stretch> main


###Import the GPG key:

    wget -O - http://zarquon42b.github.io/debian/pubkey.gpg.key|sudo apt-key add -

### update sources

    apt-get update

### install statismo

    apt-get install statismo statismo-tools
