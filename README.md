<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <form action="">
        <h1>Payment Form</h1>
        <h2>Contact Details</h2>
        <p>Required fields are followed by * </p>
        <p>Name:*<input type="text" name="name" required></p> 
        <p> 
            <fieldset>
                <legend>Gender*</legend>
            Male: <input type="radio" name="gender" id="gender" required> Female:<input type="radio" name="gender" id="gender" required>Other:<input type="radio" name="gender" id="gender" required>
            </fieldset>
        </p>
        <p> Address: <textarea name="Address" id="Address" cols="60" rows="10"></textarea></p>
        <p>Email:* <input type="email" name="email" id="email" required></p>
        <p>Pincode:* <input type="number" name=" pincode" id="pincode" required></p>
        <hr>
        <h2>Payment information*</h2>
        <p>card type:*
            <select name="Card_type" id="Card_type" required>
                <option value="">----select a card----</option>
                <option value="visa">Visa</option>
                <option value="rupay">rupay</option>
                <option value="Master_card">Master_card</option>
            </select>
        </p>
        <p>
            Card Number:* <input type="number" name="card_number" id="card_number"required>
        </p>
        <p>
            Expiry Date:* <input type="date" name="exp_date" id="exp_date" required>
        </p>
        <p>
            CVV:* <input type="password" name="cvv" id="cvv"required>
        </p>
        <input type="submit" value="Pay now">
        <input type="reset" value="Reset">



    </form>
    
</body>
</html>
