# phpDoc

### Variable declaratrion

    <!DOCTYPE html>
    <html lang="en">
        <head>
            <meta charset="UTF-8">
            <meta name="viewport" content="width=device-width, initial-scale=1.0">
            <title>Document</title>
        </head>
        <body>
            <?php

                $firstName = "sourav";
                $lastName = "majumder";
                $age = 24;
                $gender = true;

                echo $gender;

                echo "Hello $firstName $lastName, you age is $age";

                echo "Hello ".$firstName.$lastName.",your age is".$age;
            ?>
        </body>
    </html>

### $$variable

    $firstName = "sourav";
    $lastName = "firstName";

    echo $$lastName   [output -- sourav]

steps of compile,

    $firstName  ; since $lastName = "firstName"
    Now just put the value of $firstName. so o/p is sourav
