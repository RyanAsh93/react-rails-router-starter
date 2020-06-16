## instructions

## Clone 

1. `git clone https://github.com/jimibue/react-rails-router-starter.git`
`give it different projectname`
2. `git remote rm origin`
3. create a new repo and add new origin
4. `git add remote origin <url>`

### Rails setup

2. `cd into project name`
3. run `bundle`
4. `in config/database yml replace database name to something else in
  the case that would be react-rails-router
5. rails db:create db:migrate and db:seed "if you have a seed file"
6. rails s -p 3001
7. check this route `http://localhost:3001/api/products` should see products

### React

1. `cd into project name and then cd into client`
2. run `yarn`
3. run `yarn start`
4. open `http://localhost:3000` "make sure rails is running on port 3001"
