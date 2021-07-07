# Nop Commerce V4.30

Nop commerce is an open source platform for developing ecommerce websties. Please fnd more details [here](https://nopcommerce.com/)

## Getting Started

This plugin provides a RESTful API for managing resources in nopCommerce. The contains some extended functonality of the original plugin

You can find the github link of plugin [here](https://github.com/SevenSpikes/api-plugin-for-nopcommerce)

## How to use API
1. In Admin pannel Configuration -> Local Plugin -> Nop Api -> Install
2. Give the user role which can access the API **Api User** role
3. If error occured 'The 'AppId' option must be provided', this is because of the facebook plugin after uninstalling it it will get resolved.
4. Add the postman collection (../postman collection) and set the environment variable.
5. You can get token from 'Get Token' API and start using other API, for some i have added postman example also.

Please make sure the user must have 'Api User' role while you fetch token

There are other API's but i have not added them in postman collection. Please checkin if you are using this.

## What about security?

The API plugin currently supports OAuth 2.0 Authorization Code grant type flow. So in order to access the resource endpoints you need to provide a valid AccessToken. To understand how the authorization code grant flow works please refer to the [**Sample Application**](https://github.com/SevenSpikes/nopCommerce-Api-SampleApplication).

