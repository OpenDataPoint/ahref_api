# Ahrefs API 🚀
The Ahrefs API provides access to powerful SEO metrics and data 📊. Currently, it offers one endpoint that delivers essential domain authority metrics.

# Endpoint: DR & AR 📈
This endpoint allows you to retrieve the Domain Rating (DR) and Ahrefs Rank (AR) for a specified domain.

# Request 🔍
GET https://ahrefs-api.p.rapidapi.com/check-dr-ar

## Parameters

|       Name         |Type                          |Description|
|----------------|-------------------------------|-----------------------------|
|    domain      |      string                   |The domain to check (required)    


## Headers
- x-rapidapi-host: ahrefs-api.p.rapidapi.com
- x-rapidapi-key: YOUR_RAPIDAPI_KEY

# Response 📊
The API returns a JSON object with the following properties:
## Parameters

|       Property         |Type                          |Description|
|----------------|-------------------------------|-----------------------------|
|    domain      |      string                   |The domain that was checked     
| domain_rating  |      integer                  |Domain Rating (DR) score (0-100)     
| ahrefs_rank    |      integer                  |Ahrefs Rank (AR) - lower numbers indicate higher rank   

# Example 💡

### base
```bash curl --request GET \
	--url 'https://ahrefs-api.p.rapidapi.com/check-dr-ar?domain=facebook.com' \
	--header 'x-rapidapi-host: ahrefs-api.p.rapidapi.com' \
	--header 'x-rapidapi-key: fd3f1114b1msh3d69719929fe501p1f1b72jsn2432d43bd3d1'
```

 # Response

 {
  "domain": "facebook.com",
  "domain_rating": 100,
  "ahrefs_rank": 1
}


### This endpoint provides a quick way to assess the authority and popularity of a domain in the eyes of Ahrefs 🏆. Use it to compare websites, evaluate link prospects, or track your own domain's progress over time!


# [Check Ahrefs API](https://rapidapi.com/opendatapoint-opendatapoint-default/api/ahrefs-api/playground)
