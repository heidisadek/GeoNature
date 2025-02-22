# GeoNature

GeoNature is a Geographic Information System (GIS) application developed in C++ for the course ECE297: Software Design and Communication. While the main focus is mapping areas and offering other tools for navigation, it was also designed with the theme of biodiversity in mind. The features and UI were designed using the GTK library along with CSS styling, and the OpenStreetMap API was used for the geographical data.

## Features
### Observing Species
Using the libcurl library, GeoNature uses the iNaturalist API to allow a user to observe species documented in the range of where they click on the map.
![species](https://github.com/user-attachments/assets/cba2844f-ed96-4c91-b1d8-d07074168e1b)

### Direction Finding
GeoNature allows a user to find the shortest path using the A* algorithm from one point to another. The user may choose to type their directions, or simply click on the map to input their desired source and destination. 
![direction-finding](https://github.com/user-attachments/assets/1925f66e-5941-491c-88ef-02d43a5f7481)

### Pin Creation
The user may add their own customizable pins, which they can edit or delete later on. They may also add their own details.
![pin-creation](https://github.com/user-attachments/assets/19a07558-ead0-4c4e-a69f-86aab736363e)
![pin-details](https://github.com/user-attachments/assets/d9ce2df5-d91e-4ff0-927d-9d143a2eb3ca)

### Other Navigation Tools
The user can enter the names of two streets and find the intersections between them.
![intersection-finder](https://github.com/user-attachments/assets/da58bda6-4442-4ede-bbb3-1ece701d5a54)
The user may toggle points of interest to be displayed on the map. 
![points-of-interest](https://github.com/user-attachments/assets/1a453364-1e36-4da7-8717-99a74e8161a9)
Subway toggle allows the user to view the subway routes on the map.
![transportation](https://github.com/user-attachments/assets/48ccabb8-7c63-4f3d-a1f4-6e8224b3f312)
The user can toggle a button and click anywhere on the map to find the closest intersection. 
![closest-intersection](https://github.com/user-attachments/assets/924c558c-3ae3-475c-95d9-6f64ee551063)


Due to course policies, the project is not open-source.
