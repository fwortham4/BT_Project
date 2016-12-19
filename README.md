# BT Project

An example Braintree's v.zero API integration, with Hosted Fields, for a Ruby on Rails application.

## Setup Instructions

1. Install bundler:

  ```sh
  gem install bundler
  ```

2. Bundle:

  ```sh
  bundle
  ```

3. Create a new, local file named `.env` and fill in your Braintree API credentials. Credentials can be found by navigating to Account > My User > View Authorizations in the Braintree Control Panel. Full instructions can be [found on the Braintree support site](https://articles.braintreepayments.com/control-panel/important-gateway-credentials#api-credentials).

4. Start rails:

  ```sh
  rails server
  ```

5. Use the following fake credit card number:
```sh
4111 1111 1111 1111
```

## Disclaimer

This code is provided as is and is only intended to be used for illustration purposes. This code is not production-ready and is not meant to be used in a production environment. This repository is to be used as a tool to help merchants learn how to integrate with Braintree. Any use of this repository or any of its code in a production environment is highly discouraged.
