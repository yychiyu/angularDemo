
# angularDemo
## how to use
   html </br>
      ``` html
      <my-page num={{num}} on-page-change="onPageChange(name)"></my-page>
       ```
       </br>
   controller.js </br>
   ``` javascript
         $scope.num = 10;
         $scope.onPageChange = function(name) {
            // alert(name);
            //name为当前页码
         }; 
          
   
