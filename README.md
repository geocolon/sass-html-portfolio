# sass-html-portfolio

Run npm run sass Again:
Try running the npm run sass command again:

bash
Copy code
npm run sass
This should now use the sass command, and you should see your SCSS files being compiled to CSS in the dist/css/ directory.

By following these steps, you should resolve the "command not found" issue and be able to use the sass command for watching and compiling your SCSS files.

Install http-server:
Run the following command to install http-server globally:

bash
Copy code
npm install -g http-server
Run the Local Server:
Navigate to your project directory and run the following command to start the server:

bash
Copy code
http-server dist
This assumes that your compiled files are in the dist/ directory. Adjust the path accordingly if your files are in a different location.

The server will start, and you'll see output similar to:

arduino
Copy code
Starting up http-server, serving ./dist
Available on:
  http://127.0.0.1:8080
  http://192.168.0.2:8080
Hit CTRL-C to stop the server
Open in Browser:
Open your web browser and navigate to http://127.0.0.1:8080 or http://localhost:8080. You should be able to see your Sass and Responsive Portfolio Website.

Any changes you make to your SCSS files and save should trigger the Sass compiler and, subsequently, the local server to update. Simply refresh your browser to see the changes.

Keep in mind that the specific commands and steps might vary based on your project structure and build setup, so adjust them accordingly. If you have a different method for serving files or if you're using a different setup, please provide more details for more accurate guidance.