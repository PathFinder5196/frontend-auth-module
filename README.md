## How to use

1. After cloning this repository either run `yarn` or `npm i` command to install project dependency
   
2. After above step is completed create `.env.local` file in root folder and add `NEXT_PUBLIC_API_URL = "http://localhost:5000/users/"` this statement, this is to access the backend APIs in frontend project
   
3. After this you can start project using `yarn dev` or `npm run dev` for running frontend in development mode

4. To build the project you can use `yarn build` or `npm run build` command which will generate build of entire project which you can use to deploy on services like AWS S3 or any static site hosting platforms