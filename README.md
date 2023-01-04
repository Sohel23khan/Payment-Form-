# Payment-Form-<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Payment Form</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
 
    <div class="main">Payment Form </h1>
        <p>Reqiered fields are followed by * </p>
        <h2>Contact Information</h2>
        <p>Name: * <input type="text" name="name" required placeholder="Enter Name"></p>  
        <fieldset>  
            <legend>Ge="container">
    <form action="">
        <h1 classnder</legend>
            <p>
            Male <input type="radio" name="gender" id="Male" >
            Female <input type="radio" name="gender" id="Female">
        </p> </fieldset>
        <p>Address: <textarea name="address" id="address" cols="100" rows="10" placeholder="Enter Address "></textarea> </p>
        <p>Email: * <input type="email" name="email" id="email" required placeholder="Email Enter "></p>
        <p>Pincode: * <input type="number" name="pincode" id="pincode" required placeholder="Zip code "></p>
        <h2>Payment Information</h2>
         <p>Card Type:*
            <select name="card_type" id="card_type" required> 
            <option value=""> Select the card type</option>
            <option value="Visa"> Visa</option>
            <option value="Mastercard"> Master Card</option>
            <option value="Rupay"> Rupay</option>
        </select>
         </p>
         <p>
            Card Number: * <input type="number" name="card_number" id="card_number" required placeholder="Card in Number form">
         </p>
         <p>
            Expiration Date: * <input type="date" name="exp_date" id="exp_date" required>
         </p>
         <p>
            CVV: * <input type="password" name="cvv" id="cvv" required>
         </p>

         <input type="submit" value="Pay Now">

 </form> </div>
</body>
</html>
