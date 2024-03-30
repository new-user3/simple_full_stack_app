Simple Full Stack App
This is a simple full stack application with a C backend and a minimalistic HTML/JavaScript frontend.

Directory Structure
css
Copy code
simple_full_stack_app/
│
├── backend/
│   ├── main.c
│   ├── Makefile
│   └── responses.txt
│
└── frontend/
    └── index.html
Backend
The backend is written in C and listens for HTTP requests on port 8080. It responds to requests by reading the contents of responses.txt and sending it back as the response.

Compilation
To compile the backend, navigate to simple_full_stack_app/backend/ and run:

go
Copy code
make
Running the Backend
After compiling, start the backend by running:

bash
Copy code
./backend
Frontend
The frontend is a simple HTML file (index.html) that contains a button. When clicked, it triggers a JavaScript function to send a GET request to the backend and displays the response.

Running the Frontend
Open simple_full_stack_app/frontend/index.html in a web browser to interact with the frontend.

Usage
Compile and run the backend as described above.
Open frontend/index.html in a web browser.
Click the "Send Request" button to trigger a request to the backend.
The response from the backend will be displayed on the webpage.
License
This project is licensed under the MIT License - see the LICENSE file for details.