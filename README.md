# docs
##Navigation
1. [Roles](#Roles);
2. [Views](#Views);
3. [Models](#Models);

## <a name="Views"/> VIEWS

#### Registration

* url: domen.com/registration
* input: user info
* output: redirect to profile page

#### Login

* url: domen.com/login
* input: login, password
* output: redirect to profile page

#### Profile

* url: domen.com/user/{id}
* response: Dashboard page

## <a name="Models"/> MODELS

#### USERS
* id
* subscription-plan
* balance
* bit-coin
* sp-expive-date
* user-login
* user-password
* reg-ip-adresss
* last-ip-adress
* email-notification

#### USERS_INFO 
* id
* phone
* country
* city
* state
* zip_code
* skype
* telegram
* first_name
* last_name
* user_registred

#### PRODUCTS 
* id
* name
* descriptions
* image
* price
* video
* type
* value
* quantity
* matrix_depth
* bonus
* icon
* retive

#### TRANSACTIONS
* id
* user_id
* refferal_id
* date
* type
* status
* cash
* bit_coin
* shop_order
* description
* hash




