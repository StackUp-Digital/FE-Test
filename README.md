# Front End Developer Assessment

Thank you for taking the time to work through this task. The purpose of this task is to provide a means of assessing your ability to use HTML, CSS, JavaScript, your coding style and how you approach best practices.

## User Requirements

Imagine you are presented with the following user story:

> As a User I want the ability to check the weather forecast for a given location so that I can plan activities for my trip.

We would like you to create a weather widget that could be used as part of a travel website. This widget should:

- Provide users with the ability to search for a location.

- Upon selecting a location, the widget should hide the search results and return a weather forecast for the selected location.

- Be responsive and functional across mobile and desktop based devices.

## Design

A figma document has been put together to demonstrate how we want the widget to look.

- Figma Design: [https://www.figma.com/file/NRd8MVtMLn8X7rTJ06EjWK/Untitled?node-id=0%3A1](https://www.figma.com/file/NRd8MVtMLn8X7rTJ06EjWK/Untitled?node-id=0%3A1)

- Please take a look at this video for a brief overview of the Figma document [https://www.loom.com/share/45259d7fadc04df4853aa7d18d625247](https://www.loom.com/share/45259d7fadc04df4853aa7d18d625247)

## Technical Requirements

The widget must be created with HTML, CSS and JavaScript that can be executed in a browser.

We want you to have the freedom to use frameworks and libraries that you are most comfortable with. So don't feel the need to be restricted to something like React (we use a combination of React and plain old JS at StackUp).

You should also feel free to use SCSS, PostCSS or plain old CSS - we don't mind! As long as your code is structured and well written, we'll be happy!

## MetaWeather API

We would like you to use the MetaWeather API to retrieve locations and weather forecasts. The documentation for this API can be found at [https://www.metaweather.com/api](https://www.metaweather.com/api)

Due to CORS, you are unable to use the MetaWeather API directly from the browser. To simplify things, we have created an API proxy that you can use.

The original vs proxied endpoints are listed below

```
# Search Original Url
https://www.metaweather.com/api/location/search?query=London

# Search Proxied Url (Use this)
https://xenodochial-edison-a2f234.netlify.app/.netlify/functions/search?query=London
```

```
# Location Original Url
https://www.metaweather.com/api/location/44418

# Location Proxied Url (Use this)
https://xenodochial-edison-a2f234.netlify.app/.netlify/functions/get-location?id=44418
```

The returned response for each of the requests are as per the MetaWeather documentation.

### Weather Icons

Please use the MetaWeather weather icons when displaying the weather forecast in the widget.

## How to Submit Your Test

When you are ready to hand your test over, please publish your code up to a GIT repository that we can access. Please include a README with instructions that tell us how to run your code locally.

## Thank You!

Once again, thank you for taking the time to put this together for us. If you encounter any issues using the proxy API or if you have any questions then please let us know.
