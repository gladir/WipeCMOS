# WipeCMOS
Cette commande permet d'effacer le contenu du CMOS.

<h3>Syntaxe</h3>

<b>WIPECMOS</b> [<i>taille</i>] [<i>option</i>]

<h3>Paramètres</h3>

<table>
  <tr>
    <th>Nom</th>
    <th>Description</th>
  </tr>
  <tr>
    <td><i>taille</i></td>
    <td>Taille du CMOS</td>
  </tr>
  <tr>
    <td><b>-b:</b><i>valeur</i></td>
    <td>Indique la valeur à écrire. Par défaut 0.</td>
  </tr>
  <tr>
    <td><b>/AMDEK</b></td>
    <td>Utilise l'adresse d'un AMDEK SYSTEM/88.</td>
  </tr>
</table>  

<h3>Remarques</h3>
<ul>
  <li>Ce programme s'exécute uniquement en mode réel du microprocesseur 8086, et il est très dangereux car il élimine le contenu du CMOS, aussi bien la date et l'heure, la configuration des disques durs et les mots de passe. Il ne faut pas l'utiliser de façon inapproprié, car vous risquez d'endommager votre micro-ordinateur.</li>
  <li>Cette commande est un équivalent d'enlever la batterie du CMOS contenu dans votre micro-ordinateur. Ainsi, lorsque vous enlever la battterie, toutes les données contenus dans le CMOS disparaissent.</li>
</ul>
