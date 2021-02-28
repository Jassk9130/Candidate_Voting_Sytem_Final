1. Open the Solution in Visual Studio
2. Build the project 
3. Navigate to tools ans select Nuget Package manager -> Package Manager Console (PMC)
4. On the console execute the following command
Update-Database Idntity -Context Candidate_Voting_IdentityContext


5. On the console execute the following command

  Update-Database Data -Context Candidate_Voting_DataContext



6. After migration is successful Run the project 

7 if you login as admin  from the following credentials will be able to see the Votes,  Voters 
Candidates and voting transactions  
User : admin@votes.com
Password: 1qaz2wsX@

8. Also you can login with the following credentials to visit the site as a Voter who will vote for a candidate
 Can only vote for a single candidate. If the voter tries to vote for two candidate an error message will be displayed as the vote is invalid

 User : jim@gmail.com
Password: 1qaz2wsX@
 
 OR 

  User : kent@gmail.com
Password: 1qaz2wsX@


9 if you need to create another  admin login with the admin credentials on step 7 above and
Click in "Register Vote admin" register a new admin 





The identity  authentication code used in the project were obtained by following URLS

Introduction to Identity on ASP.NET Core
https://docs.microsoft.com/en-us/aspnet/core/security/authentication/identity?view=aspnetcore-3.0&tabs=visual-studio
