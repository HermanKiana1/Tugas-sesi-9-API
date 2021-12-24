# Tugas-sesi-9-API

HERMAN KIANA

1. Metode POST.
- Create new object repository "Method POST"
- Input Url http://jsonplaceholder.typicode/posts

- Create Test case Metode POST
- Add keyword Send Request
	- Object "Method POST"
	- Output "Response"
- Add Verify Response Status Code
	- Input param name "responseObject" Param type "ResponseObject" Value Type "Variable" Value "Response"
	- Input param name "expectedStatusCode" Param type "integer" Value Type "number" Value "201"
- Add Verify Element Proprty value
	- Input param name "response" Param type "ResponseObject" Value Type "Variable" Value "Response"
	- Input param name "locator" Param type "string" Value Type "string" Value "id"
	- Input param name "value" Param type "Object" Value Type "number" Value "101"


2. Methode GET.
- Create new object repository "Methode GET"
- Input Url - Input Url http://jsonplaceholder.typicode/posts1
- Create Test case Methode Get
- Add keyword Send Request
	- Object "Methode GET"
	- Output "Response"
- Add Verify Response Status Code
	- Input param name "responseObject" Param type "ResponseObject" Value Type "Variable" Value "Response"
	- Input param name "expectedStatusCode" Param type "integer" Value Type "number" Value "200"
- Add Verify Element Proprty value
	- Input param name "response" Param type "ResponseObject" Value Type "Variable" Value "Response"
	- Input param name "locator" Param type "string" Value Type "string" Value "userid"
	- Input param name "value" Param type "Object" Value Type "string" Value "1"
- Add Verify Element Proprty value
	- Input param name "response" Param type "ResponseObject" Value Type "Variable" Value "Response"
	- Input param name "locator" Param type "string" Value Type "string" Value "id"
	- Input param name "value" Param type "Object" Value Type "string" Value "1"
- Add Verify Element Proprty value
	- Input param name "response" Param type "ResponseObject" Value Type "Variable" Value "Response"
	- Input param name "locator" Param type "string" Value Type "string" Value "title"
	- Input param name "value" Param type "Object" Value Type "string" Value "sunt aut facere repellat provident occaecati excepturi optio reprehenderit"

3. Delete User
- Create new object repository "Metod DELETE"
- Input Url http://jsonplaceholder.typicode/posts1
- Create Test case Methode DELETE
- Add keyword Send Request
	- Object "Methode DELETE"
	- Output "Response"
- Add Verify Element Proprty value
	- Input param name "responseObject" Param type "ResponseObject" Value Type "Variable" Value "Response"
	- Input param name "expectedStatusCode" Param type "integer" Value Type "number" Value "200"
	- Input param name "flowControl" Param type "FailureHandling" Value Type "Property" Value "STOP_ON_FAILURE"
