<h3>Delete local branches on fetch/pull</h3>  

Remote repositorysta poistetut branchit voidaan poistaa automaattisesti fetch/pull komennon yhteydessä, jos tämä asetus on päällä.
```
git config --global fetch.prune true
```    
Voidaan myös laittaa .gitconfig tiedoston kautta laittamalla sinne seuraavasti:
```
[fetch]
  prune = true
```
