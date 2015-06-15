##HOWTO install statismo for debian using this repository:

###Add  the statismo repository to your debian sources list:

```bash
## Debian jessie (stable):
echo "deb http://zarquon42b.github.io/debian jessie main" | \
sudo tee /etc/apt/sources.list.d/statismo.list
echo "deb-src http://zarquon42b.github.io/debian jessie main" | \
sudo tee -a /etc/apt/sources.list.d/statismo.list
    
## Debian stretch (testing):
echo "deb http://zarquon42b.github.io/debian stretch main" | \
sudo tee /etc/apt/sources.list.d/statismo.list
echo "deb-src http://zarquon42b.github.io/debian stretch main" | \
sudo tee -a /etc/apt/sources.list.d/statismo.list
```

###Import the GPG key:

    wget -O - http://zarquon42b.github.io/debian/pubkey.gpg.key|sudo apt-key add -

### update sources

    apt-get update

### install statismo

    apt-get install statismo statismo-tools
