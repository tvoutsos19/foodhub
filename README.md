# Foodhub

Here is our target for this project:

[https://foodhub.matchthetarget.com](https://foodhub.matchthetarget.com)

## Standard asset links

I place these in the `<head>` of _almost_ every HTML document I write:

```html
<!-- Expand the number of characters we can use in the document beyond basic ASCII 🎉 -->
<meta charset="utf-8">

<!-- Connect Font Awesome CSS -->
<link rel="stylesheet" href="https://use.fontawesome.com/releases/v5.0.13/css/all.css">

<!-- Connect Bootstrap CSS -->
<link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.4.1/css/bootstrap.min.css">

<!-- Connect Bootstrap JavaScript and its dependencies -->
<script src="https://cdnjs.cloudflare.com/ajax/libs/jquery/3.4.1/jquery.js"></script>
<script src="https://stackpath.bootstrapcdn.com/bootstrap/4.4.1/js/bootstrap.bundle.min.js"></script>

<!-- Make it responsive to small screens -->
<meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">
```

## Standard Workflow

 1. Start the web server with bin/server.
 1. Navigate to your live application preview.
 1. As you work, remember to navigate to /git and **Always Be Committing.**
 1. Run `rails grade` as often as you like to see how you are doing, but **make sure you test your app manually to make sure it matches the target's behavior first**.

## Recommended steps

 1. Get as far as you can [with Bootstrap alone](https://getbootstrap.com/docs/4.4/components/alerts/).
 1. Then add your own external stylesheet and sprinkle in your own CSS as needed.
 1. Post questions on Piazza!

## Images

All of the images you need to build the landing page are already uploaded to the `/public/images/` folder.

## Useful CSS properties

To set a background image that retains its aspect ratio no matter how an element gets resized,

```css
.who-delivers {
  background: url("images/main-hero.jpg") no-repeat center center;
  background-size: cover;
}
```


## Specs
<details>
  <summary>Click here to see names of each test</summary>

The landing page has only one nav tag. 

The landing page has a nav tag that contains the 'FOODHUB' link. 

The landing page has a nav tag that contains the 'Sign In' link. 

The landing page has a nav tag that contains the shopping icon link. 

The landing page has only one footer. 

The landing page has at least one label.

The landing page has at least two label. 

The landing page has exactly 3 labels. 

The landing page has a label with the text 'Enter your address below.'.

The landing page has a label with the text 'Email address'. 

The landing page has a label with the text 'Zip Code'. 

The landing page has a label 'Enter your address below.' with a for attribute that is not empty. 

The landing page has a label 'Enter your address below.' with a matching input tag. 

The landing page has a label 'Email address' with a for attribute that is not empty. 

The landing page has a label 'Email address' with a matching input tag. 

The landing page has a label 'Zip Code' with a for attribute that is not empty. 

The landing page has a label 'Zip Code' with a matching input tag. 

The landing page should have a nav element with a mostly red background color. 

The landing page should have a link in a nav with the text 'FOODHUB' in white text. 

The landing page should have a secondary heading with the text 'Who delivers in your neighborhood?' in white text. 

The landing page should have a label with the text 'Enter your address below.' in white text. 

The landing page should have a secondary heading with the text 'How to Foodhub' in non-white text.

The landing page should have a fourth level heading with the text 'The where' in non-white text.

The landing page should have a fourth level heading with the text 'The what' in non-white text.

The landing page should have a fourth level heading with the text 'The delivery' in non-white text.

The landing page should have a secondary heading with the text 'Download apps' in white text. 

The landing page should have a paragraph with the text 'Millions of users...' in white text. 

The landing page should have the 'app-store-badge.png' resized to be 200 pixels. 

The landing page should have the 'google-play-badge.png' resized to be 200 pixels. 

The landing page has the 'gem.jpg' reshaped to be a circle (has a border-radius of 50%.) 

The landing page has the 'like.jpg' reshaped to be a circle (has a border-radius of 50%.) 

The landing page has the 'bite.jpg' reshaped to be a circle (has a border-radius of 50%.) 

The landing page has a footer element that has a dark blue background color. 

The landing page should have a fourth level heading with the text 'Sign up for special offers' in white text. 

The landing page should have a fourth level heading with the text 'Get to know us' in white text. 

The landing page should have a fourth level heading with the text 'Help' in white text. 

The landing page should have a fourth level heading with the text 'Connect with us' in white text. 

The landing page should have a fourth level heading with the text 'Partner with us' in white text. 

The landing page should have a list item with the text 'About Foodhub' in white text. 

The landing page should have a list item with the text 'Our apps' in white text. 

The landing page should have a list item with the text 'Our blog' in white text. 

The landing page should have a list item with the text 'Careers' in white text. 

The landing page should have a list item with the text 'Investor relations' in white text. 

The landing page should have a list item with the text 'News' in white text. 

The landing page has the images 'map.jpg' and 'menu.jpg' next to each other when browser width is >= 768px. 

The landing page should have the images 'menu.jpg' and 'delivery.jpg' next to each other when browser width is >= 768px. 

The landing page should have the images 'app-store-badge.png' and 'google-play-badge.png' next to each other. 

The landing page should have the images 'map.jpg' and 'menu.jpg' be on their own line when browser width is < 768px.

The landing page should have the images 'menu.jpg' and 'delivery.jpg' be on their own line when browser width is < 768px.

The landing page should have the images 'user-1.jpg', 'user-2.jpg' be next to each other when browser width is >= 768px. 

The landing page should have the images 'user-3.jpg', 'user-4.jpg' be next to each other when browser width is >= 768px. 

The landing page should have the images 'user-1.jpg' and 'user-4.jpg' be on separate lines when browser width is < 991px.

The landing page should have the images 'user-1.jpg' and 'user-2.jpg' be on their own line when browser width is < 768px.

The landing page should have the images 'user-3.jpg' and 'user-4.jpg' be on their own line when browser width is < 768px.

The landing page should have the images 'user-1.jpg' and 'user-4.jpg' be on their own line when browser width is < 768px.

The landing page has a secondary heading 'About Foodhub' next to 'Foodhub helps you find and order food' paragraph when browser width is >= 768px. 

The landing page has a secondary heading 'About Foodhub' 'Foodhub helps you find and order food' paragraph are on separate lines when browser width is < 768px.

</details>