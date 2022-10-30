
# API testing project with java + Rest Assured + Allure report

As a website for API testing, I used the website https://reqres.in/ with an open API

Test cases that I automated in my project:

Test 1
   
 1. Using the service "https://reqres.in/" to get a list of users from the second page(2)
 2. Check that the avatar names/user ID's match
 3. Check that email ends with reqres.in

Test 2
 1. Using the service "https://reqres.in/" check user registration
 2. Check successful registration
 3. Check unsuccessful registration

Test 3
 1. Using the service "https://reqres.in/" check that LIST<RESOURCE> return data which sorted for years

Test 4
 1. Using the service "https://reqres.in/" delete users and check response status

Test 5
 1. Using the service "https://reqres.in/" update information and compare get time with computer time