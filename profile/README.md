📘 Ekit — V0 Beta

A modern template-driven dynamic content engine with SSR, data sources, live preview, multilingual AI, and a powerful studio built with Angular + Monaco Editor.

Ekit allows developers to create dynamic pages and components using a custom Handlebars-like templating engine, connected to MongoDB datasources, rendered via server-side SSR, and edited in a modern UI with live preview, AI-assisted multilingual data, and snippet generation.

⚠️ This is the V0 Beta, fully functional and ready for early adopters.
The goal is to collect feedback before the official V1.

🚀 Core Features (V0 Beta)
🔧 Custom Handlebars Engine

Helpers: each, single, and extended internal helpers

Native access to datasources, assets, and frontmatter

Support for layouts, partials, components

Dynamic SSR rendering

Clean errors and debug logs

🗂️ Datasources (MongoDB)

Table-based model

Supports multilingual fields

Field types: text, number, boolean, select, rich text (WYSIWYG)

single and list modes

Automatic validation

Live updates reflected instantly in SSR preview

Auto-generated REST API for each datasource (CRUD)

🌐 Studio (Angular + Monaco Editor)

File explorer sidebar

Multi-tab editor

Powerful Monaco Editor integration

Dark UI inspired by Notion / Linear

Live SSR preview with instant update

Data editor (multilingual, WYSIWYG, select types, etc.)

Integrated assets browser

🤖 AI-Powered Multilingual Support

Ekit includes a built-in AI workflow to automatically generate translations for multilingual fields.

Detects source language

Auto-fills missing languages

Ensures content consistency

Manual override supported

Powered by OpenAI GPT models

This feature is fully operational in the V0 Beta.

✨ Intellisense (Beta)

Built on top of Monaco Editor, Ekit provides smart autocompletion:

Already available:

Datasources suggestions

Field suggestions

Snippets for helpers (each, single, etc.)

Partials / components suggestions

Assets autocompletion

Frontmatter hints

To be finalized:

Context-aware suggestions (this, nested scopes)

Helper signatures

Improved accuracy + reduced noise

This is the main Beta-area of the release.

📤 Export Tools
✔️ Export to Excel (XLSX)

Datasources can be exported instantly:

full table export

multilingual support

compatible with Excel / Sheets / BI tools

✔️ YAML + Snippet Generator

An integrated tool that generates:

frontmatter YAML blocks

template code snippets (loops, singles, partials, fields…)

ready-to-paste code for the editor

Huge time-saver for new users.

🔐 Authentication

Fully implemented:

Email / Password

Google OAuth

GitHub OAuth

Token/session security

User management in MongoDB

Production-ready.

⚙️ Architecture & Tech Stack

Frontend: Angular, Monaco Editor, Material

Backend: Node.js, Express

Realtime: Socket.IO + Redis adapter

Database: MongoDB

Rendering: Custom Handlebars engine + SSR

Deployment: PM2 cluster, Nginx

AI: OpenAI GPT for translations

🎯 What’s Included in the V0 Beta

The V0 Beta is fully functional and includes:

Complete editor UI

Templating engine

SSR live preview

Datasources + REST API

Auth system

AI multilingual translation

XLSX export

Snippet/YAML generator

Intellisense (beta version)

Error handling & logs

Example project + onboarding

This version is meant for early adopters & testers.

🧭 Roadmap
🟩 NOW (During V0 Beta)

Finalize Intellisense context-awareness

Improve UX in the Studio

Add more template examples

Polish WYSIWYG editor

Fix minor visual/UI rough edges

Improve documentation

🟨 NEXT (V1 Candidate)

Advanced version history

Undo/Redo global system

Public shareable preview links

Plugin system (helpers, datasources, render logic)

Workspace multi-project

Asset upload improvements

Deployment & publishing helpers

🟧 LATER (Post V1)

Marketplace (templates, components, datasources)

Collaborative editing (real-time multiplayer)

AI-assisted template generation

Built-in hosting + CDN

ElasticSearch integration for content indexing

Analytics and performance dashboards

Since this is a V0 Beta, your feedback is extremely valuable.

Please open issues for:

bugs

missing features

UX suggestions

improvement ideas

Or contact directly through GitHub Discussions.

💙 Credits

Built by Fabrice Grenouillet — 25 years of experience in development, Node.js specialist, creator of Ekit.
