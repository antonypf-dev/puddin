## About You.

I am antony pf, Software developer with an experience in the field of Angular JS and core PHP for more than 1 year. I completed my btech in cs in 2018 and joined as a trainee in kingslabs technologies and later continued in the same firm as a developer. 
A word about my personal life, i am from vyppin,kochi and like gaming,travelling and badminton

OS:- linux(14.04+),windows 10
IDE & Editor:- visual studio code,notepad++
Config manager:- xampp

## Social Profile
Gitlab Profile url:- https://gitlab.com/antonypf
github Profile url:- https://github.com/antonypf-dev/puddin
LinkedIn profile:- https://www.linkedin.com/in/antony-p-f-0773b6184

## The real stuff.

1. Linux, Apache, mySQL, PHP, Laravel, Angular 8 
<!--
2. <body>
    <form method="post">
        <table border="0" align="center">
            <tr>
                <td>Enter Your Numbers</td>
                <Td><input type="text" name="num" value="<?php if(isset($num)){echo $num;}?>" /></Td>
            </tr>
            <tr>
                <td colspan="2" align="center">
                    <input type="submit" value="Conver Number to Array" name="convert" />
                </td>
            </tr>
        </table>
    </form>
</body>

<?php 
function NumbertoArray ($number){
    $nu = str_split($number);
    $array = "{";
    for($i=0;$i<sizeof($nu)-1;$i++){
        $array .= $nu[$i].", ";
    }
    $array .=$nu[$i]."}";
    // $array = [];
    // $array  = array_map('intval', str_split($number));
    // var_dump($array);
    //the comment portion will result array(4) { [0]=> int(9) [1]=> int(8) [2]=> int(5) [3]=> int(6) } 
    return $array;
}
extract($_POST);
if(isset($convert))
{
    echo "<p align='center' style='color:red'>".$num."</p>";
    echo "<p align='center' style='color:blue'>".NumbertoArray("$num")."</p>";
}
?>
3. <body>
    <form method="post">
        <table border="0" align="center">
            <tr>
                <td>Enter Your String</td>
                <Td><input type="text" name="str" value="<?php if(isset($str)){echo $str;}?>" /></Td>
            </tr>
            <tr>
                <td colspan="2" align="center">
                    <input type="submit" value="Text to Pig Latin" name="convert" />
                </td>
            </tr>
        </table>
    </form>
</body>

<?php 
function TexttoPigLatin ($str){
    $string = str_word_count($str,1);
    $len =  count($string);
    $s = array();
    for($i=0;$i<$len;$i++){
        for($j=1;$j<=strlen($string[$i]);$j++){
            $s[$i] .= $string[$i][$j];
        }
        $s[$i] .= $string[$i][0]."ay ";
        $strr .="".$s[$i]."";
    }
    return $strr;
}
extract($_POST);
if(isset($convert))
{
    echo "<p align='center' style='color:red'>".$str."</p>";
    echo "<p align='center' style='color:blue'>".TexttoPigLatin("$str")."</p>";
}
?>
4. <body>
    <form method="post">
        <table border="0" align="center">
            <tr>
                <td>Enter Your Array</td>
                <Td><input type="text" name="str" value="<?php if(isset($str)){echo $str;}?>" /></Td>
            </tr>
            <tr>
                <td>Enter k elements to rotate</td>
                <Td><input type="text" name="rot" value="<?php if(isset($rot)){echo $rot;}?>" /></Td>
            </tr>
            <tr>
                <td colspan="2" align="center">
                    <input type="submit" value="Text to Pig Latin" name="convert" />
                </td>
            </tr>
        </table>
    </form>
</body>

<?php 
function RotateArray ($str,$rot){
    $str = preg_split('/[\ \n\,]+/',$str);
    $len = sizeof($str); 
    for($i=0;$i<$rot;$i++){
        $temp = $str[0]; 
        for($j = 0;$j < $len - 1;$j++) {
            $str[$j] = $str[$j + 1]; 
        }
        $str[$j] = $temp; 
    }
    for ($j = 0; $j < $len; $j++) {
        $strr .="".$str[$j].", ";
    }

   
    return $strr;
}
extract($_POST);
if(isset($convert))
{
    echo "<p align='center' style='color:red'>".$str."</p>";
    echo "<p align='center' style='color:blue'>".RotateArray("$str","$rot")."</p>";
}
?>
-->
