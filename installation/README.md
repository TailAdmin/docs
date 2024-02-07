---
description: >-
  This part of the documentation will show you how you can install and configure
  TailAdmin templates. Both Tailwind + AlpineJS and Tailwind + React.
---

# 🚀 Installation

### TailAdmin HTML: Tailwind + Alpine.js

To use the TailAdmin dashboard template, you'll first have to install it.

Follow these steps to install the [TailAdmin Tailwind + AlpineJS](https://tailadmin.com/download) template:

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



### TailAdmin React: Tailwind + React.js

In this part, we are going to show you how to install the TailAdmin React template.

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



### TailAdmin Next.js: Tailwind + Next.js

In this part, we are going to show you how to install the TailAdmin Next.js template.

Follow these steps to install the templates.

Here are the steps you need to follow to install the dependencies.

1. Download and extract the template from Next.js Templates.
2. After that **cd** into the template directory then run this command to install all the dependencies

```
npm install
```

or

```
yarn install
```

3. Now run this command to start the developement server

```
npm run dev
```

or

```
yarn dev
```



### TailAdmin Vue: Tailwind + Vue.js <a href="#vue" id="vue"></a>

In this section, we'll guide you through the installation process of the TailAdmin Vue template.

Follow these steps to install the template:

**Note:** We've utilized **Vite** as build tool for TailAdmin Vue.

1. Download and extract the TailAdmin zip package
2. Navigate to the project folder and execute the following command:

```sh
npm install
```

3. After that, run this command to start the local server:

```sh
npm run dev
```

Upon successful execution of the `dev` command, the TailAdmin will open on port: [http://localhost:5173/](http://localhost:5173/).

Now, you can customize the dashboard and observe the changes locally.

Once customization is complete, run the following command to generate the build folder. You can then upload this **build** folder to your server, and the dashboard will be live.

```sh
npm run build
```
