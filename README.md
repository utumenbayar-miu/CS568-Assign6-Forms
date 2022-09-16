# CS568 Assignment 7 - Forms and Axios
## Users app in React and Users API in Express, NodeJS, MongoDB

Requirements:
- List all users in the DB.
- In the user component, there is the "delete" button. Should be able to delete.
- Show the first user information in the inputs. Should be able to edit directly.
- Show empty input fields where user can save data in the DB.

**Tasks 1.** Practice various of HTML input types in React and learn how to capture and process input data entered by the user.
  * Text type input - firstname, lastname. VALIDATION, these 2 are required.
  * [Date type input](https://www.w3schools.com/html/tryit.asp?filename=tryhtml_input_date_max_min) - Date of Birth, VALIDATION with min and max.
  * [Tel type input](https://www.w3schools.com/html/tryit.asp?filename=tryhtml_input_tel) - Phone in 123-45-678 format, VALIDATION make sure phone is in the right format. ```<input type="tel" id="phone" name="phone" placeholder="123-45-678" pattern="[0-9]{3}-[0-9]{2}-[0-9]{3}" required>```
  * [Color type input](https://www.w3schools.com/html/tryit.asp?filename=tryhtml_input_color) - Favorite color in #ff0000 format.
  * [Range type input](https://www.w3schools.com/html/tryit.asp?filename=tryhtml_input_range) - Course satisfaction score (0 to 10). 
  * Dropdown type input - Education degree (high school, collage, bachelor, master, doctor)
  * Select type input - Hobbies (Basketball, motorcycle, pool billiards, so on ...).
  * Radio button type input - Gender (Female, Male, Other)
  * Number type input - Lucky number
  * Text area type input - About

**Tasks 2.** Based on the knowledge of the previous classes, build out a simple "User" back-end API using Express and MongoDB. Object structure:
```
{
	id: "632373a9170462d65b9ed26c",
	firstname: "Unubold",
	lastname: "Tumenbayar",
	about: "looooooong paragraph",
	favColor: "#00e1ff",
	gender: "male",
	email: "utumenbayar@miu.edu",
	dob: "2000-09-15",
	luckNumber: 521,
	courseSatisfaction: 8,
	phone: 123-45-678,
	education: "master",
	hobbies: ["motorcycle", "pool billiards"]
}
```

**Tasks 3.** Practice uncontrolled elements and Ref. Make the "firstname" field uncontrolled. Read the value from the Ref. When page loads, focus on the "firstname" field automatically. 
