# react-redux-pet-management-system

This is the pet management system support by React and Redux for Frontend and Rails for Backend. 

There are three models, Owner, Pet and Clinic. They have relationship each other.

For example, pet belongs to Owner and Clinic. Owner could have many clinics through Pet. Likewise from Clinic.

![javascript_backend](https://user-images.githubusercontent.com/29337166/123549950-763b4380-d76b-11eb-8161-0f51534d7f51.JPG)

## Instruction

### API Backend Preparation

`/pet-api`

Uner pet-api, run the followiing commands.

`bundle install`

Install all the necessary gems for this application. Especially, 'rack-cors' and
'fast_jsonapi' are used for Rails Backend.

`rails db:migrate`

Migrate the database which is described in `db/migrate` folder.

`rails db:seed`

Seed some datas into sqlite3. In this example, I put 2 clinics and 1 owner.

`npm start` under `/react-redux-pet-management-system` folder.

This will run Frontend React-redux app and Rails api app.

## Development Environment

OS: Windows 10 and WSL2 Ubuntu 20.04 Web browser: Chrome 91 

## License

Under the MIT License

## Reference

`https://github.com/Joeycho/sinatra-pet-management-system`

`https://github.com/Joeycho/rails-pet-management-system`

`https://github.com/Joeycho/javascript-pet-management-system`

`https://github.com/learn-co-curriculum/js-rails-as-api-creating-a-rails-api-from-scratch`

`https://github.com/learn-co-students/js-rails-as-api-using-fast-json-api-v-000`

## Feedback

Not yet
