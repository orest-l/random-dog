# Random Dog Image

This code defines a function called `getRandomDogImage()` that fetches a random dog image from the Dog API, sets the `src` attribute of an `img` element with id "dog-image" to the URL of the fetched image, and displays it on the webpage.

The `fetch()` function sends a GET request to the Dog API endpoint `https://dog.ceo/api/breeds/image/random` and returns a promise that resolves to the response object. We then use the `json()` method of the response object to extract the JSON data from the response and return it as a promise. Finally, we set the `src` attribute of the `img` element to the URL of the fetched image, which is contained in the `message` property of the JSON data.
