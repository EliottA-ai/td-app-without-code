# td-app-without-code

4:
vercel -v
5: 
npm install -g @angular/cli
ng new "nameofproject"

6:
vercel deploy

7:
vercel list

8:
vercel logs <deployment-url>

9:
Cela permet d'avoir des informatiosn détaillés sur le deploiement
vercel inspect <deployement-url>

10:
les variables d'environements sont des variables dynamiques qui servent à communiquer netre les programmes

11: 
vercel env add

12:
vercel env ls

13:


15:
vercel secret add name value (to create secret)
vercel env add (to add the env variable)

16: Vercel met à disposition un environement Production, Preview et Development. Cela permet de mieux organiser son projet selon les utilité de chaque changements

18:
https://td-app-without-code-2kk43z5mk.vercel.app/

19:
Vercel a automatiquement deployer la pull request 

20:
Vercel met également à jour le deployement avec le merge qui à été effectué

21:
la production correspond au main ou master
les pull request permettent une collaboration plus facile au sein du projet avec de merge les modifications
On fais la phase Develpment avec chacun de son coté puis on utilise la preview avant de pull request avant de merge sur le main ou master dans l'environnement production

22:
Les fonctions serverless sont des bouts de codes en backend pour faire des requette http avec des reponses
