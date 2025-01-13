# Go CRUD TODO - TypeScript, React Query, MongoDB, ChakraUI

### Some Features:

- Stack: Go, React, TypeScript, MongoDB, TanStack Query, ChakraUI
- Create, Read, Update, and Delete (CRUD) functionality for todos
- Toggleable Light and Dark mode
- Responsive design for various screen sizes
- Deployment
- Real-time data fetching, caching, and updates with TanStack 

### .env file

```shell
MONGO_URI=<your_mongo_uri>
PORT=5000
ENV=development
```

### Compile and run

```shell
cd client
npm install
# for development build
npm run dev

#for production build
npm run build

# to run the main file
cd ..
go run main.go
```

### Notes to devs
- fully functional provision for production build, uses the /client/dist for optimised build.
- just change ``` ENV=production ``` in the .env you create.