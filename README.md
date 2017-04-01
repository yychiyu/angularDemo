
# angularDemo
## how to use
   html
      ``` html
      <my-page num={{num}} on-page-change="onPageChange(name)"></my-page><br>
      ```
   controller.js
         $scope.num = 10;
         $scope.onPageChange = function(name) {
            // alert(name);
            //name为当前页码
            }; 
