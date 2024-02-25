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

#### Now how to use this connection with php page for data CRUD

first need to include 'function.php' page for database connection with current page.

##### Code for add data to the database

![Screenshot from 2024-02-25 13-50-16](https://github.com/s0urav6529/phpDoc/assets/96060029/9a2bbcaa-3dec-4fa7-804f-23c5817e140c)

![Screenshot from 2024-02-25 13-51-18](https://github.com/s0urav6529/phpDoc/assets/96060029/1b892f61-b705-46bb-b132-af282d0eb44e)

##### Code for display data in the table

![Screenshot from 2024-02-25 13-58-07](https://github.com/s0urav6529/phpDoc/assets/96060029/eb8e6b40-ce8b-4768-8a33-e7dfb11d4c54)

![Screenshot from 2024-02-25 13-56-48](https://github.com/s0urav6529/phpDoc/assets/96060029/3c2c4b2a-07df-4412-aa14-a2df81dc0d64)

##### display data in the table

![Screenshot from 2024-02-25 14-03-46](https://github.com/s0urav6529/phpDoc/assets/96060029/881ce324-ca46-401b-acac-6c8f65a87b21)

![Screenshot from 2024-02-25 14-03-15](https://github.com/s0urav6529/phpDoc/assets/96060029/8fd16248-c41c-4cff-a6ed-1c054fe7c549)

##### delete the data

![Screenshot from 2024-02-25 16-04-50](https://github.com/s0urav6529/phpDoc/assets/96060029/5bc862cb-4bf0-49a4-a952-bc927440cebd)

![Screenshot from 2024-02-25 16-07-01](https://github.com/s0urav6529/phpDoc/assets/96060029/1b1c6d98-f4fa-4530-b259-a52c401c2823)

![Screenshot from 2024-02-25 16-08-00](https://github.com/s0urav6529/phpDoc/assets/96060029/3e792940-178b-4184-b8b1-bafb52ef2cde)
