# Skeleton_Templates

![Project Logo](Logo.svg)

---
This repository contains a collection of loading skeleton templates designed to mimic the loading states of various popular web applications. These templates are built using HTML and Tailwind CSS to provide a visually appealing and responsive loading experience.

---
## **💪🏿 List & Skeleton Name:**

1. **Facebook Loading Skeleton**
   - Inspired by Facebook's loading placeholders.

2. **GitHub Loading Skeleton**
   - Inspired by GitHub's loading placeholders.

3. **Twitter (X) Loading Skeleton**
   - Inspired by Twitter's loading placeholders.

4. **Instagram Loading Skeleton**
   - Inspired by Instagram's loading placeholders.

5. **Threads Loading Skeleton**
   - Inspired by Threads' loading placeholders.

6. **WhatsApp Loading Skeleton**
   - Inspired by WhatsApp's loading placeholders.

7. **TikTok Loading Skeleton**
   - Inspired by TikTok's loading placeholders.

8. **LinkedIn Loading Skeleton**
   - Inspired by LinkedIn's loading placeholders.

9. **TikTok For You Page Loading Skeleton**
   - Specifically for TikTok's For You Page.

10. **TikTok Profile Page Loading Skeleton**
    - Specifically for TikTok's Profile Page.

11. **TikTok Chats Page Loading Skeleton**
    - Specifically for TikTok's Chats Page.

12. **Messenger Chats List Home Page Loading Skeleton**
    - Inspired by Facebook Messenger's Chats List.

13. **Facebook Profile Page Loading Skeleton**
    - Inspired by Facebook's Profile Page.

14. **Facebook Settings Page Loading Skeleton**
    - Inspired by Facebook's Settings Page.

15. **YouTube Home Page Loading Skeleton**
    - Inspired by YouTube's Home Page.

16. **YouTube Reels Page Loading Skeleton**
    - Inspired by YouTube's Reels Page.

17. **YouTube Subscription Page Loading Skeleton**
    - Inspired by YouTube's Subscription Page.

18. **Telegram Loading Skeleton**
    - Inspired by Telegram's loading placeholders.

19. **Telegram Profile Loading Skeleton**
    - Inspired by Telegram's Profile Page.

20. **Meta Business Sites Loading Skeleton**
    - Inspired by Meta Business sites' loading placeholders.

21. **YouTube Studio (YT Studio) Loading Skeleton**
    - Inspired by YouTube Studio's loading placeholders.

22. **MyGP App Loading Skeleton**
    - Inspired by the MyGP app's loading placeholders.

23. **Google Loading Skeleton**
    - Inspired by Google's clean and minimalistic loading placeholders.

24. **Bonus Beautiful Loading Skeleton**
    - A custom, visually appealing loading skeleton template.

# Live Demo link

