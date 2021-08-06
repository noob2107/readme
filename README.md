# CSOC week 5 Submission

## Track

- [ ] Django
- [x] Express

## Task Completed

- [x] **Task 1**: Completed all the basic endpoints
- [x] **Task 2**: Implemented collaborator feature

### End points for collaborator

**Auth**

-   `PUT /todo/:id/add-collaborators/` 

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
	  "token":  "string"
	}
	```
	Response Code: `200`


-   `PUT /todo/:id/remove-collaborators/` 

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
	  "token":  "string"
	}
	```
	Response Code: `200`

### Submission

[Repo](https://github.com/MohitSharma-21/CSOC-2021-task-5-Express-Apis/tree/mohit)
[Deployed API ](https://mohitsharma-21.github.io/tic-tac-toe/)
