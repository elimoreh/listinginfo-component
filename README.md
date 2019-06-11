
# Airbnb Listing Information Module
The goal of this project was to use React to create a clone of the Airbnb infromation module on the home listings page both in styling and fuctionality. A visiual demo of the two comparison be seen lower in this page.

## Requirments 
- MongoDB: `brew install mongodb`

## Getting Started
- Install dependencies with `npm install`
- Run the server with `npm run server`
- Populate the module with randomly generated data with `npm run seed`
- Bundle the React app and run webpack with `npm run app`
- Change listing id by adding `?listingid=(listing # from 0-100)` to the end of the URL for expample `http://localhost:3004/?listingid=29`

## Running the Tests
To run the test built for the module simply use `npm test`

## Built With
  **Front-End**: React  
  **Server**: Node, Express  
  **Database**: MongoDB  
  **Testing**: Jest, Enzyme, Supertest  
  **Styling**: Styled Components  

## AWS link
This component is deployed on an amazon EC2 instance at the following link:  
http://ec2-13-57-31-14.us-west-1.compute.amazonaws.com/?listingid=79  
The component support listing ids from 1-100 so feel free to change the id at the end of the url. 


## Visual Demo
Airbnb on the left and this clone on the right.  

 <img src="https://media.giphy.com/media/gf5h875WqEELIED4SO/giphy.gif" width="800px">  
 
