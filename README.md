# About
NFQ Software Engineering Internship task\
Tautvydas Rušas\
Project deployed on: http://stark-river-44975.herokuapp.com

# Project description
Project is done on the Symfony framework. All the required tasks are completed

# How it works


#### Home Page - http://stark-river-44975.herokuapp.com/
- The customer can book his appointment with a specialist by selecting a doctor he wants, entering his details, selecting a date and then submitting.
#### Customer Time Left Registration Code Page - http://stark-river-44975.herokuapp.com/registration/code
- The customer can enter his registration code which he should have saved and check how much time he has left till his appointment.
#### Customer Time Left Page - Registration code =   D5MY2ZF6QN8B7I4AE01R, so url = http://stark-river-44975.herokuapp.com/search?registrationCode=D5MY2ZF6QN8B7I4AE01R
- The customer can see how much time is left till his appointment. If the time has already passed the customer will see that the output changes to - "The doctor will appoint you soon."
Otherwise the customer will see how much time he has left till his appointment.
- The customer can cancel his appointment if he wants by pressing the cancel button.
#### Display Board Registration Code Page - http://stark-river-44975.herokuapp.com/display/board
- The customer can enter his registration code and see the display board.
#### Display Board Page - Registration code =   D5MY2ZF6QN8B7I4AE01R, so url = http://stark-river-44975.herokuapp.com/displayBoard?registrationCode=D5MY2ZF6QN8B7I4AE01R
- The customer can see customers which have entered the specialists appointment.
- The customer can see 5 upcoming customers which will have to be admitted next to the appointment.
- The page refreshes every 5 seconds so the customer can see time counting down till the appointment.
- If the time ended the message will say - 'The doctor should appoint you soon"
#### Login Page - http://stark-river-44975.herokuapp.com/login 
##### Login details - Username: tom  Password: 123 or Username: linas Password: 123
- The specialist can log in and access his customers management page
- The specialist accounts are created using a fixture
#### Customer Management Page - http://stark-river-44975.herokuapp.com/customer/managing
- The page only becomes accessible after a specialist logs on
- Impossible to access this page unless you are logged in
- The specialist can see all customers that have registered appointments with only him
- The specialist can admit a customer, by doing that no other customers can be admitted at the same time
- The specialist can end the admitted customers appointment
- If no customer is appointed to meet a specialist then it's impossible to end any appointments
- The specialist can cancel any appointment at any time

# Problems
- Two same dates can be selected for a specialist appointment
- Being able to select a date which happened before current time
- If the display board has no admitted customers it will still create a table
- If the display board has no customers waiting for admission it will still create a table
- If the specialist has no customers he will still see a table

# Contacts
tautis63@gmail.com\
+37067987256

# Thanks for your attention
