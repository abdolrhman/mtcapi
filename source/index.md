---
title: API Reference

language_tabs:
- bash
- javascript

includes:

search: true

toc_footers:
- <a href='http://github.com/mpociot/documentarian'>Documentation Powered by Documentarian</a>
---

# Info

Welcome to the generated API reference.
[Get Postman Collection](public/docs/collection.json)

# Available routes
#Account
Make the Account of the user and Add the right credential to the User ,
## All
all drivers

> Example request:

```bash
curl "http://localhost/api/v1/account/all" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "http://localhost/api/v1/account/all",
    "method": "GET",
        "headers": {
    "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
console.log(response);
});
```

> Example response:

```json
null
```

### HTTP Request
`GET api/v1/account/all`

`HEAD api/v1/account/all`


## CheckCredential
Api call to authenticate the user -- returns ServiceResponse object

> Example request:

```bash
curl "http://localhost/api/v1/account/checkCredentials" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "http://localhost/api/v1/account/checkCredentials",
    "method": "POST",
        "headers": {
    "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
console.log(response);
});
```


### HTTP Request
`POST api/v1/account/checkCredentials`


## Update Profile
Api call to update the profile -- returns ServiceResponse object

> Example request:

```bash
curl "http://localhost/api/v1/account/updateProfile" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "http://localhost/api/v1/account/updateProfile",
    "method": "POST",
        "headers": {
    "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
console.log(response);
});
```


### HTTP Request
`POST api/v1/account/updateProfile`


## Change Password
Api call to change the password -- returns ServiceResponse object

> Example request:

```bash
curl "http://localhost/api/v1/account/changePassword" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "http://localhost/api/v1/account/changePassword",
    "method": "POST",
        "headers": {
    "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
console.log(response);
});
```


### HTTP Request
`POST api/v1/account/changePassword`


#Route
route with CRUD operations
## StartTrip
starting the trip automatically based on pre-settings for the supervisor

> Example request:

```bash
curl "http://localhost/api/v1/route/startTrip" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "http://localhost/api/v1/route/startTrip",
    "method": "POST",
        "headers": {
    "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
console.log(response);
});
```


### HTTP Request
`POST api/v1/route/startTrip`


## Createt Route
create the route through API call

> Example request:

```bash
curl "http://localhost/api/v1/route/createAPI" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "http://localhost/api/v1/route/createAPI",
    "method": "POST",
        "headers": {
    "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
console.log(response);
});
```


### HTTP Request
`POST api/v1/route/createAPI`


## Stop Point CheckIn
check in into stop point

> Example request:

```bash
curl "http://localhost/api/v1/route/stopPointCheckIn" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "http://localhost/api/v1/route/stopPointCheckIn",
    "method": "POST",
        "headers": {
    "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
console.log(response);
});
```


### HTTP Request
`POST api/v1/route/stopPointCheckIn`


## Stop Point CheckOut
check out from strop point

> Example request:

```bash
curl "http://localhost/api/v1/route/stopPointCheckOut" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "http://localhost/api/v1/route/stopPointCheckOut",
    "method": "POST",
        "headers": {
    "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
console.log(response);
});
```


### HTTP Request
`POST api/v1/route/stopPointCheckOut`


## EndTrip
check User credential and end the trip

> Example request:

```bash
curl "http://localhost/api/v1/route/endTrip" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "http://localhost/api/v1/route/endTrip",
    "method": "POST",
        "headers": {
    "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
console.log(response);
});
```


### HTTP Request
`POST api/v1/route/endTrip`


## attend student
Supervisor(driver) attend User

> Example request:

```bash
curl "http://localhost/api/v1/route/attendStudent" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "http://localhost/api/v1/route/attendStudent",
    "method": "POST",
        "headers": {
    "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
console.log(response);
});
```


### HTTP Request
`POST api/v1/route/attendStudent`


## Attend Student Self
User attend him slef

> Example request:

```bash
curl "http://localhost/api/v1/route/attendStudentSelf" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "http://localhost/api/v1/route/attendStudentSelf",
    "method": "POST",
        "headers": {
    "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
console.log(response);
});
```


### HTTP Request
`POST api/v1/route/attendStudentSelf`


#User 
CRUD operations For User
## Create User
create the user through API call

> Example request:

