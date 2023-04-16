---
description: >-
  This part of the documentation will show you how you can install and configure
  TailAdmin templates. Both Tailwind + AlpineJS and Tailwind + React.
---

# 🚀 Installation

### TailAdmin HTML - Tailwind + Alpine.js

To use the TailAdmin dashboard template first you’ll have to install it.

Follow these steps to install [TailAdmin Tailwind + AlpineJS](https://tailadmin.com/download) template:

**Note:** You’ll have to have Node.js installed on your machine. Otherwise, these commands won’t work.

1. Download the dashboard template from TailAdmin, and extract it.
2. Then navigate to the project folder and run this command:

```bash
npm install
```

1. After that run this command to start the local server.

```bash
npm run start
```

Now you can make the changes.

After you’ve made the changes, run this command to generate the **build** folder, you can upload this build folder to the server.

```bash
npm run build
```



### TailAdmin React - Tailwind + React.js

In this part, we are going to show you how to install the TailAdmin Tailwind + ReactJS template.

Follow these steps to install the templates.

**Note:** We’ve used **Vite** to develop the Tailwind + ReactJS template.

1. Download the dashboard template from TailAdmin.
2. Then navigate to the project folder and run this command:

```bash
npm install
```

1. After that run this command to start the local server.

```bash
npm run dev
```

When the dev command runs successfully the Dashboard will be open on port:[http://localhost:5173/](http://localhost:5173/)

Now you can customize the dashboard and see the changes locally.

After that, run this command to generate the **build** folder. You can upload this build folder to your server, and the dashboard will be live.

<mark style="color:red;">`npm run build`</mark>

