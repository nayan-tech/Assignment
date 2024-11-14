
# Assignment

* Ruby version - 3.3.0
* Rails - 7.1.3
* System Dependencies - Nodejs(16+) , sqlite , yarn , bundler , git
* any desk , ssh

  
Assignment Overview --
1. Set up ssh via any-desk
2. To run a rails app locally - command > rails s
3. A docker file is included with the repo , if you need to change accordingly you can do that
4. Your task is to dockerize the application and then  deploy the  Ruby on Rails application and provide a  URL to access the app.
4. Provide us an url on which we can see the application is running (Url should be working properly)


References -
1. You can install Ruby using a version manager like rbenv or RVM.
   rbenv install 3.3.0
  refer - https://www.digitalocean.com/community/tutorials/how-to-install-ruby-on-rails-with-rbenv-on-ubuntu-20-04

2. Ensure the correct version of Rails is installed globally or within your project’s Gemfile.
   gem install rails -v 7.1.3
   refer - https://www.digitalocean.com/community/tutorials/how-to-install-ruby-on-rails-with-rbenv-on-ubuntu-20-04
   
4. Node.js - Installation (via Node Version Manager):
   Version: Install the latest stable version (16+).
   refer - https://www.digitalocean.com/community/tutorials/how-to-install-node-js-on-ubuntu-20-04
   nvm install 16
   nvm use 16
6. Bundler
  gem install bundler

Running the app locally - Once all the above dependencies are installed, you can follow these steps to run the app: refer - https://www.digitalocean.com/community/tutorials/how-to-build-a-ruby-on-rails-application-on-ubuntu-22-04
1. Clone the repository:  git clone <repo-url>
2. Install Ruby dependencies:   bundle install
3. Install JavaScript dependencies: yarn install
4. Run the Rails server: rails s
5. Access the application:  Open http://localhost:3000 in your browser to see the running Rails app.



