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
  | basic php  | [Which of the following are valid ways to define a string in PHP?](#basicphp123) |
  | basic php  | [Which of the following functions in PHP can be used to manipulate strings?](#basicphp124) |
  | basic php  | [Which of the following are true about strings in PHP?](#basicphp125) |
  | basic php  | [You are writing a PHP script and you need to combine two strings into one. How would you do this?](#basicphp126) |
  | basic php  | [You have a string in your PHP script and you want to find out how many characters it has. How would you do this?](#basicphp127) |
  | basic php  | [You need to replace a certain word in a string in your PHP script. How would you do this?](#basicphp128) |
  | basic php  | [Which PHP function checks if a variable is a number or a numeric string?](#basicphp129) |
  | basic php  | [Which of the following is used in PHP to declare a floating-point number?](#basicphp130) |
  | basic php  | [The is_numeric() function in PHP checks if a variable is a(n) ______.](#basicphp131) |
  | basic php  | [In PHP, integers can be specified in decimal (base 10), hexadecimal (base 16), octal (base 8), and ______ (base 2) format.](#basicphp132) |
  | basic php  | [PHP supports two types of numbers: integers and ______.](#basicphp133) |
  | basic php  | [In PHP, a number must be within a certain range to be considered an integer.](#basicphp134) |
  | basic php  | [The is_float() function in PHP checks if a variable is an integer.](#basicphp135) |
  | basic php  | [In PHP, a number with a decimal point or an exponential form is considered a float.](#basicphp136) |
  | basic php  | [Which of the following are valid ways to specify an integer in PHP?](#basicphp137) |
  | basic php  | [Which of the following functions in PHP can be used to check the type of a number ?](#basicphp138) |
  | basic php  | [Which of the following are true about numbers in PHP?](#basicphp139) |
  | basic php  | [You are writing a PHP script and you need to check if a variable contains a numeric value. How would you do this?](#basicphp140) |
  | basic php  | [You need to store a price, which includes cents, in a variable in your PHP script. What type of number would you use and why?](#basicphp141) |
  | basic php  | [You need to check if a variable in your PHP script is an integer. How would you do this?](#basicphp142) |
  | basic php  | [What PHP function is used to return the highest value from a list of numbers?](#basicphp143) |
  | basic php  | [Which PHP function returns the square root of a number?](#basicphp144) |
  | basic php  | [What is the function to round a floating-point number in PHP?](#basicphp145) |
  | basic php  | [The max() function in PHP returns the ______ value from a list of numbers.](#basicphp146) |
  | basic php  | [In PHP, the sqrt() function returns the square root of a(n) ______.](#basicphp147) |
  | basic php  | [The round() function in PHP rounds a floating point number to the nearest ______.](#basicphp148) |
  | basic php  | [The min() function in PHP returns the ______ value from a list of numbers.](#basicphp149) |
  | basic php  | [The rand() function in PHP returns a ______ integer.](#basicphp150) |
  | basic php  | [The ceil() function in PHP rounds a number up to the nearest ______.](#basicphp151) |
  | basic php  | [Which of the following are valid PHP Math functions?](#basicphp152) |
  | basic php  | [Which of the following functions in PHP can be used to round a number?](#basicphp153) |
  | basic php  | [Which of the following are true about PHP Math functions?](#basicphp154) |
  | basic php  | [You are writing a PHP script and you need to find the highest value in a list of numbers. How would you do this?](#basicphp155) |
  | basic php  | [You need to generate a random number in your PHP script. What function would you use and why?](#basicphp156) |
  | basic php  | [You have a floating-point number in your PHP script and you need to round it to the nearest integer. How would you do this?](#basicphp157) |
  | basic php  | [Which PHP function is used to create a constant?](#basicphp158) |
  | basic php  | [In PHP, constant identifiers are always case-______.](#basicphp159) |
  | basic php  | [Unlike variables, constants in PHP are automatically ______.](#basicphp160) |
  | basic php  | [In PHP, constants are defined using the ______ function.](#basicphp161) |
  | basic php  | [Once a constant is set in PHP, it cannot be ______ or ______.](#basicphp162) |
  | basic php  | [In PHP, the ______ function checks if a constant with a given name exists.](#basicphp163) |
  | basic php  | [PHP constants are case -_________.](#basicphp164) |
  | basic php  | [Once a constant is defined in PHP, it ______ be changed during the execution of the script.](#basicphp165) |
  | basic php  | [Constants in PHP can be defined and accessed anywhere in the script without regard to ______ rules.](#basicphp166) |
  | basic php  | [Which of the following are true about constants in PHP?](#basicphp167) |
  | basic php  | [Which of the following PHP functions are related to constants?](#basicphp168) |
  | basic php  | [Which of the following are differences between variables and constants in PHP?](#basicphp169) |
  | basic php  | [You are writing a PHP script and you need to set a value that should not change throughout the execution of the script. How would you do this?](#basicphp170) |
  | basic php  | [You want to check if a certain constant has been defined in your PHP script. How would you do this?](#basicphp171) |
  | basic php  | [You need to define a constant in your PHP script that can be accessed anywhere in the script, regardless of scope. How would you do this?](#basicphp172) |
  | basic php  | [What is the operator used for addition in PHP?](#basicphp173) |
  | basic php  | [Which of the following is a comparison operator in PHP?](#basicphp174) |
  | basic php  | [What is the purpose of the assignment operators in PHP?](#basicphp175) |
  | basic php  | [The + operator in PHP is used for ______.](#basicphp176) |
  | basic php  | [The == operator in PHP is a type of ______ operator.](#basicphp177) |
  | basic php  | [The = operator in PHP is a type of ______ operator.](#basicphp178) |
  | basic php  | [In PHP, the * operator is used for ______.](#basicphp179) |
  | basic php  | [The === operator in PHP checks if the values of two operands are ______ and of the ______ type.](#basicphp180) |
  | basic php  | [The && operator in PHP is an example of a ______ operator.](#basicphp181) |
  | basic php  | [You are writing a PHP script and you need to add the values of two variables. How would you do this using operators?](#basicphp182) |
  | basic php  | [You need to compare two variables in your PHP script to check if they are equal. What operator would you use and why?](#basicphp183) |
  | basic php  | [What is the purpose of the if statement in PHP?](#basicphp184) |
  | basic php  | [What is the else statement used for in PHP?](#basicphp185) |
  | basic php  | [In PHP, the if statement is used to execute some code if a ______ is true.](#basicphp186) |
  | basic php  | [The else statement in PHP is used to execute some code if the same ______ is false.](#basicphp187) |
  | basic php  | [The elseif statement in PHP is used to specify a new condition to test if the first condition is ______.](#basicphp188) |
  | basic php  | [The else statement in PHP can only be used after an if statement.](#basicphp189) |
  | basic php  | [The elseif statement in PHP can be used to test multiple conditions.](#basicphp190) |
  | basic php  | [Which of the following are true about the if statement in PHP?](#basicphp191) |
  | basic php  | [Which of the following are true about the else statement in PHP?](#basicphp192) |
  | basic php  | [Which of the following are true about the elseif statement in PHP?](#basicphp193) |
  | basic php  | [You are writing a PHP script and you need to execute some code only if a certain condition is met. How would you do this using an if statement?](#basicphp194) |
  | basic php  | [You want to execute some code in your PHP script if a certain condition is not met. How would you do this using an else statement?](#basicphp195) |
  | basic php  | [You have multiple conditions in your PHP script and you want to test each one in order. How would you do this using if, elseif, and else statements?](#basicphp196) |
  | basic php  | [What is the purpose of the switch statement in PHP ?](#basicphp197) |
  | basic php  | [In a PHP switch statement, what does the case keyword represent?](#basicphp198) |
  | basic php  | [What is the default keyword used for in a PHP switch statement?](#basicphp199) |
  | basic php  | [The switch statement in PHP is used to select one of many blocks of code to be executed.](#basicphp200) |
  | basic php  | [In a PHP switch statement, the case keyword is followed by a value to compare against the expression.](#basicphp201) |
  | basic php  | [The default keyword in a PHP switch statement specifies the code to execute if there is no matching case.](#basicphp202) |
  | basic php  | [The switch statement in PHP can only test a single condition.](#basicphp203) |
  | basic php  | [The case keyword in a PHP switch statement represents a possible value for the expression.](#basicphp204) |
  | basic php  | [The default keyword in a PHP switch statement is optional.](#basicphp205) |
  | basic php  | [Which of the following are true about the switch statement in PHP?](#basicphp206) |
  | basic php  | [Which of the following are true about the case keyword in a PHP switch statement?](#basicphp207) |
  | basic php  | [Which of the following are true about the default keyword in a PHP switch statement?](#basicphp208) |
  | basic php  | [You are writing a PHP script and you have a variable that can have many different values. You want to execute different blocks of code depending on the value of this variable. How would you do this using a switch statement?](#basicphp209) |
  | basic php  | [You have a switch statement in your PHP script and you want to specify what code to execute if none of the cases match the expression. How would you do this using the default keyword?](#basicphp210) |
  | basic php  | [You are using a switch statement in your PHP script and you want to execute the same block of code for multiple cases. How would you do this?](#basicphp211) |
  | basic php  | [What is the purpose of a loop in PHP?](#basicphp212) |
  | basic php  | [Which PHP loop will execute a block of code at least once, then it will repeat the loop as long as the condition is true?](#basicphp213) |
  | basic php  | [Which PHP loop is suitable when you want to iterate over a block of code for a known number of times?](#basicphp214) |
  | basic php  | [The for loop in PHP is used when you want to loop through a block of code a specific number of ______.](#basicphp215) |
  | basic php  | [The while loop in PHP will continue to execute a block of code as long as the ______ is true.](#basicphp216) |
  | basic php  | [The do...while loop in PHP will always execute the block of code at least ______, then it will repeat the loop as long as the condition is true.](#basicphp217) |
  | basic php  | [The foreach loop in PHP is used exclusively for ______.](#basicphp218) |
  | basic php  | [In PHP, the while loop tests the condition ______ executing the block of code.](#basicphp219) |
  | basic php  | [The do...while loop in PHP tests the condition ______ executing the block of code.](#basicphp220) |
  | basic php  | [Which of the following are types of loops in PHP?](#basicphp221) |
  | basic php  | [Which of the following PHP loops checks the condition before the loop has run?](#basicphp222) |
  | basic php  | [Which of the following are true about loops in PHP?](#basicphp223) |
  | basic php  | [You are writing a PHP script and you want to execute a block of code a certain number of times. Which type of loop would you use and why?](#basicphp224) |
  | basic php  | [You have an array in your PHP script and you want to execute a block of code for each element in the array. Which type of loop would you use and why?](#basicphp225) |
  | basic php  | [You need to execute a block of code at least once in your PHP script, then repeat it as long as a certain condition is true. Which type of loop would you use and why?](#basicphp226) |
  | basic php  | [What is the while loop used for in PHP?](#basicphp227) |
  | basic php  | [In a PHP while loop, where is the condition tested?](#basicphp228) |
  | basic php  | [What happens if the condition in a PHP while loop is never false?](#basicphp229) |
  | basic php  | [The while loop in PHP will continue to execute a block of code as long as the ______ is true.](#basicphp230) |
  | basic php  | [In a PHP while loop, the condition is tested ______ the code block is executed.](#basicphp231) |
  | basic php  | [If the condition in a PHP while loop is never false, the loop will ______.](#basicphp232) |
  | basic php  | [The while loop in PHP tests the condition ______ executing the block of code.](#basicphp233) |
  | basic php  | [In PHP, if the condition in a while loop is never false, the loop will ______.](#basicphp234) |
  | basic php  | [A PHP while loop will always execute its block of code ______.](#basicphp235) |
  | basic php  | [Which of the following are true about the while loop in PHP?](#basicphp236) |
  | basic php  | [What can be the potential issues with a while loop in PHP?](#basicphp237) |
  | basic php  | [Which of the following are common uses of while loops in PHP?](#basicphp238) |
  | basic php  | [You are writing a PHP script and you want to execute a block of code as long as a certain condition is true. How would you do this using a while loop?](#basicphp239) |
  | basic php  | [You have a while loop in your PHP script that is not terminating as expected. What could be the possible reasons and how would you debug this?](#basicphp240) |
  | basic php  | [You need to execute a block of code in your PHP script for an unknown number of times, but at least once. How would you do this using a while loop and why might you choose it over a for loop?](#basicphp241) |
  | basic php  | [What is the do...while loop used for in PHP?](#basicphp242) |
  | basic php  | [In a PHP do...while loop, where is the condition tested?](#basicphp243) |
  | basic php  | [How many times will the block of code in a PHP do...while loop execute at a minimum?](#basicphp244) |
  | basic php  | [The do...while loop in PHP will execute a block of code once, and then continue executing it as long as the ______ is true.](#basicphp245) |
  | basic php  | [In a PHP do...while loop, the condition is tested ______ the code block is executed.](#basicphp246) |
  | basic php  | [A PHP do...while loop will always execute its block of code at least ______ times.](#basicphp247) |
  | basic php  | [When is the elseif statement used in PHP?](#basicphp248) |
  | basic php  | [The do...while loop in PHP tests the condition before executing the block of code.](#basicphp249) |
  | basic php  | [In a PHP do...while loop, if the condition is never true, the loop will still execute once.](#basicphp250) |
  
  
  
  
  
  
