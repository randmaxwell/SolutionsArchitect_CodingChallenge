# Shopify Sections - Klaviyo Add On

Shopify Section with Klaviyo Custom API Built In

## Description

A section you can add to any Shopify2.0 theme that has a pre-built Klaviyo form that submits information through the track API.
The great thing about this section is it can be added after the fact to any page type the store owner wants. They just have to add the section via the Shopify Customizer like seen below:

![Screen Shot 2022-08-17 at 7 43 15 PM](https://user-images.githubusercontent.com/102880120/185262485-e35d5916-30c5-45f1-9953-7851a0331e26.png)

![Screen Shot 2022-08-17 at 7 43 35 PM](https://user-images.githubusercontent.com/102880120/185262521-b365125a-ab45-4802-af0d-cc434ac4401b.png)

This specific section is hard coded with some content, but that content can be changed as needed to fit the scope of any given project/idea.


## Getting Started

### Installing

* Add the custom-klaviyo-section.liquid section to your Shopify theme
* Keep in mind that this section has some styling specific to the theme, so if it's added to a different theme, styling may need to be adjusted.


## How It Works
The way to code works is that it's injected directly into a Shopify Sections Liquid file, so when the form is filled out and the submit button is pressed, it fires a custom function that gathers all of the data from the form, turns that data into variables, and then adds those variables into the Klaviyo track API request.

The most important Klaviyo code can all be seen here:

<img width="1202" alt="Screen Shot 2022-08-17 at 8 20 45 PM" src="https://user-images.githubusercontent.com/102880120/185265820-3d9b1981-9dbb-4438-856d-24f28aab7626.png">


## Authors

Max Rand
mrand1204@gmail.com
