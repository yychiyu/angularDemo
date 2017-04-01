# angularDemo
angular demo
how to use 
exmaple
   html  <my-page num={{num}} on-page-change="onPageChange(name)"></my-page>
   in controller  
   $scope.num = 10; //num pageCounts;
   $scope.onPageChange = function(name) {
       // alert(name); //name currentPage
   };
