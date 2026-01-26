# Ekit Studio – V0 Beta

A modern template-driven dynamic content engine with SSR, data sources, live preview, multilingual AI, and a powerful studio built with Angular + Monaco Editor.

> **Status**: V0 Beta – Private (non open source)

Ekit allows developers to create dynamic pages and components using a custom Handlebars-like templating engine, connected to MongoDB datasources, rendered via SSR, and edited in a modern UI with live preview, AI-assisted multilingual data, and snippet generation.

---

## Overview

Ekit is a studio and runtime engine designed to:

- Define content structures as **datasources** in MongoDB  
- Create **templates** based on a custom Handlebars-style syntax  
- Render content via **server-side rendering (SSR)**  
- Edit content and templates in a **web studio** with live preview  
- Leverage **AI** for multilingual content and developer productivity  

This V0 Beta is fully functional and aimed at early adopters and testers.

---

## Core Features (V0 Beta)

### Custom Handlebars Engine

- Custom helpers: `each`, `single`, and internal utility helpers  
- Native access to datasources, assets, and frontmatter  
- Support for layouts, partials, and components  
- Dynamic SSR rendering  
- Error logging and debug information

### Datasources (MongoDB)

- Table-based model backed by MongoDB  
- Multilingual fields support  
- Field types: text, number, boolean, select, rich text (WYSIWYG)  
- `single` and `list` modes  
- Automatic validation  
- Live updates reflected instantly in SSR preview  
- Auto-generated REST API (CRUD) for each datasource

### Studio (Angular + Monaco Editor)

- File explorer sidebar with project structure  
- Multi-tab editor for templates and config files  
- Monaco Editor integration (syntax highlighting, editing comfort)  
- Dark UI inspired by Notion / Linear  
- Live SSR preview with instant update  
- Data editor (multilingual fields, WYSIWYG, selects, etc.)  
- Integrated assets browsing and usage
- Custom domain configuration wth free SSL (lets encrypt)

### AI-Powered Multilingual Support

Ekit includes built-in AI workflows to handle multilingual content:

- Automatic translation for fields marked as multilingual  
- Detection of the source language  
- Generation of translations for configured target languages  
- Consistent content across languages  
- Manual override possible at any time  

Powered by OpenAI GPT models (or compatible AI backends).

### Intellisense (Beta)

Smart autocompletion inside Monaco Editor:

**Already available:**

- Suggestions for datasources  
- Suggestions for fields  
- Suggestions for helper snippets (`each`, `single`, etc.)  
- Suggestions for partials and components  
- Suggestions for assets  
- Hints for frontmatter YAML

**To be finalized:**

- Context-aware suggestions (`this`, nested loops, scopes)  
- Helper signatures and better types  
- Improved accuracy and reduced noise  

This is the main “beta” part of the V0.

### Export Tools

- **Export to Excel (.xlsx)**  
  - Export full datasources  
  - Multilingual fields included  
  - Directly usable in Excel, Google Sheets, BI tools  

- **YAML + Snippet Generator**  
  - Generates frontmatter YAML blocks  
  - Generates ready-to-paste template snippets (loops, singles, partials, fields)  
  - Helps users integrate datasources quickly in templates  

### Authentication

Fully implemented authentication layer:

- Email / password  
- Google OAuth  
- GitHub OAuth  
- Token / session handling  
- User storage in MongoDB  

---

## Architecture & Tech Stack

- **Frontend**: Angular, Monaco Editor, Material  
- **Backend**: Node.js, Express  
- **Realtime**: Socket.IO + Redis adapter  
- **Database**: MongoDB  
- **Rendering**: Custom Handlebars engine + SSR  
- **Deployment**: PM2 cluster, Nginx  
- **AI**: OpenAI GPT for automatic translations and language support  

---

## What’s Included in the V0 Beta

The V0 Beta includes:

- Full studio UI (editor, preview, datas management)  
- Custom templating engine  
- Live SSR preview  
- Datasources + auto-generated REST API  
- Authentication (email, Google, GitHub)  
- AI-powered multilingual translations  
- Excel (.xlsx) export  
- YAML & snippet generator  
- Intellisense (beta)  
- Error handling and logging  
- Example project and onboarding flow

The goal of this Beta is to validate the core UX, stability, and developer experience.

---

## Roadmap

### Now (during V0 Beta)

- Finalize Intellisense context-awareness  
- Improve Studio UX (ergonomics, clarity, messages)  
- Add more template and datasource examples  
- Polish WYSIWYG editor integration  
- Improve documentation and onboarding

### Next (V1 Candidate)

- Advanced version history for templates and datasources  
- Global undo/redo system  
- Public shareable preview URLs  
- Plugin system (custom helpers, custom datasources, custom logic)  
- Multi-project workspaces  
- Improved asset management and upload flows  
- Deployment and publishing helpers

### Later (Post V1)

- Marketplace for templates, components, and datasources  
- Real-time collaborative editing (multi-user)  
- AI-assisted template generation and refactoring  
- Built-in hosting and CDN for generated content  
- ElasticSearch integration for content indexing and search  
- Analytics and performance dashboards

---

## Access / Beta Program

Ekit is currently in **private V0 Beta**.  
The source code is **not open source**.

If you are interested in:

- testing the studio,  
- integrating it in your stack,  
- or discussing use cases,

please reach out to the maintainer.

---

## Feedback

Since this is a V0 Beta, feedback is extremely valuable.

You can report:

- bugs  
- UX issues  
- feature requests  
- integration questions  

via issues, discussions, or direct contact (depending on how this repository is shared).

---

## Credits

Ekit is created and maintained by **Fabrice Grenouillet**,  
a developer with 20+ years of experience in application development, Node.js, Angular, and data-driven tools.
