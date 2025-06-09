
PearlThoughts Internship Task 1 – Strapi Setup and Content Type Creation

This repository contains the setup for Task 1 of the Pearl Thoughts Internship, where we explore the Strapi open-source headless CMS locally and create a sample content type using its admin panel.

1. Clone the Repository

git clone https://github.com/strapi/strapi.git
cd strapi

2. Install Dependencies

Make sure you have Node.js (≥14.x) and npm installed. Then:

    $$ npm install

or   if you use Yarn:

    $$ yarn install
    $$ yarn build

3. Creating the New Strapi App

    $$ npx create-strapi-app@latest my-strapi-app --quickstart

 if using yarn:
  
     $$yarn develop

  if using npm:
     
      $$npm run develop

The admin panel will be available at:
    
    http://localhost:1337/admin

🧩 Sample Content Type Created

Content Type: Article

Field Name	Type	Description
Title	Text	The title of the post
Body	RichText	Full article content
Published	Boolean	Whether it's live

📹 Loom Video
Watch my walkthrough here:
🎥 Loom Video Link

🔗 Pull Request
Here is the PR for this task:
🔗 Pull Request Link


📝 Notes
Explored the full folder structure of Strapi.

Set up using the --quickstart option.

Understood how content types, collections, and admin
