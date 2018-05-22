# latte
Content editor defines accordions, tabs, carousels, image-map, popup window, popup contents using HTML table. 
The script will convert the table into the respective components.

For example:

<table>
 <tr><td> [Popup][Name=testpopup] </td</tr>
 <tr><td> This is a popup content </td></tr>
 </table>
 
<a href="#testpopup">click here to open popup</a>

<!-- paste latte.html content here -->

Results:

When user clicks on the link, the popup with the defined content will be displayed.
