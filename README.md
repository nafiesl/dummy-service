# Dummy Lumen PHP Framework

A lumen service for dummy service to test error responses on localhost.

## How to Use

1. Clone this repo
2. `$ composer install --no-dev`
3. Start php server: `$ php -S localhost:8000 -t public`

## Usage Example

```
curl -X POST 'http://localhost:8000/tags/object/contacts/999'
```
Response
```
{
    "post": 504
}
```
```
Status: 504Gateway Timeout
Time: 57 ms
Size: 282 B
```

Play around with routes on `routes/web.php` for any response we need.
