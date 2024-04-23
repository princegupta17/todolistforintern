# Instruction

Step wise instruction to run this project in your local environment.

## Step 1: - Clone the project

Open Git bash in your local machine and cd to working directory in which you want to clone this project. Now copy and paste following come in Git bash.

```bash
git clone https://github.com/princegupta17/todolistforintern.git
```

## Step 2: -Installation

Install npm package in todolistforintern folder.

```bash
npm i
```

## Step 3: - Run the project

After successful installation of npm package run the website.

```bash
npm run dev
```

Now click on the link.

# Consideration

### 1. Vite: -

Vite pre-bundles dependencies using esbuild, providing a significantly faster spin-up of the development server compared to JavaScript-based alternatives like Create React App.

### 2. Tailwind Css: -

Tailwind CSS provides a set of pre-designed utility classes, which reduces the need for writing custom CSS, leading to smaller file sizes and improved loading times, ultimately enhancing the performance of ReactJS applications.

### 3. Context API: -

Context API allows for the sharing of state across multiple components without the need to pass props manually at every level of the component tree. This simplifies data management and reduces prop-drilling, leading to cleaner and more maintainable code.

### 4. Local Storage: -

Local storage allows you to store data on the client's browser, providing a way to persist user preferences, settings, or other data without the need for a backend server. This can enhance user experience by maintaining state across sessions and reducing the need for repeated data fetching from a server.

### 5. index.js: -

I have created an index.js file in the context and components folders, as it is considered good practice to export all components from the index.js file.
