# Go API client for openapi

No description provided (generated by Openapi Generator https://github.com/openapitools/openapi-generator)

## Overview
This API client was generated by the [OpenAPI Generator](https://openapi-generator.tech) project.  By using the [OpenAPI-spec](https://www.openapis.org/) from a remote server, you can easily generate an API client.

- API version: 1.0.0
- Package version: 1.0.0
- Build package: org.openapitools.codegen.languages.GoClientCodegen

## Installation

Install the following dependencies:

```shell
go get github.com/stretchr/testify/assert
go get golang.org/x/oauth2
go get golang.org/x/net/context
go get github.com/antihax/optional
```

Put the package under your project folder and add the following in import:

```golang
import "./openapi"
```

## Documentation for API Endpoints

All URIs are relative to *http://localhost*

Class | Method | HTTP request | Description
------------ | ------------- | ------------- | -------------
*AuthApi* | [**AuthLoginPost**](docs/AuthApi.md#authloginpost) | **Post** /auth/login | Login
*AuthApi* | [**AuthMeGet**](docs/AuthApi.md#authmeget) | **Get** /auth/me | Me


## Documentation For Models

 - [AuthLoginPayload](docs/AuthLoginPayload.md)
 - [InlineObject](docs/InlineObject.md)


## Documentation For Authorization



## bearer

- **Type**: HTTP basic authentication

Example

```golang
auth := context.WithValue(context.Background(), sw.ContextBasicAuth, sw.BasicAuth{
    UserName: "username",
    Password: "password",
})
r, err := client.Service.Operation(auth, args)
```



## Author



