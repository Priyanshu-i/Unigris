Meta tags in HTML provide metadata about the HTML document and are crucial for SEO, social media sharing, and browser behavior. Here are the commonly used meta tags, including those for author name, keywords, and other SEO-friendly data:

### Basic Meta Tags
```html
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<meta http-equiv="X-UA-Compatible" content="IE=edge">
```

### SEO Meta Tags
```html
<meta name="description" content="A brief description of the page's content for search engines.">
<meta name="keywords" content="keyword1, keyword2, keyword3">
<meta name="author" content="Author Name">
```

### Social Media Meta Tags (Open Graph for Facebook, Twitter Cards)
```html
<!-- Open Graph / Facebook -->
<meta property="og:type" content="website">
<meta property="og:title" content="Your Page Title">
<meta property="og:description" content="A brief description of the page's content.">
<meta property="og:image" content="https://www.example.com/image.jpg">
<meta property="og:url" content="https://www.example.com">
<meta property="og:site_name" content="Your Site Name">
<meta property="og:locale" content="en_US">

<!-- Twitter Card -->
<meta name="twitter:card" content="summary_large_image">
<meta name="twitter:title" content="Your Page Title">
<meta name="twitter:description" content="A brief description of the page's content.">
<meta name="twitter:image" content="https://www.example.com/image.jpg">
<meta name="twitter:site" content="@YourTwitterHandle">
<meta name="twitter:creator" content="@AuthorTwitterHandle">
```

### Additional Useful Meta Tags
```html
<meta name="robots" content="index, follow">
<meta name="googlebot" content="index, follow">
<meta name="bingbot" content="index, follow">
<meta name="revisit-after" content="7 days">
<meta name="rating" content="General">
<meta name="distribution" content="Global">
```

### Mobile and App Meta Tags
```html
<meta name="apple-mobile-web-app-capable" content="yes">
<meta name="apple-mobile-web-app-status-bar-style" content="black-translucent">
<meta name="mobile-web-app-capable" content="yes">
```

### Language and Geo Meta Tags
```html
<meta name="language" content="English">
<meta name="geo.region" content="US-CA">
<meta name="geo.placename" content="San Francisco">
<meta name="geo.position" content="37.7749;-122.4194">
<meta name="ICBM" content="37.7749, -122.4194">
```

### Example of a Complete Set of Meta Tags
Here's a complete example of an HTML document with a comprehensive set of meta tags:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="description" content="A brief description of the page's content for search engines.">
    <meta name="keywords" content="keyword1, keyword2, keyword3">
    <meta name="author" content="Author Name">
    <meta name="robots" content="index, follow">
    <meta name="googlebot" content="index, follow">
    <meta name="bingbot" content="index, follow">
    <meta name="revisit-after" content="7 days">
    <meta name="rating" content="General">
    <meta name="distribution" content="Global">
    <meta name="language" content="English">
    <meta name="geo.region" content="US-CA">
    <meta name="geo.placename" content="San Francisco">
    <meta name="geo.position" content="37.7749;-122.4194">
    <meta name="ICBM" content="37.7749, -122.4194">

    <!-- Open Graph / Facebook -->
    <meta property="og:type" content="website">
    <meta property="og:title" content="Your Page Title">
    <meta property="og:description" content="A brief description of the page's content.">
    <meta property="og:image" content="https://www.example.com/image.jpg">
    <meta property="og:url" content="https://www.example.com">
    <meta property="og:site_name" content="Your Site Name">
    <meta property="og:locale" content="en_US">

    <!-- Twitter Card -->
    <meta name="twitter:card" content="summary_large_image">
    <meta name="twitter:title" content="Your Page Title">
    <meta name="twitter:description" content="A brief description of the page's content.">
    <meta name="twitter:image" content="https://www.example.com/image.jpg">
    <meta name="twitter:site" content="@YourTwitterHandle">
    <meta name="twitter:creator" content="@AuthorTwitterHandle">

    <!-- Mobile and App Meta Tags -->
    <meta name="apple-mobile-web-app-capable" content="yes">
    <meta name="apple-mobile-web-app-status-bar-style" content="black-translucent">
    <meta name="mobile-web-app-capable" content="yes">

    <title>Your Page Title</title>
</head>
<body>
    <!-- Page Content -->
</body>
</html>
```

This comprehensive set of meta tags covers various aspects of SEO, social media integration, mobile optimization, and geographic metadata, ensuring that your HTML document is well-optimized for search engines and social media platforms.