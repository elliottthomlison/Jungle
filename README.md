# Jungle

Jungle is a mini e-commerce application built with Rails and Ruby on Rails. It is the fifth project built during the Lighthouse Labs Web Development Bootcamp. Jungle enables a user to browse the options that are available in the store whereby they can add and remove items into a cart. They are also able to create an account, log in, and interact with their account there.  

## Final Product
<p float="center">
  <img src="https://raw.githubusercontent.com/elliottthomlison/Jungle/master/docs/main.gif" width=600px height=600px/>
  <img src="https://github.com/elliottthomlison/Jungle/blob/master/Jungle.png?raw=true"/>
  <img src="https://github.com/elliottthomlison/Jungle/blob/master/Jungle2.png?raw=true"/>
  <img src="https://github.com/elliottthomlison/Jungle/blob/master/Jungle3.png?raw=true"/>
  <img src="https://github.com/elliottthomlison/Jungle/blob/master/Jungle4.png?raw=true"/>
</p>
## Setup

1. Run `bundle install` to install dependencies
2. Create `config/database.yml` by copying `config/database.example.yml`
3. Create `config/secrets.yml` by copying `config/secrets.example.yml`
4. Run `bin/rake db:reset` to create, load and seed db
5. Create .env file based on .env.example
6. Sign up for a Stripe account
7. Put Stripe (test) keys into appropriate .env vars
8. Run `bin/rails s -b 0.0.0.0` to start the server

## Stripe Testing

Use Credit Card # 4111 1111 1111 1111 for testing success scenarios.

More information in their docs: <https://stripe.com/docs/testing#cards>

## Dependencies

* Rails 4.2 [Rails Guide](http://guides.rubyonrails.org/v4.2/)
* PostgreSQL 9.x
* Stripe
