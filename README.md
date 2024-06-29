# Setup a TypeScript + Node.js Project

_Step-by-Step Guide:_

1. _Install TypeScript and Node.js:_

   - Begin by installing TypeScript globally and Node.js on your machine.
     ```bash
     npm install -g typescript
     ```

2. _Initialize TypeScript Configuration:_

   - In your project directory, run the following command to create a tsconfig.json file.
     ```bash
     tsc --init
     ```

3. _Configure tsconfig.json:_

   - Open tsconfig.json and customize settings such as target, module, and outDir according to your project requirements.

4. _Create Project Structure:_

   - Organize your project by creating directories like src and dist. Place your TypeScript files in src.

5. _Write TypeScript Code:_

   - Create a sample TypeScript file (e.g., index.ts) in the src directory and start writing your TypeScript code.

6. _Compile TypeScript to JavaScript:_

   - Compile your TypeScript code to JavaScript using the following command:
     ```bash
     tsc
     ```

7. _Run Your Node.js Application:_

   - Execute your Node.js application with the following command:
     ```bash
     node dist/index.js
     ```

8. _Test Your Setup:_

   - Ensure everything is working as expected by testing your TypeScript + Node.js setup with sample code.

9. _Enhance Your Workflow (Optional):_
   - Explore additional tools like Nodemon for automatic reloading during development.
