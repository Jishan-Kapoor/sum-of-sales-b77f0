# Sales Summary Web App

## Summary
The Sales Summary Web App is a static single-page site that fetches data from a CSV file, calculates the total sales, and displays the result on the page. The site is titled "Sales Summary 731cade2" and utilizes Bootstrap 5 for styling.

## Setup
To deploy the Sales Summary Web App on GitHub Pages, follow these steps:
1. Create a new repository on GitHub.
2. Upload the necessary HTML, CSS, JavaScript files, and the `data.csv` file.
3. Enable GitHub Pages for the repository and select the main branch as the source.

## Usage
- Access the page by navigating to the GitHub Pages URL for the deployed site.
- There are no query parameters or configuration options needed.
- Key features include:
  - Fetching data from `data.csv`.
  - Calculating the total sales.
  - Displaying the total inside `#total-sales`.
  - Using Bootstrap 5 for styling.

## Code Explanation
The web app is built using HTML, JavaScript, and CSS. Bootstrap 5 is added to the page through a CDN link from jsdelivr. The key libraries used are Bootstrap 5 for styling.
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sales Summary 731cade2</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/css/bootstrap.min.css" rel="stylesheet">
</head>
<body>
    <div id="total-sales"></div>
    <script src="app.js"></script>
</body>
</html>
```

## License
This project is licensed under the MIT License.