Spring Data Rest addresses: 
	1) The developer uses a Spring Data project that supports the repository model
	2) The system uses well accepted industry standard protocols, 
	   like HTTP verbs, standardized media types, and IANA-approved link names.

*******JSP*******	
- we will use Spring Data Rest-based application as the domain object. 
Which will let us keep track of the employees for a company. 
- JPA annotation is used to denote employee ID. (@Id and @GeneratedValue)
- When launch backend of REST API is to write "public static void main"
  using Spring Boot.

*******React*****
- We create a componentDidMount() to use get rest call for our employees
  Then pass it down to JSX EmployeeList and give the variable employees
-We use state and properties. State is data that hte compoennt is expected
to handle. we read state with this.state() and this.setState() will update.
-You defined a domain object and a corresponding repository.

-You let Spring Data REST export it with full blown 
hypermedia controls.

-You created two simple React components in a parent-child relationship.

-You fetched server data and rendered them in as a simple, static HTML structure.

Part 2 - Hypermedia Controls

Rendering
-key is needed by React to distinguish between multiple child nodes.
-It's a simple text-based entry field
-placeholder is where we cna show the user with field is which.

Handling User Input
-this.refs is used to reach out and grab a particular React component
-Promises are a way to start asynchronous operations and register
a function to respond when the task is done. They avoid callback hell.

Part 3 - Conditional Operations

