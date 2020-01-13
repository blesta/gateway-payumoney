# PayUmoney Gateway

[![Build Status](https://travis-ci.org/blesta/gateway-payumoney.svg?branch=master)](https://travis-ci.org/blesta/gateway-payumoney) [![Coverage Status](https://coveralls.io/repos/github/blesta/gateway-payumoney/badge.svg?branch=master)](https://coveralls.io/github/blesta/gateway-payumoney?branch=master)

This is a nonmerchant gateway for Blesta that integrates with [PayUmoney](https://www.payu.in/).

## Install the Gateway

1. You can install the gateway via composer:

    ```
    composer require blesta/payumoney
    ```

2. Upload the source code to a /components/gateways/nonmerchant/payumoney/ directory within
your Blesta installation path.

    For example:

    ```
    /var/www/html/blesta/components/nonmerchant/payumoney/
    ```

3. Log in to your admin Blesta account and navigate to
> Settings > Payment Gateways

4. Find the PayUmoney gateway and click the "Install" button to install it

5. You're done!

### Blesta Compatibility

|Blesta Version|Module Version|
|--------------|--------------|
|< v4.8.0|v1.0.0|
|>= v4.8.0|v1.1.0|
