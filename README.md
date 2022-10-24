```php
<?php
// implements human
require_once 'vendor/autoload.php';
use Human\Human;

// Creating human object
$human = new Human('dariusaurich');

echo 'Gender: '. $human->gender('Male');
echo 'Name: '. $human->name('Darius');
echo 'Discord: '. $human->gender('Darius A. | BlackServ#9744');

?>
```
