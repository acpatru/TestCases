# Test Case Samples

Bellow are some Test Case samples that I wrote while working on previous projects.

---------------------

**Title:**
Test login with correct credentials.

**Description:**
Test the login by using correct credentials.

**Steps to reproduce:**
1. Go to site.com/login
2. Add correct user/pass.
3. Click on the ""Login"" button.
3. Observe if user can login."

**Expected Result:**
User should be able to login and is take to his profile page.

**Test data:**
User: test & Pass: 123

---------------------

**Title:**
Test login with incorrect credentials

**Description:**
Test the login by using incorrect credentials.

**Steps to reproduce:**
1. Go to site.com/login
2. Add incorrect user/pass.
3. Click on the ""Login"" button.
4. Observe if user can't login.

**Expected Result:**
User should not be able to login and 
it should remain on the login page.

**Test data:**
User: estet & Pass: 321

---------------------

**Title:**
Test login with the empty fields

**Description:**
Test the login by not tyiping anything on the login's fields.

**Steps to reproduce:**
1. Go to site.com/login 
2. Don't add anything on user/pass.
3. Click on the "Login" button.
4. Observe if user can't login.

**Expected Result:**
User should not be able to login and 
it should remain on the login page.

**Test data:**
User: (empty) & Pass: (empty)

---------------------

**Title:**
Test the "Remember Me" check-box

**Description:**
Test the "Remember Me" check-box by clicking on it.

**Steps to reproduce:**
1. Go to site.com/login
2. Add correct user/pass.
3. Click on "Remember Me" check-box.
4. Click on the "Login" button.
5. Observe if user will remain on the page
profile without the need to login again.

**Expected Result:**
User should be able to remain on the page profile  without the need to login again on the login's page only if the ""Remember Me"" check-box was checked at the first login.

**Test data:**
User: test & Pass: 123

---------------------

**Title:**
Test the "Search" field with the autocomplete function

**Description:**
Test the ""Search"" field by writing the first 3 letters of an object.

**Steps to reproduce:**
1. Go to https://www.emag.ro/
2. Type the first 3 letters of the object
3. Click on the ""Search"" button.
4. Observe if in the "Search" field will be a list of words bellow: *canapele*,*canvas* and *cana*.

**Expected Result:**
User should be able to see a list of words (*canapele*,*canvas* and *cana*) after writing the first 3 letters of object.

**Test data:**
Search: *Can*

---------------------

**Title:**
Test the "Search" field with an object that doesn't exist

**Description:**
Test the "Search" field by writing an object that doesn't exist.

**Steps to reproduce:**
1. Go to https://www.emag.ro/
2. Type the object that doesn't exist.
3. Click on the "Search" button.
4. Observe if in the "Search" will show a message.

**Expected Result:**
User should be able to see the message *"0 results, please check if you write the correct letters,try to use synonysms,try again,using a general searching"* on the same page.

**Test data:**
Search: *Hfuehfqhfuqw*
