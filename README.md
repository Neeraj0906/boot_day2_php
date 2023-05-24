# boot_day2_php
<?php

function findLargest($num1, $num2, $num3) {
    $largest = $num1;

    if ($num2 > $largest) {
        $largest = $num2;
    }

    if ($num3 > $largest) {
        $largest = $num3;
    }

    return $largest;
}

// Example usage
$num1 = 10;
$num2 = 20;
$num3 = 30;

$largestNumber = findLargest($num1, $num2, $num3);
echo "The largest number is: " . $largestNumber;


?>
