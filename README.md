# ListBulkDelete
Simple c# implementation of list bulk delete


### Imports:
  * js:
    ``` 
    <script src="~/bulkaction/bulkaction.js" asp-append-version="true"></script> 
    ```
  * css: 
    ``` 
    <link rel="stylesheet" href="~/bulkaction/bulkbtn.css" asp-append-version="true" /> 
    ```
    
    
- DeletAll: 
set the following code above the list, and pass in the controller and action name inside the delectbulkaction() function: 
    ``` 
    <button type="button" class="btn btn-danger " id="deletebulk" onclick="delectbulkaction('Home', 'DeleteBulk')"> Delete</button> 
    ```
- Them set the checkbox in table header:
    ``` 
    <th>
        <input type="checkbox" id="selectAll">
    </th> 
    ```
     
- to set the delete list item set the following code inside the list content, and pass the Id as a value of the imput:
    ```
    <td> 
        <input type="checkbox" id="chk" class="classchk" value="@item.Id"> 
    </td>
    ``` 
 
     
### Code:
in your controller method place this code, and do what ever task you need

<img width="508" alt="Bulkdelete" src="https://user-images.githubusercontent.com/2583043/193856735-583985a8-65c7-4f06-821e-db5125a4e44f.png">
  
# Demo
<img width="1008" alt="Bulkdelete" src="https://user-images.githubusercontent.com/2583043/193836547-6055823d-51b7-4150-8520-85f0b5b0c033.PNG">

     
Goog Coding :)
