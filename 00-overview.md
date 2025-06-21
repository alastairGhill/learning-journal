
the tag <td></td>
# HTML Table

## What I Learned
- The tag `<table></table>`  is used to create a table within the webpage
- The tag `<tr>` is used to create a row
- The tag `<td>` creates cells within the row

## Example
```html
<table>
        <tr>
            <th>Date</th>
            <th>Meter reading</th>
        </tr>
        <tr>
            <td>21/06/2025</td>
            <td>5375.911</td>
        </tr>
    </table>

## What I Learned
- CSS is used to create borders and apply formating
- To create a solid black border use border:1px solid black;
- To collapse the boarder so that we don't see double lines, we use  border-collapse: collapse;

## Example
```css
table, th, td {
  border:1px solid black;
  border-collapse: collapse;
}
