**

## axios8dev


A Remake of Axios that supports like axios only nodeJS form-data library but like axios, can be extended to support other types of FormData using Axios Middleware (requests interceptors) and axios transformRequest.

Its particularity is that in nodeJS hybrid environnement like electronJS, it permits to avoid HTTP 400, 415 and 500 (The major errors that I encountered) when posting node form-data to a Rest Server.



## How to install it ?

Using npm:

    npm install --save axios8dev

Using bower:

    $ bower install axios8dev

Using yarn:

    $ yard add axios8dev

Using pnpm:

    $ pnpm add axios8dev



## How to use it ?

    const axios = require('axios8dev')
    const axios = require('axios8dev').default

It has the same api as axios so be free to look at the official docs of [axios](https://github.com/axios/axios).
