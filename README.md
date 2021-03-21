

## Getting started

git clone https://github.com/fapugliese/project7.git

### Frontend :


cd frontend
npm install 
npm run serve


### Backend :


cd backend
npm install
npm start


### Database :

You can start MySQL with XAMPP


cd backend


You'll need to verify that the username and password in the config database.json file, match your local MySQL credentials.

```
npx sequelize-cli db:create
npx sequelize-cli db:migrate
```

Then open on any web browser : http://localhost:8080/





