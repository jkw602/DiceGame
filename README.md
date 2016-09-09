# DiceGame

$Counter=0
$Die1=0
$Die2=0
$Score=0

Write "This is a Dice Simulator"
While ($Score-ne12)
{
  $Counter+=1
  $Die1=get-random-minimum1-maximum6
  $Die2=get-random-minimum1-maximum6
  $Score=$Die1+$Die2
  Write "Rolled a $Die1 and $Die2"
  Write "Total score was $Score"
}

Write "It took $Counter rolls to get a 12"
  
