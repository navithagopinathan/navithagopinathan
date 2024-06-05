<h3 style="text-align:center">Student Add Form</h3>

    <body>

        @using (Html.BeginForm("submit", "Student"))
        {
            <fieldset>
                <legend>Add Student</legend>
                
                   
                <div>
                    <label for="StudentName">Name:</label>
                    <input type="text" name="studName" value="" />
                </div>
                <div>
                    <label for="Course">Course</label>
                    <input type="text" name="course" value="" />
                </div>
                <div>
                    <label for="Course">fees</label>
                    <input type="text" name="fees" value="" />
                </div>
                <div>
                    <label>&nbsp;</label>
                    <input type="submit" value="Submit" class="submit" />
                </div>
            </fieldset>

