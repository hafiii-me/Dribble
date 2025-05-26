# Project Responsive Web Design using Bootstrap
## Date: 26-05-2025
# NAME : MOHAMED HAFEEZ S
# REG NO : 212224040193
## AIM:
To create a simplified clone of Dribbble (https://dribbble.com/) landing page.
## DESIGN STEPS:

### Step 1:
Clone the repository from GitHub.

### Step 2:
Create Django Admin project.

### Step 3:
Create a New App under the Django Admin project.

### Step 4:
Insert the necessary CSS and JavaScript files as external in order to use Bootstrap.

### Step 5:
Create a HTML file and include the needed Bootstrap components.

### Step 6:
Publish the website in the LocalHost.

## PROGRAM :
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Dribbble Mini Clone</title>
  <script src="https://cdn.tailwindcss.com"></script>
</head>
<body class="font-sans bg-white text-gray-800">

  <!-- Header -->
  <header class="flex justify-between items-center p-4 shadow">
    <h1 class="text-pink-600 font-bold text-xl">dribbble</h1>
    <nav class="space-x-4 hidden md:flex">
      <a href="#" class="hover:text-pink-600">Inspiration</a>
      <a href="#" class="hover:text-pink-600">Find Work</a>
      <a href="#" class="hover:text-pink-600">Learn</a>
    </nav>
    <div class="space-x-2">
      <button class="text-sm">Login</button>
      <button class="bg-pink-600 text-white px-3 py-1 rounded text-sm">Sign up</button>
    </div>
  </header>

  <!-- Hero -->
  <section class="text-center py-16 px-4 bg-gray-50">
    <h2 class="text-3xl font-bold mb-2">Explore creative work</h2>
    <p class="text-gray-600 mb-4">Join the world's leading design community.</p>
    <button class="bg-pink-600 text-white px-6 py-2 rounded-full">Get Started</button>
  </section>

  <!-- Gallery -->
  <section class="p-6 grid grid-cols-2 md:grid-cols-4 gap-4">
    <div class="bg-gray-200 h-32 rounded"></div>
    <div class="bg-gray-200 h-32 rounded"></div>
    <div class="bg-gray-200 h-32 rounded"></div>
    <div class="bg-gray-200 h-32 rounded"></div>
  </section>

</body>
</html>


## OUTPUT:
![Screenshot 2025-05-26 195423](https://github.com/user-attachments/assets/6524a0c0-5236-42c8-8b88-efb97c1eddc1)
## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
