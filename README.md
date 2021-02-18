[![forthebadge](https://forthebadge.com/images/badges/built-with-love.svg)](https://forthebadge.com)
[![forthebadge](https://forthebadge.com/images/badges/60-percent-of-the-time-works-every-time.svg)](https://forthebadge.com)
## Build steps
> composer install
> 
> php artisan db:create

> php artisan migrate

> php artisan db:seed

> php artisan passport:install

> php artisan serve


## Endpoints

    POST '/api/login'
    POST '/api/register'
    GET '/api/events'
    GET '/api/all_bookings'
    POST '/api/new_booking'
    PUT '/api/booking/{id}'
    DELETE '/api/booking/delete/{id}'
#### Payloads:
> example endpoint -> ['field_name|datatype']

> login -> ['email|string', 'password|string']

> register -> ['name|string', 'email"string', 'password|string']

> new_booking ->['events_id|integer', 'delivery_address|string', 'ticket_quantity|integer']

> booking/{id} -> ['delivery_address|string']
