---
sidebar_position: 1
---

# Quick-Start-Guide

In this guide you will learn how to create new pages.
This should take no more then **5 minutes!**.

## Creating a new site

Get started by **creating a new site**.

### What you'll need

- [Node.js](https://nodejs.org/en/download) version 18.0 or above:
    - When installing Node.js, you are recommended to check all checkboxes related to dependencies.

- [git](https://www.git-scm.com/download) version 
2.45.2 or above.

### Getting started with this project

- Clone this [repository](https://github.com/gottschalktobias1998/RedPandaDocs.io) onto your workstation.

```bash
git clone https://github.com/gottschalktobias1998/RedPandaDocs.io
```

- Navigate into the directory.

```bash
cd RedPandaDocs.io
```

- After navigating into the folder, install all dependencies using:

```bash
npm install
```

### Start your site

Run the development server:

```bash
npm run start
or
npm start
```

The `run` command will start one of the defined scripts located in the `package.json`

`start` is a special word, as it does not require to write `run` before it.

It will build this website locally and serves it thought a development server, ready for you to view at `http://localhost:3000`.

While the server is running, any changes will **reload automatically** in the browser!