- [Bonus.html](https://templates-gamma-two.vercel.app/Bonus.html)
- [Facebook.html](https://templates-gamma-two.vercel.app/Facebook.html)
- [Facebook_Settings_page.html](https://templates-gamma-two.vercel.app/Facebook_Settings_page.html)
- [Facebook_profile.html](https://templates-gamma-two.vercel.app/Facebook_profile.html)
- [GitHub.html](https://templates-gamma-two.vercel.app/GitHub.html)
- [Google.html](https://templates-gamma-two.vercel.app/Google.html)
- [Instagram.html](https://templates-gamma-two.vercel.app/Instagram.html)
- [LinkedIn.html](https://templates-gamma-two.vercel.app/LinkedIn.html)
- [Massagers.html](https://templates-gamma-two.vercel.app/Massagers.html)
- [Meta_Business.html](https://templates-gamma-two.vercel.app/Meta_Business.html)
- [MyGp.html](https://templates-gamma-two.vercel.app/MyGp.html)
- [Telegram.html](https://templates-gamma-two.vercel.app/Telegram.html)
- [Telegram_profile.html](https://templates-gamma-two.vercel.app/Telegram_profile.html)
- [Threads.html](https://templates-gamma-two.vercel.app/Threads.html)
- [TikTok.html](https://templates-gamma-two.vercel.app/TikTok.html)
- [TikTok_chats_page.html](https://templates-gamma-two.vercel.app/TikTok_chats_page.html)
- [TikTok_foryou_page.html](https://templates-gamma-two.vercel.app/TikTok_foryou_page.html)
- [TikTok_profile_page.html](https://templates-gamma-two.vercel.app/TikTok_profile_page.html)
- [Twitter_X.html](https://templates-gamma-two.vercel.app/Twitter_X.html)
- [WhatsApp.html](https://templates-gamma-two.vercel.app/WhatsApp.html)
- [YT_Studio.html](https://templates-gamma-two.vercel.app/YT_Studio.html)
- [YouTube.html](https://templates-gamma-two.vercel.app/YouTube.html)
- [YouTube_Subscription.html](https://templates-gamma-two.vercel.app/YouTube_Subscription.html)
- [YouTube_reel.html](https://templates-gamma-two.vercel.app/YouTube_reel.html)


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
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Facebook Profile Page Loading Skeleton</title>
    <!-- Tailwind CSS CDN -->
    <link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css" rel="stylesheet">
</head>
<body class="bg-gray-100 flex justify-center items-center min-h-screen p-4">
    <div class="w-full max-w-3xl p-4 bg-white rounded-lg shadow-md">
        <!-- Cover Photo -->
        <div class="animate-pulse mb-6">
            <div class="h-48 bg-gray-300 rounded"></div>
        </div>
        
        <!-- Profile Header -->
        <div class="animate-pulse flex items-center mb-6">
            <div class="relative">
                <div class="absolute -bottom-6 left-4 border-4 border-white rounded-full h-24 w-24 bg-gray-300"></div>
                <div class="h-24 w-24 bg-gray-300 rounded-full"></div>
            </div>
            <div class="ml-32 flex-1 space-y-4">
                <div class="h-6 bg-gray-300 rounded w-1/3"></div>
                <div class="h-4 bg-gray-300 rounded w-1/4"></div>
                <div class="h-4 bg-gray-300 rounded w-1/2"></div>
            </div>
        </div>
        
        <!-- About Section -->
        <div class="animate-pulse mb-6">
            <div class="h-4 bg-gray-300 rounded w-1/2 mb-2"></div>
            <div class="h-4 bg-gray-300 rounded w-3/4 mb-2"></div>
            <div class="h-4 bg-gray-300 rounded w-2/3"></div>
        </div>

        <!-- Posts List -->
        <div class="animate-pulse">
            <!-- Post 1 -->
            <div class="mb-6">
                <div class="flex items-center mb-4">
                    <div class="rounded-full bg-gray-300 h-12 w-12"></div>
                    <div class="ml-4 flex-1 space-y-2">
                        <div class="h-4 bg-gray-300 rounded w-1/3"></div>
                        <div class="h-3 bg-gray-300 rounded w-1/4"></div>
                    </div>
                </div>
                <div class="h-4 bg-gray-300 rounded w-5/6 mb-2"></div>
                <div class="h-4 bg-gray-300 rounded w-3/4 mb-2"></div>
                <div class="h-4 bg-gray-300 rounded w-2/3"></div>
            </div>

            <!-- Post 2 -->
            <div class="mb-6">
                <div class="flex items-center mb-4">
                    <div class="rounded-full bg-gray-300 h-12 w-12"></div>
                    <div class="ml-4 flex-1 space-y-2">
                        <div class="h-4 bg-gray-300 rounded w-1/3"></div>
                        <div class="h-3 bg-gray-300 rounded w-1/4"></div>
                    </div>
                </div>
                <div class="h-4 bg-gray-300 rounded w-5/6 mb-2"></div>
                <div class="h-4 bg-gray-300 rounded w-3/4 mb-2"></div>
                <div class="h-4 bg-gray-300 rounded w-2/3"></div>
            </div>
        </div>
    </div>
</body>
</html>
```

### YouTube Home Page

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>YouTube Home Page Loading Skeleton</title>
    <!-- Tailwind CSS CDN -->
    <link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css" rel="stylesheet">
</head>
<body class="bg-gray-100 flex flex-col items-center p-4">
    <div class="w-full max-w-6xl">
        <!-- Video Thumbnails Grid -->
        <div class="animate-pulse">
            <!-- Row 1 -->
            <div class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-4 mb-6">
                <!-- Video Thumbnail 1 -->
                <div class="bg-gray-300 h-40 rounded"></div>
                <!-- Video Thumbnail 2 -->
                <div class="bg-gray-300 h-40 rounded"></div>
                <!-- Video Thumbnail 3 -->
                <div class="bg-gray-300 h-40 rounded"></div>
                <!-- Video Thumbnail 4 -->
                <div class="bg-gray-300 h-40 rounded"></div>
            </div>

            <!-- Row 2 -->
            <div class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-4 mb-6">
                <!-- Video Thumbnail 5 -->
                <div class="bg-gray-300 h-40 rounded"></div>
                <!-- Video Thumbnail 6 -->
                <div class="bg-gray-300 h-40 rounded"></div>
                <!-- Video Thumbnail 7 -->
                <div class="bg-gray-300 h-40 rounded"></div>
                <!-- Video Thumbnail 8 -->
                <div class="bg-gray-300 h-40 rounded"></div>
            </div>
        </div>

        <!-- Video Titles and Channel Names -->
        <div class="animate-pulse">
            <!-- Row 1 Titles -->
            <div class="flex justify-between mb-4">
                <div class="space-y-2">
                    <div class="h-4 bg-gray-300 rounded w-3/4"></div>
                    <div class="h-3 bg-gray-300 rounded w-1/2"></div>
                </div>
                <div class="w-24 h-3 bg-gray-300 rounded"></div>
            </div>
            <!-- Row 2 Titles -->
            <div class="flex justify-between mb-4">
                <div class="space-y-2">
                    <div class="h-4 bg-gray-300 rounded w-3/4"></div>
                    <div class="h-3 bg-gray-300 rounded w-1/2"></div>
                </div>
                <div class="w-24 h-3 bg-gray-300 rounded"></div>
            </div>
            <!-- Row 3 Titles -->
            <div class="flex justify-between mb-4">
                <div class="space-y-2">
                    <div class="h-4 bg-gray-300 rounded w-3/4"></div>
                    <div class="h-3 bg-gray-300 rounded w-1/2"></div>
                </div>
                <div class="w-24 h-3 bg-gray-300 rounded"></div>
            </div>
            <!-- Row 4 Titles -->
            <div class="flex justify-between mb-4">
                <div class="space-y-2">
                    <div class="h-4 bg-gray-300 rounded w-3/4"></div>
                    <div class="h-3 bg-gray-300 rounded w-1/2"></div>
                </div>
                <div class="w-24 h-3 bg-gray-300 rounded"></div>
            </div>
        </div>
    </div>
</body>
</html>
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
