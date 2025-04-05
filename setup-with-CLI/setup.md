✅ Setup Tailwind CSS v4 Using CLI

```
🛠️ Requirements:

✅ Node.js and npm must be installed

✅ Tailwind CSS must be installed via CLI

✅ You need an input CSS file

✅ Run build command to generate output

✅ Create an HTML file to test

✅ Install Tailwind CSS IntelliSense extension (for auto-suggestions in VS Code)


```

🚀 Step 01: Open the Tailwind CLI Installation Page
Go to your browser and open this link:

```
🔗 https://tailwindcss.com/docs/installation/tailwind-cli
```

🚀 Step 02: Click "Docs > Get Started" and Select "Tailwind CLI"
Go to Docs > Get Started

Click on Tailwind CLI

```
🔗 Tailwind CLI Documentation

```

🧱 Setup Step 1: Install Tailwind CSS via npm
Open your terminal and run the following command:

```
npm install tailwindcss @tailwindcss/cli

```

🧱 Setup Step 2: Create Input CSS File
Create a folder named src

Inside src, create a file called input.css

Add the following line inside input.css:

```
@import "tailwindcss";

```

🧱 Setup Step 3: Build the CSS with Tailwind CLI
Run the following command to generate the output.css file and watch for changes:

```
npx @tailwindcss/cli -i ./src/input.css -o ./src/output.css --watch

```

🧱 Setup Step 4: Create an HTML File
Create an index.html file and link the generated CSS:

```
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Tailwind CLI Example</title>
    <link href="./src/output.css" rel="stylesheet" />
  </head>
  <body class="flex items-center justify-center min-h-screen bg-gray-100">
    <div class="text-center">
      <h1 class="text-4xl font-bold text-blue-600 underline mb-4">
        Hello, Tailwind CSS 4!
      </h1>
      <p class="text-lg text-gray-700">
        Tailwind is now running via CLI build.
      </p>
    </div>
  </body>
</html>

```
