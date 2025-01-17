# Delivery Point  👇 👇

Design and developed websites features such as food listing with quick delivery options within 30 minutes, showcasing top-rated restaurants, and enabling robust search capabilities for food items and restaurants.

## Features

- User-friendly Interface
- Food Listing
- Quick Delivery
- Top Restaurants Display
- Search Functionality
- Cart Management
- Order Placement
- Food Details Page



## Appendix

Technologies Used:

    Frontend: React.js, HTML5, CSS3, JavaScript

    Backend: Node.js, Express.js Database: MongoDB
    APIs: RESTful APIs for backend communication

    Deployment: Heroku for hosting

Development Process:

    Utilized Git for version control, maintaining clear commit history and branches.

    Employed Agile methodologies for project management, including user stories, sprints, and daily stand-ups.

    Conducted regular code reviews and testing to ensure quality and maintainability of the codebase.


Future Enhancements:

    Enable real-time order tracking using web sockets.



## Documentation

[Nodejs](https://nodejs.org/docs/latest/api/)

[Reactjs](https://legacy.reactjs.org/docs/getting-started.html)

[MongoDB](https://www.mongodb.com/docs/atlas/getting-started)

## Installation

Install delivery-point with npm

```bash
  cd client
     npm Install
  cd server
     npm Install
```
    ## Color Reference

| Color             | Hex                                                                |
| ----------------- | ------------------------------------------------------------------ |
| Text  | ![#5B63B7](https://via.placeholder.com/10/0a192f?text=+) #0a192f |
| Cart Color  | ![#FF5733](https://via.placeholder.com/10/0a192f?text=+) #0a192f |

## API Reference

#### Get all Foods

```http
  GET /api/get-all-foods
```

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `api_key` | `string` | **Required**.  api methods |

#### Get food by Id

```http
  GET /api/food/${id}
```

| Parameter | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `id`      | `string` | **Required**. Id of item to fetch |





