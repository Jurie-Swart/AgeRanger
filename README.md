
Inside the AgeRanger.zip file the following assets will be found.

1. AgeRanger, this is the C# single page application that allow users to add, edit, delete and find people.
2. AgeRangerTest directory contains the unit tests application to be used for custom test cases.

Additional Notes:

1. Styling was done with the help of the Bootstrap library.
2. Client scripts leverage the angularjs framework.
3. The startup page is called default.html
4. The api is accessable at /api/People/ and the following methods are exposed:
	- GET: api/People (return all people)
	- GET: api/People/{id} (return person on id)
	- POST: api/People (add person)
	- DELETE: api/People/{id} (delete person on id)
	- PUT: api/People/{id} (edit person on id)
5. The database connections are done using assemblies available from https://sqlite.org/, these assemblies can be accessed by installing the /sqlite-netFx46-setup-bundle-x86-2015-1.0.102.0.exe

Thanks
Jurie
