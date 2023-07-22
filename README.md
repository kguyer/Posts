# Posts Project
This app lets you create, edit, or delete posts and make comments if you are signed in. I used the devise gem to add the sign in function. If you are not signed in you can see the posts and make comments. The edit and delete links will be hidden unless you sign in.

### Ruby Version
This uses version 3.2.2. 
Use `ruby -v` to see your system version

### Rails version
This uses version 7.0.5.
Use `rails -v` to see your system version

### Setup
1. Clone the repo `git clone https://github.com/kguyer/Posts`

2. Setup the database `bin/rails db:setup`

3. Start the server `rails server`

4. Visit `localhost:3000` to view the app in your browser