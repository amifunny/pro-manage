
# Pro-Manage

This is a Kanban Board application for managing projects, events and product development cycle.

Kanban boards visually depict work at various stages of a process using cards to represent work items and columns to represent each stage of the process. Cards are moved from left to right to show progress and to help coordinate teams performing the work.

This app allow to Pick icon for board, Select favorites, Edit titles and description, Add task titles and description, Drag tasks to different section as work progresses.

**Checkout live website in the description! It may take some time to load because of shared instances.**

## Tech Stack - MERN

-   MongoDB
-   Mongoose
-   Express
    -   morgan
-   React
	-  React Redux
	- Material UI
	- CKEditor
-   Node
-   Axios
-   JWT

## Run locally


### Clone or Download
```
$ git clone https://github.com/amazingandyyy/mern.git
$ npm i
$ cd backend
$ npm i
```
### Launching 

You can run frontend and backend separately by entering respective folders and running following command
```
$ npm start
```

Edit `backend/.env` file according to your liking.

Run and deploy application after building frontend static files

```
$ npm run build
```

If build succeeds, you can run both frontend and backend together using -

```
$ node backend/bin/www
```

