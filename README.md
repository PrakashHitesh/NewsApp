# NewsApp

A React-based web application that displays the latest news articles fetched from the NewsAPI. The application features various categories like Politics, Crime, Education, and Entertainment, and includes a search functionality with infinite scrolling to load more articles.

## Features

  * News Categories: Users can browse news articles by categories like Politics, Crime, Science,Sports, and more.
  * Search Functionality: Search for specific news articles using keywords.
  * Infinite Scroll: Load more articles as the user scrolls down the page.
  * Multilingual Support: Switch between English and Hindi.
  * Responsive Design: Works well on mobile, tablet, and desktop devices.
## Screenshots
![image](https://github.com/user-attachments/assets/78877e0c-624c-4770-bc7e-e76f9377b1e1)

## Prerequisites

Before you start, ensure you have the following installed:

  + Node.js (v14+)
  + npm or yarn

## Installation

  ### Clone the repository:

      git clone https://github.com/your-username/newsapp.git
      cd newsapp

 ### Install dependencies:

      npm install

 ### Create a .env file in the root of your project and add your NewsAPI key:


      REACT_APP_NEWS_API_KEY=your_newsapi_key

### Start the development server:

npm start

The application will open at http://localhost:3000.


## File Structure


![image](https://github.com/user-attachments/assets/ef7192cb-6142-4d7b-8609-d337b9f50964)

## Usage
### Changing News Categories

    To add or remove news categories, you can modify the Navbar.js component and update the corresponding links.
    
### Search Functionality

    The Navbar.js component includes a search form that triggers a search request to fetch articles based on the user's input.
### Infinite Scroll

    The Home.js component uses the react-infinite-scroll-component library to load more articles as you scroll down the page. You can adjust the number of articles loaded per request in the API call (pageSize parameter).
    
### Available Scripts

    In the project directory, you can run:
    
  **npm start**
    
      Runs the app in development mode. Open http://localhost:3000 to view it in the browser.
      
  **npm run build**

    Builds the app for production to the build folder. It bundles React in production mode and optimizes the build for the best performance.

## API

This project uses the NewsAPI to fetch news articles. You must have an API key to use this service. Get your key here.

Replace your_newsapi_key in your .env file with your actual API key.


REACT_APP_NEWS_API_KEY=your_newsapi_key


## Technologies Used

     React: Frontend framework
     Bootstrap: For responsive design
     NewsAPI: For fetching news articles
     React Infinite Scroll: For loading more articles dynamically

## Contributions

Feel free to open issues or submit pull requests to enhance the functionality or fix bugs.


