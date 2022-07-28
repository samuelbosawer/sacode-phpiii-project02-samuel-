# sacode-phpiii-project02-samuel
### Belajar tipe data PHP
	✅ String
	✅ Integer
	✅ Float 
	✅ Array 
	✅ Boolean
	✅ Null
	✅ Object 

### String 

```php
<?php 

	$a = "Hello Word";
	$b = 'Hello Word';

	echo $a.'<br>'.$b;
	echo "<br>";
	echo $a;
	// echo "<br>";
	
?>
```

### Integer

```php
<?php 

$x = 23;
echo $x;
echo "<br>";
var_dump($x);

?>
```

### Float

```php
<?php 
$x = 10.134;
var_dump($x);

?>
```

### Boolean

```php
<?php
	$x = true;
	$y = false;
	var_dump($x);
?>
```

### Null

```php
<?php
	$x = 'Hello Word';
	$x = null;
	$y = null;
	$y = 'SaCode';
	var_dump($y);
	$y = 12;
	echo $y;
	var_dump($y);
	$y = null;
	var_dump($y);
?>
```

### Object

```php
<?php 
class Car {
	public $color;
	public $model;
	public function __construct($color, $model)
	{
		$this->color = $color;
		$this->model = $model;
	}

	public function message(){
		return "My Car is a " . $this->color. " ". $this->model."!";
	}
}

$myCar = new Car("black", "Volvo");
echo $myCar->message();
echo "<br>";
$myCar = new Car('Red', "Toyota");
echo $myCar->message();
?>
```




