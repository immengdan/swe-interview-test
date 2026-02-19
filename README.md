# SWE INTERVIEW TEST 
THIS IS TO TEST YOUR SKILLS TO MEET OUR APP DEVELOPMENT REQUIREMENTS

1. Clone this repo to your local machine.
2. Read `Assignment Requirements` carefully and follow it.
4. Please commit your entire code to `your own Github repository` 
5. On your repo, please add step-by-step instructions on how to launch (for both the Backend and Frontend) to the `README.md`
6. Share your repo link with us via email.

HAPPY CODING! </br>
A Round Entertainment

## Starting the servers (backend and frontend)

Follow these steps to run the project locally.

Backend

- Open a terminal and change to the backend folder:

	```bash
	cd StarterCode/backend
	```

- Install dependencies (only required once):

	```bash
	npm install
	```

- Start the backend server:

	```bash
	node index.js
	```

	The backend listens on port `5001` by default.

Frontend

- Open a separate terminal and change to the frontend folder:

	```bash
	cd StarterCode/frontend
	```

- Install dependencies (only required once):

	```bash
	npm install
	```

- Start the frontend dev server:

	```bash
	npm run start
	```

Notes

- If the frontend runs on `http://localhost:3000` and the backend on `http://localhost:5001`, CORS is already configured in the backend to allow requests from the frontend.
- If a port is already in use (EADDRINUSE), either stop the occupying process or start the server on a different port (see above).
