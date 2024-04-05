# Basic PHP conceptual/ interview preparation
Basic PHP interview questions with an explanation

### Table of Contents
  | Keyword          | Question                                        |
  |------------------|-------------------------------------------------|
  | basic php  | [ Which programming language does PHP resemble?](#basicphp1) |
  | basic php  | [ What does PEAR stand for?](#basicphp2) |
  | basic php  | [ What is the actually used PHP version ?](#basicphp3) |
  | basic php  | [ How do you execute a PHP script from the command line ?](#basicphp4) |
  | basic php  | [ How to run the interactive PHP shell from the command line interface ?](#basicphp5) |
  | basic php  | [ What is the correct and the most two common way to start and finish a PHP block of code ?](#basicphp6) |
  | basic php  | [ How can we display the output directly to the browser ?](#basicphp7) |
  | basic php  | [ Is multiple inheritance supported in PHP ?](#basicphp8) |
  | basic php  | [ What is the meaning of a final class and a final method ?](#basicphp9) |
  | basic php  | [ How is the comparison of objects done in PHP ?](#basicphp10) |
  | basic php  | [ What type of operation is needed when passing values through a form or a URL ?](#basicphp11) |
  | basic php  | [ How are failures in execution handled with include() and require() functions ?](#basicphp12) |
  | basic php  | [ What is the main difference between require() and require_once() ?](#basicphp13) |
  | basic php  | [ How can I display text with a PHP script ?](#basicphp14) |
  | basic php  | [ How can we display information of a variable and readable by a human with PHP?](#basicphp15) |
  | basic php  | [ How is it possible to set an infinite execution time for a PHP script ?](#basicphp16) |
  | basic php  | [ What does the PHP error 'Parse error in PHP – unexpected T_variable at line x' mean ?](#basicphp17) |
  | basic php  | [ What is the static variable in a function useful for?](#basicphp18) |
  | basic php  | [ How can we define a variable accessible in functions of a PHP script ?](#basicphp19) |
  | basic php  | [ How is it possible to return a value from a function?](#basicphp20) |
  | basic php  | [ How is a constant defined in a PHP script ?](#basicphp21) |
  | basic php  | [ How can you pass a variable by reference ?](#basicphp22) |
  | basic php  | [Will a comparison of an integer and a string "" work in PHP ?](#basicphp23) |
  | basic php  | [How is it possible to cast types in PHP ?](#basicphp24) |
  | basic php  | [When is a conditional statement ended with endif ?](#basicphp25) |
  | basic php  | [How is the ternary conditional operator used in PHP ?](#basicphp26) |
  | basic php  | [What is the function func_num_args() used for?](#basicphp27) |
  | basic php  | [What does $GLOBALS mean ?](#basicphp28) |
  | basic php  | [What does $_SERVER mean?](#basicphp29) |
  | basic php  | [What does $_FILES mean ?](#basicphp30) |
  | basic php  | [What is the difference between $_FILES'userfile''name' and $_FILES'userfile''tmp_name' ?](#basicphp31) |
  | basic php  | [How can we get the error when there is a problem uploading a file ?](#basicphp32) |
  | basic php  | [How can we change the maximum size of the files to be uploaded ?](#basicphp33) |
  | basic php  | [What does $_ENV mean ?](#basicphp34) |
  | basic php  | [What does $_COOKIE mean ?](#basicphp35) |
  | basic php  | [What does the scope of variables mean ?](#basicphp36) |
  | basic php  | [What is the difference between the 'BITWISE AND' operator and the 'LOGICAL AND' operator ?](#basicphp37) |
  | basic php  | [What are the two main string operators ?](#basicphp38) |
  | basic php  | [What does the array operator '===' mean ?](#basicphp39) |
  | basic php  | [What is the difference between $a != $b and $a !== $b ?](#basicphp40) |
  | basic php  | [What is the goto statement useful for?](#basicphp41) |
  | basic php  | [How is it possible to parse a configuration file ?](#basicphp42) |
  | basic php  | [How can we check if the value of a given variable is a number ?](#basicphp43) |
  | basic php  | [How can we check if the value of a given variable is alphanumeric ?](#basicphp44) |
  | basic php  | [How do I check if a given variable is empty ?](#basicphp45) |
  | basic php  | [What does the unset() function mean?](#basicphp46) |
  | basic php  | [How is it possible to remove escape characters from a string ?](#basicphp47) |
  | basic php  | [How can we determine whether a variable is set ?](#basicphp48) |
  | basic php  | [What is the difference between the functions strstr() and stristr()?](#basicphp49) |
  | basic php  | [What is the difference between for and foreach ?](#basicphp50) |
  | basic php  | [What is the difference between ereg_replace() and eregi_replace()?](#basicphp51) |
  | basic php  | [What are the three classes of errors that can occur in PHP?](#basicphp52) |
  | basic php  | [What is the difference between characters \ and \x ?](#basicphp53) |
  | basic php  | [How can we pass a variable through navigation between pages?](#basicphp54) |
  | basic php  | [Is it possible to extend the execution time of a PHP script ?](#basicphp55) |
  | basic php  | [What is the purpose of the unset() function in PHP ?](#basicphp56) |
  | basic php  | [What is the purpose of the json_encode() function in PHP ?](#basicphp57) |
  | basic php  | [What is the purpose of the require_once() function in PHP ?](#basicphp58) |
  | basic php  | [What is the purpose of the strlen() function in PHP ?](#basicphp59) |
  | basic php  | [How can you check if a file exists in PHP ?](#basicphp60) |
  | basic php  | [What is the purpose of the array_push() function in PHP ?](#basicphp61) |
  | basic php  | [What is the purpose of the array_merge() function in PHP ?](#basicphp62) |
  | basic php  | [What is the purpose of the substr() function in PHP ?](#basicphp63) |
  | basic php  | [What is the purpose of the array_search() function in PHP ?](#basicphp64) |
  | basic php  | [What is the purpose of the array_keys() function in PHP ?](#basicphp65) |
  | basic php  | [What is the purpose of the array_unique() function in PHP ?](#basicphp66) |
  | basic php  | [What is the purpose of the array_reverse() function in PHP?](#basicphp67) |
  | basic php  | [What is the purpose of the is_numeric() function in PHP ?](#basicphp68) |
  | basic php  | [Which of the following best describes PHP ?](#basicphp69) |
  | basic php  | [PHP is a server-side ______ language.](#basicphp70) |
  | basic php  | [PHP can be embedded within HTML code.](#basicphp71) |
  | basic php  | [PHP is a client - side scripting language.](#basicphp72) |
  | basic php  | [Which of the following are advantages of using PHP?](#basicphp73) |
  | basic php  | [You want to embed PHP code within your HTML.How would you do this ?](#basicphp74) |
  | basic php  | [Which of the following is necessary to run PHP scripts on your local machine ?](#basicphp75) |
  | basic php  | [The PHP files should be saved with a ______ extension for the server to parse them.](#basicphp76) |
  | basic php  | [PHP requires a web server to run PHP scripts.](#basicphp77) |
  | basic php  | [Comments in PHP can be used to leave notes in the code for other developers.](#basicphp78) |
  | basic php  | [The PHP interpreter executes comments as part of the script.](#basicphp79) |
  | basic php  | [Which of the following are reasons to use comments in PHP code ?](#basicphp80) |
  | basic php  | [Which of the following are valid ways to add comments to PHP code ?](#basicphp81) |
  | basic php  | [Which of the following are true about comments in PHP ?](#basicphp82) |
  | basic php  | [Which of the following are reasons to use comments in PHP code ?](#basicphp83) |
  | basic php  | [Which of the following are valid ways to add comments to PHP code ?](#basicphp84) |
  | basic php  | [Which of the following are true about comments in PHP?](#basicphp85) |
  | basic php  | [How do PHP statements end ?](#basicphp86) |
  | basic php  | [How are comments in PHP denoted ?](#basicphp87) |
  | basic php  | [PHP code is enclosed in ______ and ______ tags.](#basicphp88) |
  | basic php  | [In PHP, a line of code is terminated with a ______.](#basicphp89) |
  | basic php  | [PHP allows for both single - line and multi - line comments.](#basicphp90) |
  | basic php  | [Which of the following are valid ways to denote a comment in PHP ?](#basicphp91) |
  | basic php  | [You want to include a note in your PHP code for other developers, but you don't want this note to affect the execution of the script. How would you do this?](#basicphp92) |
  | basic php  | [How is a single - line comment denoted in PHP ?](#basicphp93) |
  | basic php  | [How is a multi - line comment denoted in PHP ?](#basicphp94) |
  | basic php  | [Which of the following is not a valid way to denote a comment in PHP ?](#basicphp95) |
  | basic php  | [To make a single-line comment in PHP, you can use ______ or ______ at the beginning of the line.](#basicphp96) |
  | basic php  | [Multi - line comments in PHP start with ______ and end with ______.](#basicphp97) |
  | basic php  | [Comments in PHP code are ignored by the ______.](#basicphp98) |
  | basic php  | [Which of the following is used in PHP to output one or more strings ?](#basicphp99) |
  | basic php  | [What is the key difference between echo and print in PHP ?](#basicphp100) |
  | basic php  | [Which of the following statements in PHP can output strings, variables, and HTML code ?](#basicphp101) |
  | basic php  | [In PHP, the ______ statement can output one or more strings.](#basicphp102) |
  | basic php  | [The ______ statement in PHP is not actually a function, so you can use it without parentheses.](#basicphp103) |
  | basic php  | [The print statement in PHP always returns ______.](#basicphp104) |
  | basic php  | [In PHP, both echo and print can output strings, variables, and HTML code.](#basicphp105) |
  | basic php  | [The print statement in PHP can output multiple parameters at once.](#basicphp106) |
  | basic php  | [echo and print are functions in PHP.](#basicphp107) |
  | basic php  | [Which of the following are true about the echo statement in PHP?](#basicphp108) |
  | basic php  | [Which of the following are true about the print statement in PHP?](#basicphp109) |
  | basic php  | [Which of the following can be done using either echo or print in PHP?](#basicphp110) |
  | basic php  | [You want to output a variable's value along with some text in PHP. How would you use echo or print to do this?](#basicphp111) |
  | basic php  | [You need to output a large block of HTML code in your PHP script.Which statement would be more suitable, echo or print, and why ?](#basicphp112) |
  | basic php  | [You are debugging a PHP script and you need to check the value of a variable at a certain point in the script. How would you use echo or print to do this?](#basicphp113) |
  | basic php  | [What is the concatenation operator in PHP?](#basicphp114) |
  | basic php  | [Which of the following functions can be used in PHP to find the length of a string?](#basicphp115) |
  | basic php  | [How are strings defined in PHP?](#basicphp116) |
  | basic php  | [The ______ function in PHP is used to return the length of a string.](#basicphp117) |
  | basic php  | [In PHP, the ______ function is used to replace some characters in a string with some other characters.](#basicphp118) |
  | basic php  | [To concatenate two strings in PHP, you use the ______ operator.](#basicphp119) |
  | basic php  | [In PHP, strings can be defined using either single quotes or double quotes.](#basicphp120) |
  | basic php  | [The strlen() function in PHP can be used to find the number of words in a string.](#basicphp121) |
  | basic php  | [In PHP, the str_replace() function is case-sensitive.](#basicphp122) |
  
  
  
  
