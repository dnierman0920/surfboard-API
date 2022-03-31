# Project: surfboardAPI
An Api that returns information about different surfboards
# 📁 Collection: Auth 


## End-point: sign-up
Signs up new user
### Method: POST
>```
>{{url}}/sign-up
>```
### Body (**raw**)

```json
{
    "credentials": {
      "email": "myemailname@email.com",
      "password": "S3curity!",
      "password_confirmation": "S3curity!"
    }
}
```


⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃

## End-point: sign-out
signs out user
### Method: DELETE
>```
>{{url}}/sign-out
>```
### Headers

|Content-Type|Value|
|---|---|
|||


### Body (**raw**)

```json

```

### 🔑 Authentication bearer

|Param|value|Type|
|---|---|---|
|token|9a6729650601276bf517e007a3b3747a|string|



⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃

## End-point: sign-in
signs in a previously created user
### Method: POST
>```
>{{url}}/sign-in
>```
### Body (**raw**)

```json
{
    "credentials": {
       "email": "davidnierman93@gmail.com",
      "password": "S3curity!"
    }
  }
```


⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃

## End-point: change password
updates a surfboards information
### Method: PATCH
>```
>{{url}}/change-password
>```
### Body (**raw**)

```json
{
      "old": "an example password",
      "new": "super sekrit"
    }
```

### 🔑 Authentication bearer

|Param|value|Type|
|---|---|---|
|token|9a6729650601276bf517e007a3b3747a|string|



⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃
# 📁 Collection: surfboard 


## End-point: create a surfboard
Creates a new surfboard
### Method: POST
>```
>{{url}}/surfboards
>```
### Body (**raw**)

```json
{
    "surfboard": {
        "type": "longboard",
        "height": 120,
        "width": 30,
        "fins": "single"
    }

}
```

### 🔑 Authentication bearer

|Param|value|Type|
|---|---|---|
|token|4731ac2944c1fb84159b2dd6b9d4a956|string|



⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃

## End-point: show a surfboard
Shows a sufboard's information
### Method: GET
>```
>{{url}}/surfboards/6245132586c97e37690a39e9
>```
### Body (**raw**)

```json

```

### 🔑 Authentication bearer

|Param|value|Type|
|---|---|---|
|token|4731ac2944c1fb84159b2dd6b9d4a956|string|



⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃

## End-point: update a surfboard
### Method: PATCH
>```
>{{url}}/surfboards/6245132586c97e37690a39e9
>```
### Body (**raw**)

```json
{
    "surfboard": {
        "type": "fish",
        "height": 65,
        "width": 28,
        "fins": "twin"
    }

}
```

### 🔑 Authentication bearer

|Param|value|Type|
|---|---|---|
|token|4731ac2944c1fb84159b2dd6b9d4a956|string|



⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃

## End-point: index surfboards
Shows all surfboards
### Method: GET
>```
>{{url}}/surfboards
>```
### Body (**raw**)

```json

```

### 🔑 Authentication bearer

|Param|value|Type|
|---|---|---|
|token|4731ac2944c1fb84159b2dd6b9d4a956|string|



⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃

## End-point: delete a surfboard
Deletes a surfboard
### Method: DELETE
>```
>{{url}}/surfboards/6245132586c97e37690a39e9
>```
### 🔑 Authentication bearer

|Param|value|Type|
|---|---|---|
|token|4731ac2944c1fb84159b2dd6b9d4a956|string|



⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃
_________________________________________________
Powered By: [postman-to-markdown](https://github.com/bautistaj/postman-to-markdown/)
