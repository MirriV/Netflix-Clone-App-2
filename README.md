# Netflix-Clone-App-2

NETLFIX CLONE APP

The Netflix Clone App is designed to display a list of movies that that the user has chosen to be part of their watchlist. The App will also display to the user a list of upcoming movies.  

The Watchlist will remain in place if the user closes the app and reopens it at later stage. This app was built with the use of HTML, CSS, Javascript and Vue.

Users can easily access the app by logging into the app via the sign in page.

Once the users have logged in, they will be able to search for their desired movies, and then choose items to add to their watchlist.

The movies added to the watch list will remain in place even once the user has closed the page or logged out. 

This app is the final project of my Front End Frameworks course being done through Codespace Academy. 


 <!--movie LIST STARTS-->
        <script>
          const moviesAvailable = new Vue({
            el: '#moviesAvailable',
            data: {
             movies: [
                { title: 'Made of Honor', type: 'movie' },
                { title: 'Pitch Perfect', type: 'series' },
                { title: 'Pitch Perfect 2', type: 'movie' },
                { title: 'Brooklyn 99', type:'series' },
                { title: 'Selling Sunset', type:'series'},
                { title: 'Miss Congeniality' , type: 'movie'},
                { title: 'Hot Rod' , type: 'movie'},
                { title: 'Just Go With It' , type: 'movie'},
                { title: 'What Happens in Vegas' , type: 'movie'},
                { title: 'Love, Rosie' , type: 'movie'},
                { title: 'The Proposal' , type: 'movie'},
                { title: 'New Girl',type:'series'},

             ]
            }
          }).mount("movies");

          document.getElementById("output").innerHTML =
            moviesAvailable.$data.movies;

 <!--movie LIST STARTS-->            

const moviesAvailable = new Vue({
            el: '#moviesAvailable',
            data: {
              movie: {
                      name:'Made of Honor',
                      name: 'Pitch Perfect',
                      name: 'Pitch Perfect 2',
                      name: 'Miss Congeniality',
                      name: 'Hot Rod',
                      name: 'Just Go With It',
                      name: 'What Happens in Vegas',
                      name: 'Love, Rosie',
                      name: 'The Proposal',
                    },
              series:{
                      name:'Brooklyn 99',
                      name:'Selling Sunset',
                      name: 'New Girl',
            }
          }).mount("movies");
       
        </script>
        <!--MOVIE LIST ENDS-->