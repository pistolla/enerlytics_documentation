# User Authentication and session management



Session
When a user is authenticated the app saves the authentication token and uses it to fetch subsequent api requests. That setup allows the app to only fetch data related to logged in user. This is what we refer as a session. 
The session initially fetches the user profile. The data is cached and stored intermittently as long as the user is logged in. 
The session also fetches user eWallet detail and displays on home page. The session also keep track of user meters and data related to past meter reading.
The session does not cache the e-wallet and meter data. Each time user needs to view the current state of the wallet and meter payment a request is sent to the server.
This ensure even if user is logged on a different app they are able to view same data. The app maintains a session using authenticated api requests.
The app does not connect or manage state with the meters. 
Pros


Cons 
