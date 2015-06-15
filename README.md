##HOWTO install statismo for debian using this repository:

###Add  the statismo repository to your debian sources list:

As root edit /etc/apt/sources.list and add the following line:

    deb http://zarquon42b.github.io/debian <release> main


###Import the GPG key:

    wget -O - http://zarquon42b.github.io/debian/pubkey.gpg.key|apt-key add -
