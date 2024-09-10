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
