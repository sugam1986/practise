
<html>
<head>
<meta charset="ISO-8859-1">
<title>Insert title here</title>
<link rel="stylesheet" href="http://maxcdn.bootstrapcdn.com/bootstrap/3.2.0/css/bootstrap.min.css">
<script src="https://ajax.googleapis.com/ajax/libs/angularjs/1.3.12/angular.min.js"></script>
<script src="libraries/route.js"></script>
<script src="alone.js"></script>

</head>
<body ng-app="home">


<a href="#next"><button ng-click="hi=!hi" ng-hide="hi">Start</button></a>




 <div ng-view></div>












</body>
</html>
