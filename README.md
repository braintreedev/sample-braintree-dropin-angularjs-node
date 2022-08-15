<h2>This repo is on a path to being archived, checkout our other resources in github.com/paypal</h2>

# braintree-dropin-angularjs-node
Braintree Dropin built with Node on the backend and AngularJS on the frontend.

## 1) NODE SERVER: Installation and usage

* Navigate to `/node-server`
* Run `npm install` to install all dependencies
* Run `npm start` to start the Express app

## 2) ANGULAR APP: Usage

* Open a new terminal (or prompt) window (don't stop NODE SERVER)
* Navigate to `/angular-app`
* Run `python -m SimpleHTTPServer 5000` to serve the Angular app
* Visit [http://localhost:5000](http://localhost:5000) in your browser
* Fill in the form using a Credit Card:
    * Number: `4111 1111 1111 1111`
    * CVV: `123`
    * Expiration date: `11/2020`
    
## Useful links

* [v.zero](https://www.braintreepayments.com/v.zero)
* [The Braintree Node.js SDK](https://developers.braintreepayments.com/javascript+node/sdk/server/overview)
