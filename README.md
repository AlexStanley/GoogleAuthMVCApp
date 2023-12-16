# GoogleAuthMVCApp

1. To Set up the project you need to make changes into appsettings.json config file for Server (local server name):

"DefaultConnection": "Server=.;Database=GoogleAuthMVCDb;Trusted_Connection=True;MultipleActiveResultSets=true;"

2. You need to apply migration for your local database through Package Manager Console:

update-database

3. Start applicatiom as usually;

4. "Private" is under authorization (only authorized user can go there);

5. Push the button "Login with Google", go through authorization process and 

6. You can go to the "Private" when you are authorazed.