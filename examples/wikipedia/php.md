## Simple example using PHP

```php
# Replace "kremilly" with your GitHub username
$url = 'https://api.kremilly.com/wikipedia?user=kremilly';
$data = file_get_contents($url);
$response = json_decode($data);

print_r($response);
```
