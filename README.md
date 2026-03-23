<?php

$peso= 80;
$altura= 1.63;

$imc=$peso/($altura**2);
echo "O IMC É: $imc";

Echo "<p>";
if($imc <16){

echo "Magreza grau III."; 

}elseif ($imc >16 && $imc<16.9) {
    echo "Magreza grau II.";

} elseif ($imc >17 && $imc<18.4) {
    echo "Magreza grau I.";

} elseif ($imc >18.5 && $imc<24.9) {
    echo "Eutrofia.";

} elseif ($imc >25 && $imc<29.9) {
    echo "Pré-obesidade.";

} elseif ($imc >30 && $imc<34.9) {
    echo "Obesidade Moderada (grau I).";

} elseif ($imc >35 && $imc<39.9) {
    echo "Obesidade Severa (grau II).";

} elseif ($imc >35 && $imc<39.9) {
    echo "Obesidade Severa (grau II).";

}else {
    echo "Obesidade muito Severa (grau III).";
}

?>
