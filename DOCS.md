# rest v0.0.0



- [Todo](#todo)
	- [Create todo](#create-todo)
	- [Delete todo](#delete-todo)
	- [Retrieve todo](#retrieve-todo)
	- [Retrieve todos](#retrieve-todos)
	- [Update todo](#update-todo)
	


# Todo

## Create todo



	POST /todos


### Parameters

| Name    | Type      | Description                          |
|---------|-----------|--------------------------------------|
| name			| 			|  <p>Todo's name.</p>							|
| completed			| 			|  <p>Todo's completed.</p>							|

## Delete todo



	DELETE /todos/:id


## Retrieve todo



	GET /todos/:id


## Retrieve todos



	GET /todos


### Parameters

| Name    | Type      | Description                          |
|---------|-----------|--------------------------------------|
| q			| String			| **optional** <p>Query to search.</p>							|
| page			| Number			| **optional** <p>Page number.</p>							|
| limit			| Number			| **optional** <p>Amount of returned items.</p>							|
| sort			| String[]			| **optional** <p>Order of returned items.</p>							|
| fields			| String[]			| **optional** <p>Fields to be returned.</p>							|

## Update todo



	PUT /todos/:id


### Parameters

| Name    | Type      | Description                          |
|---------|-----------|--------------------------------------|
| name			| 			|  <p>Todo's name.</p>							|
| completed			| 			|  <p>Todo's completed.</p>							|


