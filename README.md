# DOC1-CourseAssignment - Goals tracking App


## Frontend:
React application.
## Backend:
Node JS application build with Node and Express.
Takes requests that allow users to set, see and delete goals.
## Database:

DB:

❯ docker run --name mongodb -d --rm -p 27017:27017 mongo

BE:

❯ docker build -t goals-node .

❯ docker run --name goals-backend --rm -d -p 80:80 goals-node


FE:

❯ docker build -t goals-react .

docker run --name goals-frontend --rm -p 3000:3000 -it goals-react