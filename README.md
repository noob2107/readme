## CSOC week 5 Submission

### Tasks Completed

- [x] **Task 1**: Complete all the basic endpoints
- [x] **Task 2**: Implement collaborator feature

#### End points for collaborator
Both the end points takes the username as input and user token as the authorization header with the prefix Token.

-  **Add collaborator**: `PATCH /todo/:id/add-collaborators/` 
-  **Remove collaborator**: `PATCH /todo/:id/remove-collaborators/` 
  
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
