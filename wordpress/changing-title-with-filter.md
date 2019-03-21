Changing Title with Filter
--------------------------

```php
add_filter( 'pre_get_document_title', function ( $old_title ) {
    return 'New Title';
} );
```

[pre_get_document_title](https://developer.wordpress.org/reference/hooks/pre_get_document_title/)
