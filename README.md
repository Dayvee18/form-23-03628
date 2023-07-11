# form-23-03628
<form action="submit_form.php" method="post">
  <label for="student-name">Student Name:</label>
  <input type="text" id="student-name" name="student-name" required>

  <label for="telephone-number">Telephone Number:</label>
  <input type="tel" id="telephone-number" name="telephone-number" required>

  <label for="date-of-birth">Date of Birth:</label>
  <input type="date" id="date-of-birth" name="date-of-birth" required>

  <label for="admission-number">Admission Number:</label>
  <input type="text" id="admission-number" name="admission-number" required>

  <label for="course">Select Course:</label>
  <select id="course" name="course" required>
    <option value="" disabled selected>Select course</option>
    <option value="CBIT">CBIT</option>
    <option value="CIT">CIT</option>
  </select>

  <label for="gender">Select Gender:</label>
  <input type="radio" id="male" name="gender" value="male" required>
  <label for="male">Male</label>
  <input type="radio" id="female" name="gender" value="female">
  <label for="female">Female</label>

  <button type="submit">Submit</button>
</form>
