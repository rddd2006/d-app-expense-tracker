# d-app-expense-tracker
this is Riddhith Ghosh
for the soliditary i am attaching a text file with soliditary code
the feature i am choosing is to get total no of registered users the codefix is below
#function gettotal() public view returns (uint256) {
     #   return registeredPeople.length;
    #}
    for app.js also i am showing total registered people
    here are snippet i am adding
    #<p>Total Registered Users: {people.length}</p>
    also added a header
    #<h3>People ({people.length} registered)</h3>
    i am saving copy of the file as a text file
   
update added fetchusers function in app js to call solidity gettotal function
added a button for user to interact with solidity function
note i did not add contract error case in fetchuser function
