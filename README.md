# bash-notes
<tbody>
   <tr>
      <td><kbd>${parameter:-defaultValue}</kbd></td>
      <td> Get default shell variables value</td><br>
   </tr>
   <tr>
      <td><kbd>${parameter:=defaultValue}</kbd></td>
      <td> Set default shell variables value</td>
   </tr>
   <tr>
      <td><kbd>${parameter:?"Error Message"}</kbd></td>
      <td> Display an error message if parameter is not set</td>
   </tr>
   <tr>
      <td><kbd>${#var}</kbd></td>
      <td> Find the length of the string</td>
   </tr>
   <tr>
      <td><kbd>${var%pattern}</kbd></td>
      <td> Remove from shortest rear (end) pattern</td>
   </tr>
   <tr>
      <td><kbd>${var%%pattern}</kbd></td>
      <td> Remove from longest rear (end) pattern</td>
   </tr>
   <tr>
      <td><kbd>${var:num1:num2}</kbd></td>
      <td>Substring</td>
   </tr>
   <tr>
      <td><kbd>${var#pattern}</kbd></td>
      <td> Remove from shortest front pattern</td>
   </tr>
   <tr>
      <td><kbd>${var##pattern}</kbd></td>
      <td> Remove from longest front pattern</td>
   </tr>
   <tr>
      <td><kbd>${var/pattern/string}</kbd></td>
      <td> Find and replace (only replace first occurrence)</td>
   </tr>
   <tr>
      <td><kbd>${var//pattern/string}</kbd></td>
      <td> Find and replace all occurrences</td>
   </tr>
   <tr>
      <td><kbd>${!prefix*}</kbd></td>
      <td> Expands to the names of variables whose names begin with prefix.</td>
   </tr>
   <tr>
      <td><kbd>${var,}</kbd><br><kbd>${var,pattern}</kbd></td>
      <td> Convert first character to lowercase.</td>
   </tr>
   <tr>
      <td><kbd>${var,,}</kbd><br><kbd>${var,,pattern}</kbd></td>
      <td> Convert all characters to lowercase.</td>
   </tr>
   <tr>
      <td><kbd>${var^}</kbd><br><kbd>${var^pattern}</kbd></td>
      <td> Convert first character to uppercase.</td>
   </tr>
   <tr>
      <td><kbd>${var^^}</kbd><br><kbd>${var^^pattern}</kbd></td>
      <td> Convert all character to uppercase..</td>
   </tr>
</tbody>


