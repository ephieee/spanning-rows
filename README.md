# spanning-rows

You may also need entries in a table to stretch down across more than one row.The rowspan attribute can be used on a <th> or <td> element to indicate how many rows a cell should span down the table.
If you look at the last <tr> element, it only contains three elements even though there are four columns in the result below. This is because the movie in the <tr> element above it uses the rowspan attribute to stretch down and take over the cell below.

<table>
 <tr>
  <th></th>
  <th>ABC</th>
  <th>BBC</th>
  <th>CNN</th>
 </tr>
 <tr>
  <th>6pm - 7pm</th>
  <td rowspan="2">Movie</td>
  <td>Comedy</td>
  <td>News</td>
 </tr>
 <tr>
  <th>7pm - 8pm</th>
  <td>Sport</td>
  <td>Current Affairs</td>
 </tr>
</table>
