# Lab 6

1. Create angular project with routing support  
2. Create navigation link that nvaigates user to albums list component using routing  
3. Crate albums list comonent that display albums loaded from https://jsonplaceholder.typicode.com/albums Each item in  the list should have link "view photos" (lazy loaded route). When user click view photos link, application navigates to photo gallery component that should load photos of that album.  
4. Add photos gallery component that load photos of particular album from https://jsonplaceholder.typicode.com/photos. This component shoud retrive album information from router url. Component shoukd display photos using img tag, as tiles arranged as a grid.  
5. Add 404 page component with text "Page does not exist". If user by accident navigates to url that does not exist a 404 error page should be displayed.  
