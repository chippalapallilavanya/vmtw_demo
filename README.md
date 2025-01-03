<html>
    <head>
        <title>Registration Form</title>
    </head>
    <body bgcolor="SkyBlue">
        <h1>Registration form</h1>
        <form>
            <label>First Name:</label>
            <input type="text" name="firstname" size="15">
            <br>
            <label>Middle Name:</label>
            <input type="text" name="middlename" size="15">
            <br>
            <label>Last Name:</label>
            <input type="text" name="lastname" size="15">
            <br>
            <select>
                Course:
                <option value="course">Course</option>
                <option value="bca">BCA</option>
                <option value="bba">BBA</option>
                <option value="bcom">B.Com</option>
                <option value="btech">B.Tech</option>
                <option value="mtech">M.Tech</option>
                <option value="mba">MBA</option>
            </select>
            <br>
            <label>Gender:</label>
            <label>Female</label>
            <input type="radio" name="Female" size="15">
            <label>Male</label>
            <input type="radio" name="Male" size="15">
            <br>
            <label>Address</label>
            <input cols="8" rows="5" name="address" size="15" type="text">
            <br>
            <label>Phone Number:</label>
            <input type="text" name="country code" value="+91">
            <input type="text" name="phone" size="15">
            <br>
            <label>Email ID:</label>
            <input type="text" name="email" value="id" size="15">
            <br>
            <br>
            <button>Submit</button>
            <input type="button" name="submit">
        </form>
    </body>
</html>
