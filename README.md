# angularDemo
## how to use
  * html
      * <my-page num={{num}} on-page-change="onPageChange(name)"></my-page>
  * controller.js
      *  $scope.num = 10;
        $scope.onPageChange = function(name) {
            // alert(name);
            //name为当前页码
        };
