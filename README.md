## Usage:
Simply download and copy Cafeteria to your server location and run `npm install`.
Edit the 'config.json' file if you want to change ports, etc.
Add your applications to the `app` folder.
Start the server using the `node .` command, sit back and relax.

## Supported Applications
Right now, Cafeteria supports the following application types:

### HTML
Just a plain simple HTML app consisting of folders with HTML files and resources.

### Express
Express apps that are enabled to run as Node.js modules. Just copy the application directory over to your `app` folder

### Express Router
You can also use an Express router as your application. Just create a file called `index.router.js` in your application directory and create your router as you would with Express. Simple like that.
