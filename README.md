# 🤖 AutoGen Data Cleaning Studio
**with OpenAI GPT-4.1-mini**

> **Upload raw CSV/Parquet files and let AutoGen agents analyze, clean, and transform them into production-grade datasets with executable ops code.** ⚡

---

## ✨ Features

### 🎯 **Core Functionality**
- 📊 **CSV/Parquet Upload** - Upload and profile datasets instantly
- 🤖 **AI-Powered Analysis** - AutoGen Analyst agent identifies data quality issues
- 🔧 **Intelligent Cleaning** - Transformer agent generates executable cleaning code
- 📝 **Interactive Studio** - Chat with agents to refine cleaning strategies
- 💾 **Export Pipelines** - Download production-ready Python/SQL code
- 📈 **Real Dataset Profiling** - Pandas/PyArrow integration for accurate analysis

### 🎨 **Beautiful UI/UX**
- ✨ **Modern 2025 Design** - Glassmorphism, gradients, video backgrounds
- 🌙 **Dark Mode** - Full theme support with smooth transitions (dark by default)
- 📱 **Fully Responsive** - Optimized for desktop, tablet, and mobile
- 🎯 **Intuitive Interface** - Clean, user-friendly design with smooth state transitions
- ♿ **Accessible** - WCAG AA compliant with keyboard navigation

### 📊 **Studio Features**
- 🔍 **Interactive Data Grid** - Virtual scrolling, search, sort, and filter
- 💬 **Agent Chat** - Real-time conversation with Analyst and Transformer agents
- 📋 **Code Highlighting** - Syntax-highlighted code blocks with copy-to-clipboard
- 📥 **Export Functionality** - Download generated cleaning code as Python files
- ⏱️ **Typing Indicators** - Visual feedback during agent processing
- 📜 **Job History** - Search, filter, and paginate through cleaning runs

### 🚀 **Advanced Features**
- 🔄 **Real-Time Processing** - Background job system with status polling
- 💾 **Persistent Storage** - All jobs, projects, and messages saved to Supabase
- 🎯 **Multi-Agent System** - Analyst ↔ Transformer conversation loop
- 📊 **Dataset Profiling** - Automatic detection of nulls, type issues, and outliers
- 🔐 **Secure Storage** - Supabase integration with service role authentication
- ⚡ **Caching** - Redis caching for dataset profiles and job status

---

## 🏗️ Tech Stack

### **Backend** 🐍
- **FastAPI** - Modern Python web framework
- **OpenAI API** - GPT-4.1-mini for AI-powered analysis and code generation
- **PyAutoGen** - Multi-agent conversation framework
- **Pandas & PyArrow** - Dataset profiling and data manipulation
- **Python 3.11+** - Latest features and performance

### **Frontend** ⚛️
- **Next.js 15** - React 19 with App Router
- **Tailwind CSS** - Utility-first styling
- **shadcn/ui** - Beautiful component library
- **Lucide Icons** - Modern icon set
- **TanStack Virtual** - Virtual scrolling for large datasets
- **React Syntax Highlighter** - Code display with syntax highlighting

### **Database & Cache** 💾
- **Supabase** - PostgreSQL with schema `datacleaning`
- **Upstash Redis** - Serverless job queue & caching (prefix `datacleaning`)

### **AI Framework** 🤖
- **AutoGen** - Multi-agent system (Analyst ↔ Transformer)
- **OpenAI GPT-4.1-mini** - Primary model for analysis and code generation

### **Deployment** 🚀
- **Railway** - Backend API deployment
- **Vercel** - Frontend deployment

---



### 🏠 Homepage
*Beautiful landing page with video backgrounds and clear value proposition*

### 🎮 Studio
*Interactive cleaning workspace with dataset preview, agent suggestions, and chat*

### 📊 Dashboard
*Comprehensive overview with statistics, recent runs, and agent activity*

---

## 📖 User Guide

### 🎮 Using the Studio

1. **Upload Dataset**
   - Navigate to **Datasets** page
   - Click **"Choose File"** or drag-and-drop CSV/Parquet file
   - File is automatically profiled (nulls, types, outliers)

2. **Start Cleaning**
   - Go to **Studio** page
   - View dataset preview with interactive grid
   - Enter your request: *"Analyze this dataset and propose cleaning steps"*

3. **Review Agent Suggestions**
   - **Analyst** identifies data quality issues
   - **Transformer** generates cleaning plan with executable code
   - Review each step: description, action, and affected columns

4. **Apply & Export**
   - Click **"Apply"** on steps you want to use
   - View generated Python code with syntax highlighting
   - Click **"Download .py"** to export the cleaning pipeline

5. **Chat with Agents**
   - Use the chat interface to refine cleaning strategy
   - Ask follow-up questions or request modifications
   - View conversation history in the timeline

### 📊 Using the Dashboard

1. **View Statistics**
   - Total datasets tracked
   - Cleaning runs in last 7 days
   - AutoGen steps logged

2. **Recent Activity**
   - View last 5 cleaning runs
   - See fixes, iterations, and exports per run
   - Check status (clean, in-progress, error)

3. **Agent Activity**
   - Monitor Analyst and Transformer actions
   - Track suggestions awaiting approval
   - View activity timeline

### 📜 Using Job History

1. **Search & Filter**
   - Search by project ID or job ID
   - Filter by status (All, Done, Running, Queued, Error)
   - Sort by date (newest first)

2. **View Details**
   - Click **"View Details"** on any job
   - See complete cleaning plan
   - Review generated code
   - Check execution status

---


---

## 👨‍💻 Creator

**Created by Derril Filemon**

---

## 🙏 Acknowledgments

- **OpenAI** - For GPT-4.1-mini API
- **AutoGen** - For multi-agent framework
- **Supabase** - For database & storage
- **Upstash** - For Redis caching
- **Railway** - For backend deployment
- **Vercel** - For frontend deployment
- **shadcn/ui** - For beautiful components

---

<div align="center">


Made with ❤️ and ☕ by [Derril Filemon](https://github.com/derril-tech)

</div>
