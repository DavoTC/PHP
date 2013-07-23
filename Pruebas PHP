<?php date_default_timezone_set('America/Guayaquil') ?>
<html>

<head>
<title>Esta es mi Primera p√°gina web </title>
</head>

<body>
<?php $var="David Torres";
$num1=2;
$num2=1; ?>
<table border="3" align="center">

<tr>
  <td colspan="2" align="center"><h1><b>DATOS PERSONALES<b></h1>
<tr>
<td><i>Nombre</td>
<td><?php echo 'Hola '.$var;
$retval='Hola '.$var;
 ?></td>
</tr>
<tr>
<td><i>Fecha</td>
<td><?php echo date('D/M/Y');
$retval.='<br>'.date('D/M/Y');  ?></td>
</tr>
<tr>
<td><i>Edad</td>
<td><?php echo "26";
$retval.='<br>'."26" ?></td>
</tr>
<tr>
<td><i>Profesi√≥n</td>
<td><?php echo "Ciudadano del mundo";?></td>
</tr>
<tr>
<td><?php echo "Resultado Varieble retval"?></td>
<td>
<?php $retval.="<br>"."ciudadano del mundo";
echo "variable retval =".$retval?></td>
</tr>
<tr>
	<td>Tipo de variable nombre</td>
	<td><?php echo gettype($var); ?>
	</tr>
<tr>
	<td>Imprimir arreglo</td>
	<td><?php echo '<pre>';
	print_r($_SERVER);
	echo '</pre>';?></td>
	</tr>
	<tr>
		<td>If Chiquito</td>
		<td><?php echo  $num=$num1>0? "es mayor":"es menor"; ?></td> 
	</tr>
	<tr><td>Tipo de variable num1 y valor</td>
		<td><?php echo gettype($num1); echo $num1;?></td>
	</tr>
</tr>
<td>Lo Mismo con IF</td>
<td><?php if($num1>0){
	echo "es mayor";
}else{
		echo " es menor";
	}
	?>
</td>
<tr>
<td>Programa para invertir una cadena [hola]</td>
<td>
<?php
$arreglo='hola';
echo $arreglo;

?>
</td>
</tr>
</tr>

</table>
</body>
</html>
