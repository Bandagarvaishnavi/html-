# html-
html page where i used all the keys, attributes, to create a small page to take input of persons details. 
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>LUCKY DRAW</i></title>
</head>
<body>
    <form action =" " > 
        <h1>ENTER DETAILS</h1>
        <h2>contact information</h2>
        <h3>required fields are followed by *</h3>
        <p>name * :<input type="text" name="name" required></p>
        <fieldset>
            <legend>gender *</legend>
        <p>male <input type="radio" name="gender" id="male" required>female <input type="radio" name="gender" id="female" required></p>
    </fieldset>
    <p>address <input type="address" name="address" rows="30" column="20"></p>
    <p>email *<input type="email" name="email" id="email" required></p>
    <p>pincode *<input type="pincode" name="pin" id="pincode"required></p>
    <h1>payment type</h1>
    <p>card type:
    <select name="card_type" id="card_type" >
        <option value=" ">select a card type></option>
        <option value="visa" >visa</option>
        <option value="rupay">rupay</option>
            <option value="mastercard"> mastercard</option>
    </select></p>
    <p> card number * <input type="number" name="card_number" id="card_number" aria-required=""></p>
    <p>
        expire date *<input type="date" name="exp_date" id="exp_date" required>
    </p>
    <A href="CHECK.html">CHECK</A></href>

    </form>
</body>
