<!DOCTYPE html>
<html lang="en">
<head>
<title>Sign Up Form</title>
<style>
    *{
        margin: 0;
        padding: 10px;
        
    }
    form{
       
    }
    .button, h2{
        text-align: center;
        color: red;
    }
    .submit:hover, .reset:hover{
          background-color: blue;
          color:white;
    }


</style>
</head>
<body>
    <form method="post">
        <h2> Community Join Form </h2>
        <label> Name : </label>
        <input type="text" place="First Name">
        <input type="text" place="Last Name"><br><br>

        <label> Dob :</label>
        <input type="date" id="start" name="start"
        min="1999-01-01" max="2022-11-29">

        <label>Choose You Favourite Color :</label>
        <input type="color"><br><br>

        <label>Gender</label><br>
        <input type="radio" name="gender" value="male"> Male <br>
        <input type="radio" name="gender" value="Female"> Female <br>
        <input type="radio" name="gender" value="Transgender"> Transgender <br>
        <input type="radio" name="gender" value="Other"> Other <br> <br>

        <label> E-mail : </label>
        <input type="text" placeholder="ex:abc@xyz.com">

        <label> Contact No. : </label>
        <input type="text" placeholder="+91-0123456789"><br><br>

        <div class="address">
        <label>Address :</label><br>
        <input type="text" input size="90%"  placeholder="Flat no., House no., Building, Company, Apartment" ><br><br>
        <input type="text" input size="90%" placeholder="Area, Colony, Street, Sector, Village"><br><br>
        <input type="text" input size="90%" placeholder="Landmark "><br><br>
        <input type="text" input size="90%" placeholder="Town/City"><br><br>
        <select name="State"  id="State"> 
            <option value="Select Your State">Select Your State</option>
            <option value="Andhra Pradesh">Andhra Pradesh</option>
            <option value="Andaman and Nicobar Islands">Andaman and Nicobar Islands</option>
            <option value="Arunachal Pradesh">Arunachal Pradesh</option>
            <option value="Assam">Assam</option>
            <option value="Bihar">Bihar</option>
            <option value="Chandigarh">Chandigarh</option>
            <option value="Chhattisgarh">Chhattisgarh</option>
            <option value="Dadar and Nagar Haveli">Dadar and Nagar Haveli</option>
            <option value="Daman and Diu">Daman and Diu</option>
            <option value="Delhi">Delhi</option>
            <option value="Lakshadweep">Lakshadweep</option>
            <option value="Puducherry">Puducherry</option>
            <option value="Goa">Goa</option>
            <option value="Gujarat">Gujarat</option>
            <option value="Haryana">Haryana</option>
            <option value="Himachal Pradesh">Himachal Pradesh</option>
            <option value="Jammu and Kashmir">Jammu and Kashmir</option>
            <option value="Jharkhand">Jharkhand</option>
            <option value="Karnataka">Karnataka</option>
            <option value="Kerala">Kerala</option>
            <option value="Madhya Pradesh">Madhya Pradesh</option>
            <option value="Maharashtra">Maharashtra</option>
            <option value="Manipur">Manipur</option>
            <option value="Meghalaya">Meghalaya</option>
            <option value="Mizoram">Mizoram</option>
            <option value="Nagaland">Nagaland</option>
            <option value="Odisha">Odisha</option>
            <option value="Punjab">Punjab</option>
            <option value="Rajasthan">Rajasthan</option>
            <option value="Sikkim">Sikkim</option>
            <option value="Tamil Nadu">Tamil Nadu</option>
            <option value="Telangana">Telangana</option>
            <option value="Tripura">Tripura</option>
            <option value="Uttar Pradesh">Uttar Pradesh</option>
            <option value="Uttarakhand">Uttarakhand</option>
            <option value="West Bengal">West Bengal</option>
        </select> <br><br>


        
        <label>Where did you hear about us?</label><br>
        <input type="checkbox" name="Where" id="Friend"> A Friend or colleague <br>
        <input type="checkbox" name="Where" id="Google"> Google <br>
        <input type="checkbox" name="Where" id="News Article"> News Article <br>
        <input type="checkbox" name="Where" id="Youtube"> Youtube <br> <br>

        <div class="button">
        <input type="submit" value="Sign Up" class="submit">
        <input type="reset" value="Reset" class="reset">
        </div>


        


    </form>
</body>
</html>
