# Aquiles-walk-with-AngularJS

<!DOCTYPE html>
<html>
<body>
<script src="https://ajax.googleapis.com/ajax/libs/angularjs/1.6.9/angular.min.js"> </script>

<div data-ng-app="" data-ng-init="caminhada=0;distance=20">

<h2>Aquiles' walk</h2>

<p> Achilles has a distance of 20m to be covered but following the Zenon paradox: at each walk he walks half of what he still needs to. The numbers in 'Walk' indicate the number of times he walks and those in 'Distance' indicate the meters he still has to go.</p>

<p> Will he reach the end?</p>
<br>

Walk: <input type="number" data-ng-model="walk">
Distance: <input type="number" data-ng-model="distance">

<p><b>Distance missing: </b><span data-ng-bind="distance/(2**walk)"></span><b> meters</b></p>

</div>

</body>
</html>
