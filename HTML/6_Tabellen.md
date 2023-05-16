# Tabellen in HTML #
## Beispiel für eine Tabelle: ##
```html
<!DOCTYPE html>
<html>
    <head></head>

    <body>
        <table>
            <tr>
                <th> 1 </th>
                <th> 2 </th>
                <th> 3 </th>    
            </tr>
            <tr>
                <td> 1 </td>
                <td> 2 </td>
                <td> 3 </td>
            </tr>
            <tr>
                <td> 1 </td>
                <td> 2 </td>
                <td> 3 </td>
            </tr>
        </table>
    </body>
````

Der Befehl **tr** steht für **table row**, also **Reihe**.<br>
DerBefehl **td** steht für **table data**, also der **Inhalt** der Tabelle.<br>
DerBefehl **th** steht für **table header**, also die **Kopfzeile** der Tabelle.<br>


## Design ##
Mit **Css** kann auf eine **Tabelle** ein Rand und diverse andere Design Optionen angewendet werden.<p>
```html
<body>
table, th, td {
  border: 1px solid black;
}
</body>
````
Die **Größe** einer **Tabelle** kann mit dem *width* attribut beeinflusst werden.<p>
Für weitere Informationen, siehe 6_Tabellen.md oder [GitHub](https://github.com/)