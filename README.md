# html-forms
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>practice form - vishakha singhla</title>
</head>

<body>
    <h2>APPLICATION FORM FOR USERS </h2>
    <form action="post"></form>
    <div>
        <label for="username">Enter your first name:</label>
        <input type="text" name="username" id="username" placeholder="Enter your first name" required>
    </div>
    <div>
        <label for="username">Enter your last name:</label>
        <input type="text" name="username" id="username" placeholder="Enter your last name" required>

    </div>
    <div>
        <label for="DOB"> Enter Date Of Birth:</label>
        <input type="date" name="DOB" id="DOB" placeholder="dd-mm-yyyy" required>
    </div>
    <div>
        <label for="fater's name">Enter Father's name:</label>
        <input type="text" name="father's name" id="father's name" placeholder="Enter Father's name" required>
    </div>
    <div>
        <label for="mother's name">Enter Mother's name:</label>
        <input type="text" name="Mother's name" id="mother's name" placeholder="Enter Mother's name" required>

    </div>
    <div>
        <label for="gender"> Select your gender:</label>
        <label for="Male">Male</label>
        <input type="radio" name="gender" id="Male" value="Male">
        <label for="Female">Female</label>
        <input type="radio" name="gender" id="Female" value="Female">
        <label for="other">Other</label>
        <input type="radio" name="gender" id="Other" value="Other">
    </div>
    <div>
        <label for="address">Enter your Address:</label>
        <!-- <input type="text" name="address" id="address"> -->
        <textarea name="address" id="address" rows="4" cols="20"> </textarea>
    </div>
    <div>
        <label for="phone no.">Enter phone number:</label>
        <input type="tel" name="phone no." id="phone no.">
    </div>
    <div>
        <label for="e-mail">Enter E-mail:</label>
        <input type="email" name="e-mail" id="e-mail" required>
    </div>
    <div>
        <label for="status">Select your status:</label>
        <select name="status" id="status">
            <option value="select">--select--</option>
            <option value="single">Single</option>
            <option value="married">Married</option>
            <option value="divorced">Divorced</option>
            <option value="other">Other</option>
        </select>
    </div>
    <div>
        <label for="occupation">Enter occupation:</label>
        <!-- <input type="text" name="occupation" id="occupation">  -->
        <select name="occupation" id="occupation">
            <option value="select">--select--</option>
            <option value="Business">Business</option>
            <option value="Employee">Employee</option>
            <option value="Student">Student</option>
            <option value="House-wife">House-wife</option>
            <option value="other">other</option>
        </select>
    </div>
    <div>
        <label for="aadhar no.">Enter aadhar no.</label>
        <input type="text" name="aadhar no." id="aadhar no.">
    </div>
    <div>
        <label for="qualification">Enter your qualification:</label>
        <select name="checkbox" id="qualification">
            <option value="select">--select--</option>
            <option value="10th">10th pass</option>
            <option value="12th">12th pass</option>
            <option value="graduation"> Gradutation</option>
            <option value="under-gradutation">under-gradutation</option>
            <option value="post-graduation">Post-gradutation</option>
            <option value="not applicable">not applicable</option>
        </select>
    </div>
    <div>
        <label for="state">Enter your state :</label>
        <input type="text" name="state" id="state">
    </div>
    <div>
        <label for="pin-code">Enter your pin-code:</label>
        <input type="text" name="pin-code" id="pin-code">
    </div>
    <div>
        <label for="members">Enter members in your family:</label>
        <input type="number" name="members" id="members">
    </div>
    <div>
        <label for="religion">Select your religion:</label>
        <select name="religion" id="religion">
            <option value="select">--select--</option>
            <option value="hindu">Hindu</option>
            <option value="muslim">Muslim</option>
            <option value="sikh">Sikh</option>
            <option value="others">Others</option>
        </select>
    </div>
    <div>
        <label for="document">Enter document type:</label>
        <!-- <input type="text" name="document" id="document"> -->
        <select name="document" id="document">
            <option value="select">--select--</option>
            <option value="Aadhar card">Aadhar card</option>
            <option value="pan card">Pan card</option>
            <option value="voter id">Voter id</option>
            <option value="12th marksheet">12th marksheet</option>
        </select>
    </div>
    <div>
        <label for="file">Select document</label>
        <input type="file" name="document" id="document">
    </div>
    <div>
        <label for="range">Select the range of the form</label>
        <input type="range" name="range" id="range" min="0" max="5">
    </div>
    <div>
        <label for="feedback">write feedback of the above form</label>
        <textarea name="feedback" rows="5" cols="60" id="feedback">
            write your feedback here...
        </textarea>
    </div>
    <div>
        <label for="submit">Click to submit the form</label>
        <input type="submit" name="submit" id="submit">
    </div>
    <div>
        <label for="reset">Reset your form</label>
        <input type="reset" name="reset" id="reset">
    </div>
</body>

</html>
