# Pride Month Film Fest

Professional announcement of the Pride Month Film Fest event in the Entertainment industry.

![Thumbnail](./thumbnail.png)

## Template Details

- **Industries:** Entertainment
- **Message Type:** Events
- **Tags:** celebration, pridemonth, filmfest, lgbtq+

## Files
- `index.html`: The improved, localized, and branded HTML template.
- `template.blade.php`: Ready-to-use Laravel Blade template with `asset()` helpers.
- `assets/`: Directory containing localized images and styles used in the template.

## Usage in Laravel

### 1. Store the Template
Place the `index.html` content in a Blade view (e.g., `resources/views/emails/pride-month-film-fest.blade.php`).

### 2. Handle Assets
Move the content of `assets/` to your public directory (e.g., `public/vendor/mail-templates/pride-month-film-fest/`) and update the paths in the HTML to use the `asset()` helper.

### 3. Send Email
```php
Mail::to($user)->send(new \App\Mail\GenericEmail([
    'view' => 'emails.pride-month-film-fest',
    'data' => [
        // Your dynamic data here
    ]
]));
```

---
*Created with ❤️ by **[LaravelMail.com](https://laravelmail.com)** - Your source for professional email templates.*
