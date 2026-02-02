# strapi-task-1
this is for devops-strapi project
Task Overview

This task covers setting up Strapi locally, exploring its structure, creating a sample content type, and documenting the process.
The setup is done on a local machine and pushed to a personal GitHub repository as instructed.

🛠️ Prerequisites

Ensure the following are installed on your system:

Node.js (v18 or above)

npm

Git

Windows / macOS / Linux

To verify installation:

node -v
npm -v
git --version

📂 Step 1: Create Project Directory
mkdir projects
cd projects

📥 Step 2: Create a New Strapi Application

A new Strapi project was created using the official CLI:

npx create-strapi-app my-strapi-app

Selected options:

Installation type: Quickstart

Database: SQLite

Example data: Yes

TypeScript: No

Cloud login: Skipped

Git initialization: Yes

▶️ Step 3: Run Strapi Locally
cd my-strapi-app
npm run develop


Strapi starts in development mode.

🌐 Step 4: Access Admin Panel

Open the browser and navigate to:

http://localhost:1337/admin


Create an admin user (local only).

🧱 Step 5: Explore Project Structure

Key folders explored:

src/ – APIs and content types

config/ – Configuration files

database/ – SQLite database

public/ – Public assets

types/ – Generated types

📝 Step 6: Create Sample Content Type

Using Content-Type Builder in the Admin Panel:

Collection Type: Article

Fields include:

title – Text

description – Text

slug – UID

cover – Media

author – Relation

category – Relation

blocks – Dynamic zone

The content type was saved and verified in Content Manager.

🔧 Step 7: Git Setup & Commit

Git was initialized automatically during project creation.

Configure Git identity:
git config --global user.name "Ooha Pinamareddi"
git config --global user.email "ooha@local.com"

Commit changes:
git add .
git commit -m "Strapi local setup with Article content type"

☁️ Step 8: Push Code to Personal GitHub Repository

As instructed for Day-1, the code was pushed to a personal GitHub repository.

git remote add origin https://github.com/<your-username>/strapi-task-1.git
git push origin master

🎥 Loom Video (Task Walkthrough)

A Loom video was recorded showing:

Running Strapi locally

Admin dashboard

Content-Type Builder

Article content type

Git commit history

🔗 Loom Video Link:
https://www.loom.com/share/e3c359e6e073448ab6f1ee2b322f27b0
