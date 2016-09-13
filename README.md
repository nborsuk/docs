# docs
##Navigation
1. [Roles](#Roles);
2. [Views](#Views);
3. [Models](#Models);

## <a name="Views"/> VIEWS

#### Registration

* url: domen.com/registration
* request: user info
* response: profile page

#### Login

* url: domen.com/login
* request: login, password
* response: redirect to profile page

#### Profile

* url: domen.com/user/{id}
* request: -
* response: profile info

#### Dashboard

* url: domen.com/user/{id}/dashboard
* request: -
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
* id (foreign key USERS(id))
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
* user_id (foreign key USERS(id))
* refferal_id
* date
* type
* status
* cash
* bit_coin
* shop_order
* description
* hash




