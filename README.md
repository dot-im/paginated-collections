# Paginated Collections in Laravel

## Use Case
Laravel provides pagination out of the box for Eloquent Collections, but you can't use that by default on ordinary Collections.

Collections do have the `forPage()` method, but it's more low-level, so it doesn't generate pagination links.


## Installation
```bash
composer require dot-im/paginated-collections
```

## Usage

```php
collect([ ... ])->paginate( 20 );
```
