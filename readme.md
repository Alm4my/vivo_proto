# Points de Ventes | Prototype
Ceci est un api simple pour donner les points de vente. Le model de base se trouve dans `db.json`.
Tout d'abord, installez les paquets requis avec:
```shell 
npm install
```
Apres, lancez:
```shell
json-server db.json
```
NB: Si vous etes sur windows vous devez utiliser `cmd` au lieu de `powershell`.
Vous pouvez cd dans le repertire et lancez la commande 
```shell
cmd
```
puis 
```shell
json-server db.json
```
Ceci ouvrira localhost au port 3000.
Je n'ai cree qu'un seul model appele points_de_vente.
Apres avoir lancer l'application vous pourrai le voir au <http://localhost:3000/points_de_vente>

Vous pouvez CRUD et ajouter d'autres champs a votre guise. Notez que les elements creez ne s'enregistre pas automatiquement et reste en memoire. 
si vous voulez les enregister dans votre db.json vous devez appuiyez `s` sur votre terminal. 

contact: almamy@tuta.io
