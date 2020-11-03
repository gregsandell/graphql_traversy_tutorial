
# GraphQL With React & Apollo
This is a video tutorial from Brad Traversy of Traversy Media

## Links
1. [Home Page for the tutorial](https://codetalks.tv/talk/graphql-with-react-and-apollo-[1]-express-graphql-server-semtj8w04z8)


## Part 1: Express GraphQL Server
### Links
1. [YouTube video for part 1](https://www.youtube.com/watch?v=SEMTj8w04Z8)
2. [Github project for server code](https://github.com/bradtraversy/spacex_launch_stats)
3. [SpaceX API Home Page](https://github.com/r-spacex/SpaceX-API)
4. [SpaceX API gitdhub project](https://github.com/r-spacex/SpaceX-API)
5. [SpaceX API Postman Test Page](https://docs.spacexdata.com/):  make sure you are using v.3 and not v.4

At end of the server tutorial, these two queries should work in the GraphiQL:
### Query 1
```javascript
{
  launches {
    flight_number,
    mission_name,
    launch_success,
    launch_date_local,
    rocket {
      rocket_id,
      rocket_name,
      rocket_type
    }
  }
}
```

### Query 2
```javascript
{
  launch(flight_number: 2) {
    mission_name,
    launch_year,
    launch_success,
    rocket {
      rocket_name
    }
  }
}
```
## Part 2: React & Apollo Setup
### Links
1. [Youtube video for part 2](https://www.youtube.com/watch?v=-XwkFm5a9lw)
