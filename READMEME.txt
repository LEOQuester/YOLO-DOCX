____To categorize the your prompts into labels use the following formats
Endpoint : http://localhost:5000/api/Categorize
example: 
_______________________________________________________
POST JSON
Sample Request:
{
 "token" : "YOUR_API_KEY",
 "prompt": "YOUR_THOUGHTS_HERE"
}


Sample response : 
{
 "labels": [
	"action",
	"hero"
  ],
 "success":true
}


____To fetch any media files you need you can use following endpoint
______________________________________________________
GET PARAMS
Endpoint : http://localhost:5000/api/media?title=YOUR_TITLE&media_type=MEDIA_TYPE&api_key=YOUR_API_KEY