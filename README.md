<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Fearrrx Landing Page</title>
  <style>
    /* Colors from your theme */
    :root {
      --color-bg-darkest: #16181b;
      --color-bg-darker: #1b1d21;
      --color-bg-dark: #202124;
      --color-bg-mid: #272a30;
      --color-text-light: #d1d5db;
      --color-text-mid: #42454c;
      --color-text-muted: #535863;
    }

    /* Reset & base */
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }
    body {
      background-color: var(--color-bg-darkest);
      color: var(--color-text-light);
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      display: flex;
      justify-content: center;
      align-items: center;
      min-height: 100vh;
      padding: 20px;
    }

    .container {
      background-color: var(--color-bg-darker);
      padding: 40px;
      border-radius: 12px;
      box-shadow: 0 4px 12px rgba(0,0,0,0.6);
      max-width: 600px;
      text-align: center;
    }

    h1 {
      color: var(--color-text-light);
      margin-bottom: 16px;
      font-size: 2.8rem;
    }

    p {
      color: var(--color-text-muted);
      font-size: 1.2rem;
      margin-bottom: 32px;
      line-height: 1.5;
    }

    .btn {
      background-color: var(--color-bg-mid);
      color: var(--color-text-light);
      padding: 14px 36px;
      font-size: 1.1rem;
      border: none;
      border-radius: 8px;
      cursor: pointer;
      transition: background-color 0.3s ease;
      text-decoration: none;
      display: inline-block;
    }

    .btn:hover {
      background-color: var(--color-bg-dark);
    }
  </style>
</head>
<body>
  <div class="container">
    <h1>Welcome to Fearrrx's Space</h1>
    <p>This is a sleek dark-themed landing page built with your chosen palette. Explore, create, and code the future.</p>
    <a href="https://github.com/fearrrx" class="btn" target="_blank" rel="noopener noreferrer">Visit My GitHub</a>
  </div>
</body>
</html>
