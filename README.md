# Initiation au SQL
Sur [W3School](http://www.w3schools.com/sql/trysql.asp?filename=trysql_select_all)
Réalisez les requêtes suivantes : 
* La liste des ContactName de la table Customer
<table><tr><td><b>ContactName</b></td></tr>
<tr><td>Maria Anders</td><tr>
<tr><td>...</td><tr>
</table>

* La liste des ProductName qui ont la CaterogyID 1 dans la table Product
<table><tr><td><b>ProductName</b></td></tr>
<tr><td>Chais</td><tr>
<tr><td>...</td><tr>
</table>

*  Dans la table Product, au lieu d'avoir les ID  (pour categoryID et SupplierID), qu'on voie les noms des catégories et des fournisseurs , tout celà en une seule requête (edited)
<table><tr><td><b>ProductName</b></td><td><b>CategoryName</b></td><td><b>SupplierName</b></td></tr>
<tr><td>Chais</td><td>Beverages</td><td>Exotic Liquid</td><tr>
<tr><td>...</td><td>...</td><td>...</td><tr>
</table>

* Créez une table utilisateur semblable à celle qu enous pouvons trouver au sein d'un réseau social. Réflechissez aux champs nécessaires et à la structure.
* Quels champs seront répetitifs? Est-il possible d'en générer des tables en 1,n . Et/Ou que suis-je en train de vous demander  de faire ?
* Est-il possible d'avoir le nombre d'ordres (OrderDetails) réalisés pour chaque Categorie avec leur cout total?
<table><tr><td><b>CategoryName</b></td><td><b>Nb Order Details</b></td><td><b>Sum Order Cost</b></td></tr>
<tr><td>Beverages</td><td>93</td><td>99464.5</td></tr>
</table>
