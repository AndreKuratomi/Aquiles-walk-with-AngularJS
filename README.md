# Aquiles-walk-with-AngularJS

<!DOCTYPE html>
<html>
<body>
<script src="https://ajax.googleapis.com/ajax/libs/angularjs/1.6.9/angular.min.js"></script>

<div data-ng-app="" data-ng-init="walk=0;distance=20">

<h2>Aquiles' walk</h2>

Walk: <input type="number" data-ng-model="walk">
Distance: <input type="number" data-ng-model="distance">

<p><b>He walked: </b><span ng-bind="distance/2**walk"></span><b> metters</b></p>

</div>

</body>
</html>
