# Image-search-engine


# Unsplash Image Search

This is a simple image search app that uses the Unsplash API. It allows users to search for images and display the results in a grid. The app is built using HTML, CSS, and JavaScript.

## How to use

To use the app, simply type a search term into the search box and click the "Search" button. The app will then display the results of your search in a grid. You can click on an image to view it in a larger size.

## Code

The code for the app is located in the `index.js` file. The following is a step-by-step explanation of the code:

1. The first step is to import the necessary modules. The `useState` hook is used to track the state of the search term and the search results. The `useEffect` hook is used to fetch the search results from the Unsplash API.
2. The `searchImages` function is used to fetch the search results from the Unsplash API. The function takes the search term as an argument and returns a promise that resolves with the search results.
3. The `showMoreBtn` function is used to show the "Show More" button when the user reaches the bottom of the search results.
4. The `searchForm` event listener is used to handle the submit event of the search form. The event listener calls the `searchImages` function and updates the state of the search term and the search results.
5. The `showMoreBtn` event listener is used to handle the click event of the "Show More" button. The event listener calls the `searchImages` function and increments the page number.

## Conclusion

This is a simple image search app that demonstrates how to use the Unsplash API. The app is easy to use and can be used to find images for a variety of purposes.

