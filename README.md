API to convert text to JSON file using AI

http://localhost:3000/api/json
Method: POST

Input example 
{
    "data":"Hello everyone I'm Omar and I'm 24 years old I live in Cairo",
    "format": {
        "name": {"type":"string"},
        "age": {"type":"number"},
        "city": {"type":"string"}
    }
}

Output example 
{
  "name":"Omar",
  "age":24,
  "city":"Cairo",
}
  
