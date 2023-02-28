# SpringBootInterview 

# We need you to build a service that will accept HTTP GET requests at http://localhost:8080/greeting.
# It will respond with a JSON representation of a greeting, as the following listing shows:
#   {"id":1,"content":"Hello, Welcome to CUBA ! "}
# You will further customize the greeting with an optional name parameter in the query string, like
#   http://localhost:8080/greeting?name=Tripathi
# The name parameter value overrides the default value of "Welcome to CUBA !" and is reflected in the response, like
#   {"id":2,"content":"Hello, Welcome to CUBA ! Tripathi !! "}
# With multiple request, value of ID should be autoincremented 
