# Aquiles-walk-with-AngularJS

<!DOCTYPE html>
<html>
<body>
<script src="https://ajax.googleapis.com/ajax/libs/angularjs/1.6.9/angular.min.js"></script>

<div data-ng-app="" data-ng-init="caminhada=0;distancia=20">

<h2>A caminhada de Aquiles</h2>

Caminhada: <input type="number" data-ng-model="caminhada">
 Distância: <input type="number" data-ng-model="distancia">

<p><b>Até agora foram: </b><span ng-bind="distancia/2**caminhada"></span><b> metros</b></p>

</div>

</body>
</html>
