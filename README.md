# Loading Skeleton Templates
---
This repository contains a collection of loading skeleton templates designed to mimic the loading states of various popular web applications. These templates are built using HTML and Tailwind CSS to provide a visually appealing and responsive loading experience.

## Overview
---
Loading skeletons are placeholders that simulate the content layout of a webpage while the actual content is loading. They improve the user experience by giving users a preview of the content structure and layout.

## Installation
---
To use these loading skeletons, you need to include Tailwind CSS in your project. You can either use the Tailwind CSS CDN or install it via npm.

### Using CDN
---
Simply include the following link in the `<head>` of your HTML document:

```html
<link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css" rel="stylesheet">
```

### Using npm
---
Install Tailwind CSS via npm:

```bash
npm install tailwindcss
```

Then, include it in your project according to the Tailwind CSS documentation.

## Usage
---
To use a loading template, copy the corresponding HTML code from the templates section into your HTML file. Ensure that you include the Tailwind CSS link or import in your project.

## Templates
---
### Facebook Profile Page

```html
<!-- Add the HTML code for the Facebook Profile Page loading skeleton here -->
```

### YouTube Home Page

```html
<!-- Add the HTML code for the YouTube Home Page loading skeleton here -->
```

### Google Style

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Google Style Loading Skeleton</title>
    <!-- Tailwind CSS CDN -->
    <link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css" rel="stylesheet">
</head>
<body class="bg-gray-100 flex flex-col min-h-screen">
    <!-- Navigation Bar -->
    <div class="animate-pulse bg-white shadow-md p-4">
        <div class="flex items-center space-x-4">
            <div class="bg-gray-300 h-8 w-32 rounded"></div>
            <div class="bg-gray-300 h-8 w-24 rounded"></div>
            <div class="flex-1"></div>
            <div class="bg-gray-300 h-8 w-16 rounded"></div>
        </div>
    </div>

    <!-- Main Content -->
    <main class="flex-1 p-6">
        <!-- Section 1 -->
        <div class="animate-pulse mb-6">
            <div class="bg-gray-300 h-6 rounded w-1/3 mb-4"></div>
            <div class="grid grid-cols-1 sm:grid-cols-2 md:grid-cols-3 gap-4">
                <!-- Card 1 -->
                <div class="bg-gray-300 h-40 rounded-lg"></div>
                <!-- Card 2 -->
                <div class="bg-gray-300 h-40 rounded-lg"></div>
                <!-- Card 3 -->
                <div class="bg-gray-300 h-40 rounded-lg"></div>
            </div>
        </div>

        <!-- Section 2 -->
        <div class="animate-pulse">
            <div class="bg-gray-300 h-6 rounded w-1/4 mb-4"></div>
            <div class="space-y-4">
                <!-- List Item 1 -->
                <div class="bg-gray-300 h-16 rounded-lg p-4 flex items-center space-x-4">
                    <div class="bg-gray-400 h-12 w-12 rounded-full"></div>
                    <div class="flex-1 space-y-2">
                        <div class="bg-gray-400 h-4 rounded w-3/4"></div>
                        <div class="bg-gray-400 h-3 rounded w-1/2"></div>
                    </div>
                </div>
                <!-- List Item 2 -->
                <div class="bg-gray-300 h-16 rounded-lg p-4 flex items-center space-x-4">
                    <div class="bg-gray-400 h-12 w-12 rounded-full"></div>
                    <div class="flex-1 space-y-2">
                        <div class="bg-gray-400 h-4 rounded w-3/4"></div>
                        <div class="bg-gray-400 h-3 rounded w-1/2"></div>
                    </div>
                </div>
                <!-- List Item 3 -->
                <div class="bg-gray-300 h-16 rounded-lg p-4 flex items-center space-x-4">
                    <div class="bg-gray-400 h-12 w-12 rounded-full"></div>
                    <div class="flex-1 space-y-2">
                        <div class="bg-gray-400 h-4 rounded w-3/4"></div>
                        <div class="bg-gray-400 h-3 rounded w-1/2"></div>
                    </div>
                </div>
            </div>
        </div>
    </main>

    <!-- Footer -->
    <footer class="animate-pulse mt-6">
        <div class="bg-gray-300 h-8 rounded w-1/3 mb-2"></div>
        <div class="bg-gray-300 h-6 rounded w-1/4"></div>
    </footer>
</body>
</html>
```

### More Templates

Additional templates can be found in the repository. Feel free to explore and customize them according to your needs.

## Contributing

Contributions are welcome! If you have suggestions or improvements, please open an issue or submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](https://github.com/mdriyadkhan585/Skeleton_templates/blob/main/LICENSE) file for details.
