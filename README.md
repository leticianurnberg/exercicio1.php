<?php
print "digite a quantidade de metros que você deseja converter para milimetros:";
$metros =  (int)  fgets (STDIN) ;
$mili=  $metros * 1000;
print "  Sua conversão resultou em $mili  ";
