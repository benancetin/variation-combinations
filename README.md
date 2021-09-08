# Combinations

To take the combination of two array this function can be used. (Ex: Colour and size for e-commerce websites.)

Ex Output;

$combinations = get_combinations(
    array(
        'item1' => array('A','B','C'),
        'item2' => array('X', 'Y'),
    )
);

var_dump($combinations);

Output: 
array(6) {
  [0]=>
  array(2) {
    ["item1"]=>
    string(1) "A"
    ["item2"]=>
    string(1) "X"
  }
  [1]=>
  array(2) {
    ["item1"]=>
    string(1) "A"
    ["item2"]=>
    string(1) "Y"
  }
  [2]=>
  array(2) {
    ["item1"]=>
    string(1) "B"
    ["item2"]=>
    string(1) "X"
  }
  [3]=>
  array(2) {
    ["item1"]=>
    string(1) "B"
    ["item2"]=>
    string(1) "Y"
  }
  [4]=>
  array(2) {
    ["item1"]=>
    string(1) "C"
    ["item2"]=>
    string(1) "X"
  }
  [5]=>
  array(2) {
    ["item1"]=>
    string(1) "C"
    ["item2"]=>
    string(1) "Y"
  }
}
