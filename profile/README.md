# Ekit — Dynamic Template Studio with SSR, Data Sources & Real-Time Preview

Ekit is a modern template development studio designed for developers and content teams who need **dynamic SSR rendering**, **structured data sources**, and **powerful Handlebars-based templating** — all in a clean, real-time editing environment.

Ekit combines:
- a multilingual datasource manager (MongoDB),
- a customized Handlebars templating engine,
- real-time SSR preview,
- Monaco-based editor with advanced Intellisense,
- a full Node.js/Express rendering pipeline,
- automatic REST API generation for datasources.

Perfect for building dynamic pages, emails, marketing templates, product listings, landing pages, blog structures, and more.

---

## ✨ Features

### 🔨 Template Editor (Handlebars + Custom Helpers)
- Handlebars templating with `{{#each}}`, `{{single}}`, layouts, and partials  
- Dynamic Intellisense for:
  - datasource fields  
  - partials  
  - assets  
  - layout blocks  
- YAML frontmatter for datasource binding  
- Live SSR preview with hot reload

### 🗂️ Datasource System
- MongoDB-backed structured tables  
- Multilingual fields supported  
- Field types: text, number, boolean, select, rich text, media, etc.  
- Single + list datasource modes  
- Automatic validation (required fields, types)

### ⚙️ Real-Time Rendering Engine
- Modified Express/Handlebars runtime  
- Dynamic SSR per template  
- Auto partial resolution  
- Asset autocomplete  
- Hot template reload via Socket.IO

### 🖥️ Studio Interface
- File explorer for templates, components, layouts, assets  
- Monaco Editor with syntax highlighting  
- Live preview panel  
- Data editor for datasource rows  
- Dark UI inspired by Notion & Linear  
- Multilanguage UI (i18n)

### 🌐 API & Integrations
- Auto-generated REST API for datasources  
- Webhooks & real-time events (via Socket.IO)  
- Ready for integration with external CMS or frontends

---

## 🚀 Tech Stack

- **Frontend:** Angular, Material, Monaco Editor  
- **Backend:** Node.js, Express, Socket.IO  
- **Database:** MongoDB  
- **Runtime:** PM2 + Nginx  
- **Auth:** Email/password, Google OAuth (GitHub/Apple coming)  

---

## 📦 Folder Structure (Simplified)

