<img width="1689" alt="Screenshot 2024-03-25 at 12 00 45 AM" src="https://github.com/ianMontesclaros/worldwise/assets/122757362/b987444f-7716-4881-b01c-af6f96b362bf">

# WorldWise

WorldWise is a ReactJS single-page application (SPA) that allows users to pinpoint and save every place they've been to on an interactive map.

https://worldwise-ianmontesclaros.netlify.app/

# Features

1. Dynamic Page Navigation: The application features a navigation system that dynamically updates the URL bar as users navigate through different pages.
   
2. City and Country Lists: Users are presented with a list of visited cities and their respective countries. This information is fetched and displayed based on user input.
  
3. Interactive Map: Through the integration of geolocation API, users can pinpoint their current location on the interactive map. The map displays markers for all the cities users have visited.
  
4. City Details: By clicking on a city marker, users can access detailed information about the city they visited. This includes its name, the date of the visit, personal notes added by the user, and even a  Wikipedia link for further details.

# Built with

* React Router
* context API
* memo
* useMemo
* useCallback
* Performance Optimization

# Quick Setup

Before accessing the netlify link:
1. Clone the repository.
2. Install the dependencies with ``` npm install ```.
3. Run the JSON server with ``` npm run server ```.
