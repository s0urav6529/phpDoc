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

            <h1>Hello <?php echo $firstName; ?> </h1>

        </body>
    </html>

### $$variable

    $firstName = "sourav";
    $lastName = "firstName";

    echo $$lastName   [output -- sourav]

steps of compile,

    $firstName  ; since $lastName = "firstName"
    Now just put the value of $firstName. so o/p is sourav

### constant

    define("name","Sourav Majumder");
    define("age",24);

    echo name;
    echo "<br>";
    echo age;

    or

    echo "My name is ".name.", my age is".age;

    or echo constant("name");

### File in Form

![Screenshot from 2024-02-25 12-53-19](https://github.com/s0urav6529/phpDoc/assets/96060029/59eb630c-10e6-4821-b44c-d828b7c95b5d)

for retrive the file

![Screenshot from 2024-02-25 12-55-42](https://github.com/s0urav6529/phpDoc/assets/96060029/868f519a-9eb1-4a35-bb0a-d01efe9946bc)

### Database connection to php

![Screenshot from 2024-02-25 13-27-28](https://github.com/s0urav6529/phpDoc/assets/96060029/7a002f2c-2ce0-45fb-b41b-c5632b18b2cd)

![Screenshot from 2024-02-25 13-41-53](https://github.com/s0urav6529/phpDoc/assets/96060029/3b94f9bf-9b95-4b70-a463-d5b427be0916)
