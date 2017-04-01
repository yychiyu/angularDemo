
# angularDemo
## how to use
   html </br>
      ```
      <my-page num={{num}} on-page-change="onPageChange(name)"></my-page>
       ```
       </br>
   controller.js </br>
      ```
   $scope.num = 10;
   $scope.onPageChange = function(name) {
   // alert(name);
   //name为当前页码
            }; 
            ```
    
         
          
   