```bash
curl "http://localhost/api/v1/user/createAPI" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "http://localhost/api/v1/user/createAPI",
    "method": "POST",
        "headers": {
    "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
console.log(response);
});
```


### HTTP Request
`POST api/v1/user/createAPI`


## get Route
return the route of bus

> Example request:

```bash
curl "http://localhost/api/v1/user/get_routes" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "http://localhost/api/v1/user/get_routes",
    "method": "POST",
        "headers": {
    "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
console.log(response);
});
```


### HTTP Request
`POST api/v1/user/get_routes`


## go online
set user to be online

> Example request:

```bash
curl "http://localhost/api/v1/user/goOnline" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "http://localhost/api/v1/user/goOnline",
    "method": "POST",
        "headers": {
    "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
console.log(response);
});
```


### HTTP Request
`POST api/v1/user/goOnline`


## get offline
set user to be online

> Example request:

```bash
curl "http://localhost/api/v1/user/goOffline" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "http://localhost/api/v1/user/goOffline",
    "method": "POST",
        "headers": {
    "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
console.log(response);
});
```


### HTTP Request
`POST api/v1/user/goOffline`


## get all online Users

> Example request:

```bash
curl "http://localhost/api/v1/user/getAllOnlineUsers" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "http://localhost/api/v1/user/getAllOnlineUsers",
    "method": "POST",
        "headers": {
    "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
console.log(response);
});
```


### HTTP Request
`POST api/v1/user/getAllOnlineUsers`


## getRouteOnlineUsers

> Example request:

```bash
curl "http://localhost/api/v1/user/getRouteOnlineUsers" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "http://localhost/api/v1/user/getRouteOnlineUsers",
    "method": "POST",
        "headers": {
    "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
console.log(response);
});
```


### HTTP Request
`POST api/v1/user/getRouteOnlineUsers`


## supervisor checkin
checkIn Supervisor

> Example request:

```bash
curl "http://localhost/api/v1/user/supervisorCheckIn" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "http://localhost/api/v1/user/supervisorCheckIn",
    "method": "POST",
        "headers": {
    "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
console.log(response);
});
```


### HTTP Request
`POST api/v1/user/supervisorCheckIn`


## checkIn Supervisor

> Example request:

```bash
curl "http://localhost/api/v1/user/supervisorCheckOut" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "http://localhost/api/v1/user/supervisorCheckOut",
    "method": "POST",
        "headers": {
    "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
console.log(response);
});
```


### HTTP Request
`POST api/v1/user/supervisorCheckOut`


## getSingleOnlineUser

> Example request:

```bash
curl "http://localhost/api/v1/user/getSingleOnlineUser" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "http://localhost/api/v1/user/getSingleOnlineUser",
    "method": "POST",
        "headers": {
    "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
console.log(response);
});
```


### HTTP Request
`POST api/v1/user/getSingleOnlineUser`


## checkIn User

> Example request:

```bash
curl "http://localhost/api/v1/user/userCheckInDestination" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "http://localhost/api/v1/user/userCheckInDestination",
    "method": "POST",
        "headers": {
    "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
console.log(response);
});
```


### HTTP Request
`POST api/v1/user/userCheckInDestination`


#AboutBus
About bus controller
## aboutUs
return the aboutUs object .

> Example request:

```bash
curl "http://localhost/api/v1/aboutus/aboutUs" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "http://localhost/api/v1/aboutus/aboutUs",
    "method": "POST",
        "headers": {
    "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
console.log(response);
});
```


### HTTP Request
`POST api/v1/aboutus/aboutUs`


#contactUs
return Contact Us information
## send Message
save the message been sent by the use and give contact info .

> Example request:

```bash
curl "http://localhost/api/v1/contactus/sendMessage" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "http://localhost/api/v1/contactus/sendMessage",
    "method": "POST",
        "headers": {
    "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
console.log(response);
});
```


### HTTP Request
`POST api/v1/contactus/sendMessage`


#FeedBack Controller
## Send FeedBack

> Example request:

```bash
curl "http://localhost/api/v1/feedback/sendFeedback" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "http://localhost/api/v1/feedback/sendFeedback",
    "method": "POST",
        "headers": {
    "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
console.log(response);
});
```


### HTTP Request
`POST api/v1/feedback/sendFeedback`


