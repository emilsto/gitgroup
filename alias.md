<h3>Use Aliases</h3>  

Luomalla aliaksen, ei pitkien komentojen kirjoittelu ole enaan tuskaa.  
```
git config --global alias.enforce "push --force-with-lease"
```  
Luo aliaksen config, joka ajaa pidemman komennon. Tulevaisuudessa voit kayttaa:  
```
git enforce
```  
Joka tekee saman kuin:
```
git push --force-with-lease
``` 
