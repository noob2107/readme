## CSOC week 5 Submission

### Tasks Completed

- [x] **Task 1**: Completed all the basic endpoints
- [x] **Task 2**: Implemented collaborator feature

#### End points for collaborator
Both the end points take user token as the authorization header with the prefix Token and User id in the request body.

-  **Add collaborator**: `PUT /todo/:id/add-collaborators/` 
-  **Remove collaborator**: `PUT /todo/:id/remove-collaborators/` 

	Takes the username as input
  
	Request Body (Sample):
	```
	{
	  "username": "string",
	}
	```
	Response Body (Sample):
	```
	{
	  "collaborators": [{<useranme of collbaorators>}],
	  "title": "string",
	  "createdBy":"string"
	}
	```
	Response Code: `200`


-  **Remove collaborator**: `PUT /todo/:id/remove-collaborators/` 

	Takes the username as input
  
	Request Body (Sample):
	```
	{
	  "username": "string",
	}
	```
	Response Body (Sample):
	```
	{
       	 "collaborators": [{<useranme of collbaorators>}],
    	 "title": "string",
    	 "createdBy":"string"
	}
	```
	Response Code: `200`

### Submission

[Repo](https://github.com/MohitSharma-21/CSOC-2021-task-5-Express-Apis/tree/mohit)
[Deployed API ](https://mohitsharma-21.github.io/tic-tac-toe/)
