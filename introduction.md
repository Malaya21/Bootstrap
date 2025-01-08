
# Introduction to Bootstrap

Bootstrap is a powerful front-end framework for faster and easier web development. It includes HTML, CSS, and JavaScript components for creating responsive and mobile-first websites. With Bootstrap, you can quickly design and customize responsive web pages without having to write extensive CSS from scratch.

Bootstrap provides a grid system, pre-designed components, and utility classes that help you build a consistent and visually appealing layout. It is widely used by developers due to its ease of use, flexibility, and extensive documentation.
## Example of Using Bootstrap CDN

To use Bootstrap via CDN, you can include the following HTML code in the `<head>` section of your HTML document:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Bootstrap CDN Example</title>
    <!-- Bootstrap CSS -->
    <link href="https://stackpath.bootstrapcdn.com/bootstrap/5.1.3/css/bootstrap.min.css" rel="stylesheet">
</head>
<body>
    <div class="container">
        <h1 class="text-center">Hello, Bootstrap!</h1>
        <p class="lead">This is an example of using Bootstrap via CDN.</p>
    </div>
    
</body>
</html>
```

This code includes the necessary Bootstrap CSS files from a CDN, allowing you to use Bootstrap's features in your web page.
## Advantages of Using Bootstrap CDN vs. Locally

### Using Bootstrap CDN

1. **Faster Load Times**: CDNs are optimized for delivering static content quickly, which can result in faster load times for your website.
2. **Caching**: Since many users may already have the Bootstrap files cached in their browsers from other websites, your site can load even faster.
3. **Reduced Server Load**: Offloading the delivery of Bootstrap files to a CDN reduces the load on your own server.
4. **Automatic Updates**: Using a CDN ensures that you are always using the latest version of Bootstrap without having to manually update the files.

### Using Bootstrap Locally

1. **Offline Development**: Having Bootstrap files locally allows you to develop and test your website without an internet connection.
2. **Customization**: You can easily customize and modify the Bootstrap files to suit your specific needs.
3. **Version Control**: You have full control over which version of Bootstrap you are using, which can be important for maintaining compatibility with other libraries or frameworks.
4. **Security**: Hosting Bootstrap files locally can reduce the risk of relying on third-party servers, which might be compromised.


# Bootstrap Container

Bootstrap having 5 screen sizes:
- Extra Small - < 576
- Small -sm- < 768
- Medium -md- < 992
- Large -lg- < 1200
- Extra Large -xl- < 1400
- Extra Extra Large -xxl- > 1400

By using all this we can provide different types of styling for different screen sizes which makes our website responsive.

## Size for devices
- For mobile devices, extra small size is used.
- For tablets, small and medium sizes are used.
- For desktops and other big screens, large, extra large, and so on sizes are used.
