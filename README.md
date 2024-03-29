### Sample
This is the expected output when `app.js` is run on terminal

  <img src="image\Screenshot (386).png">


### Tests for Requirements

This project has the following requirments:

- Telephone Class with 3 Public Methods <br/><br/>
In `phone.js` file, the Telephone class is in line 2 while AddPhoneNumber, RemovePhoneNumber, and DialPhoneNumber methods can be found in lines 9, 18 and 26 respectively.


- Update Telephone Class to Use Observer Pattern <br/><br/>
This was applied in lines 40 and and 49 of the `phone.js` file.


- A Class for Observer Pattern <br><br/>
Line 49 in `phone.js` file, shows a class for Observer pattern.


- Telephone Class Notify Observer Anytime Phone Number is Dailed <br/><br/>
This can also be found in line 40 of the `phone.js` file.


- Add Two Observer to the Telephone Class <br/><br/>
In `app.js` lines 7 and 8, we have two observers to the telephone class.


### Note
- Phone Number must be added(to the observersArray) before it can be dailed.

- In `phone.js` file, line 22 will throw an error because the phone number has not being added before it was dailed.


### Usage
- `clone` this project with this command below or any preferred method, cd into the `telephone-package` folder
```
git clone https://github.com/lotacodic/telephone-package.git
```
- `node js` is needed to run this project on terminal 
- recommended IDE is Vs Code, I recommend Maximum Panel Size for a better view of the output
- run this command `node app.js` on terminal 
