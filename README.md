# html-code
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>pancard</title>
</head>
<body bgcolor="#fafad2">
    <form>
    <table border="1" width="1300">
    <tr>
        <center><b>Request For New Pan Card Or/And Changes Or Correction in Pan Data<br>Fields marked with <font color="red">*</font>(asterisk) are mandatory. To avoid mistake(s), please refer <font color="red"><u>guidelines</u></font> and <font color="red"><u>instructions</u></font></b></center></bgcolor>
    <tr>
        <td></td>
        <td colspan="2"><font color="red">*</font>Whether citizen of India &nbsp Yes<input type="radio" id="Yes" name="yes" value="Yes"> &nbsp No<input type="radio" id="No" name="No" value="No"></td>
    </tr>
    <tr>
        <td></td>
        <td colspan="2"><font color="red">*</font>Permanent Account Number(PAN)<input></td>
    </tr>
    <tr>
        <td><input type = "checkbox"></td>
        <td colspan="2"><font color="red">*</font>Name required</td>
    </tr>
    <tr>
        <td></td>
        <td colspan="2">Title &nbsp Shri/Mr<input type="radio" id="Shri/Mr" name="Shri/Mr" value="Shri/Mr"> &nbsp Smt/Mrs<input type="radio" id="Smt/Mrs" name="Smt/Mrs" value="Smt/Mrs"> &nbsp Kumari/Ms<input type="radio"> &nbsp M/s</td>
    </tr>
    <tr>
        <td></td>
        <td colspan="2">Last Name/Surname<input type="text"> &nbsp First Name<input type="text"> &nbsp Middle Name<input type="text"></td>
    </tr>
    <tr>
        <td></td>
        <td colspan="2"><font color="red">*</font>Name as you would like it printed on the card<font color="green">(Prefix like Shri,Smt,Kumari,Late,Dr,CA,Ms,Mr,Mrs,M/s,Alias ETC. are not allowed)</font></td>
    </tr>
    <tr>
        <td></td>
        <td colspan="2"><input type="text"></td>
    </tr>
    <tr>
        <td></td>
        <td colspan="2">Details of Parents.<font color="green">(Prefix like Shri,Smt,Kumari,Late,Dr,CA,Ms,Mr,Mrs,M/s,Alias ETC. are not allowed)</font></td>
    </tr>
    <tr>
        <td><input type="checkbox"></td>
        <td colspan="2"><font color="red">*</font>2. Father's Name<font color="green">(Mandatory field. Even married women should give father's name only.)</font></td>
    </tr>
    <tr>
        <td></td>
        <td colspan="2">Last Name/Surname<input type="text">First Name<input type="text">Middle Name<input type="text"></td>
    </tr>
    <tr>
        <td><input type="checkbox"></td>
        <td colspan="2">3. Mother's Name<font color="green">(This field is optional.)</font></td>
    </tr>
    <tr>
        <td></td>
        <td colspan="2">Last Name/Surname<input type="text">First Name<input type="text">Middle Name<input type="text"></td>
    </tr>
    <tr>
        <td></td>
        <td><font color="red">*</font>4. Select Parent name which is to be printed on the card<br><font color="green">(in case no option is provided then PAN card will be issued with father's name)</font></td>
        <td>Father Name<input type="radio" name="father" id="father" value="Father Name"> &nbsp Mother Name<input type="radio" name="mother" id="mother" value="Mother Name"></td>
    </tr>
    <tr>
        <td><input type="checkbox"></td>
        <td><font color="red">*</font>5. Date of<br>Birth/Incorporation/Agreement/Partnership<br>or Trust Deed/Formation of Body of <br>Individuals/<br>Association of Persons</td>
        <td>DD &nbsp MM &nbsp YYYY<br>
            <select name="dd" aria-placeholder="DD" id="dd">
            <option value="">DD</option>
            <option value="1">1</option>
            <option value="2">2</option>
            <option value="3">3</option>
            <option value="4">4</option>
            <option value="5">5</option>
            <option value="6">6</option>
            </select>
            <select name="mm" id="mm" placeholder="MM">
                <option value="">MM</option>
                <option value="1">1</option>
                <option value="2">2</option>
                <option value="3">3</option>
                <option value="4">4</option>
                <option value="5">5</option>
                <option value="6">6</option>
            </select>
            <select name="yyyy" id="yyyy" placeholder="YYYY">
                <option value="">YYYY</option>
                    <option value="1">2000</option>
                    <option value="1">2001</option>
                    <option value="1">2002</option>
                    <option value="1">2003</option>
                    <option value="1">2004</option>
                    <option value="1">2005</option>
            </select>
        </td>
    </tr>
    <tr>
        <td><input type="checkbox"></td>
        <td><font color="red">*</font>6. Gender</td>
        <td>Male<input type="radio" name="male" id="male" value="Male"> &nbsp Female<input type="radio" name="female" id="female" value="Female"></td>
    </tr>
    <tr>
        <td><input type="checkbox"></td>
        <td colspan="2">7. Photo Mismatch</td>
    </tr>
    <tr>
        <td><input type="checkbox"></td>
        <td colspan="2">8. Signature Mismatch</td>
    </tr>
    <tr>
        <td><input type="checkbox"></td>
        <td><font color="red">*</font>9. Address for Communication</td>
        <td>Residential<input type="radio" name="res" id="res" value="Residential"> &nbsp Office<input type="radio" name="office" id="office" value="Office"></td>
    </tr>
    <tr>
        <td></td>
        <td>Office Name(to be filled only in case of office address)</td>
        <td><input type="text"></td>
    </tr>
    <tr>
        <td></td>
        <td>Flat/Door/Block No.</td>
        <td><input type="text"></td>
    </tr>
    <tr>
        <td></td>
        <td>Name of Premises/Building/Village</td>
        <td><input type="text"></td>
    </tr>
    <tr>
        <td></td>
        <td>Road/Street/Lane/Post Office</td>
        <td><input type="text"></td>
    </tr>
    <tr>
        <td></td>
        <td>Area/Locality/Taluka/Sub-Division</td>
        <td><input type="text"></td>
    </tr>
    </tr>
</form>
    </table>


    
    
</body>
</html>
