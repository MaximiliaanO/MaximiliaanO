# Maximiliaan Oorschot

After 15 years in finance and private equity I made a deliberate transition 
into software development in 2025. Everything on this page was built, learned, 
or earned since then.

Currently working as a freelance developer and AI automation specialist 
based in the Netherlands, focused on fintech and data-heavy applications.

## 💻 Tech Stack

**Languages:** Python · TypeScript · JavaScript · SQL · Rust (learning) · Bash

**Python Libraries:** asyncio · aiohttp · asyncpg · psycopg2 · BeautifulSoup4 · Transformers · Pandas · Matplotlib · Altair

**Frontend:** React · Tailwind CSS · Vite · Streamlit

**Backend:** FastAPI · Node.js

**Databases:** PostgreSQL · Supabase · CosmosDB

**Data & BI:** Power BI · Power Query · DAX

**AI & ML:** Anthropic SDK · RAG pipelines · MCP · Azure AI Foundry · Copilot Studio

**Infrastructure:** Docker · Proxmox · Linux (Debian) · Git · CI/CD

**Cloud:** Azure

## 🛠️ Projects

- [Samen Family Planner](https://github.com/MaximiliaanO/Family-Planner-MVP) - *TypeScript*

Samen, is an application for families to manage their busy schedules, it gives the user one overview of what the whole family is doing during the week. It offers a unique way of viewing the schedule of your family.

- [ISA AI Accountant](https://isaudit.nl/) - *TypeScript, Azure*

ISA AI accountant is a specialized application for audit professionals. It seeks to help them writing memo's, coach junior empolyees, quick search on audit standards and the applicable laws. I have worked on refactoring the frontend, as well as implementing the RAG pipeline.

- SCALA - *Microsoft Copilot Studio*

Scala is a business application I have built for a client that is active in supporting people with their reintegration to their workplace. Scala automated a process that would cost employees 20-30 minutes down to 5 minutes. The bot guides you through the planning of a reintegration and automatically generates a confirmation e-mail, sets calendar invites for deadlines and stores the process and deadlines into an Excel sheet.

- [ANON](https://anonimiseerdirect.nl/) - *TypeScript*

When I started working with [CoCreate](https://www.cocreateai.nl/) I was asked to refactor a large portion of the ANON application. I refactored a quickly generated \<div> soup to structured and more maintainable TSX/TS code.


- [Fuel Price Data Pipeline](https://github.com/MaximiliaanO/Data-Pipeline---Fuel-Prices) - *Python, SQL*

The fuel price data pipeline is a serious data project. The application collects price data from approximately 180 gas stations in the Netherlands and stores it on the PostgreSQL server that is hosted on my homelab. The data is presented on my the frontend I built for it using Streamlit [data summary](https://oorschot.tech/prijzen_samenvatting). 

- [Fuel Price Dashboard](https://github.com/MaximiliaanO/streamlit-fuel-price-dashboard) - *Python*

This repository contains the source code for affore mentioned presentation of the data from the Fuel Price Data Pipeline. This project contains the dockerized FastAPI backend that is installed on my homelab. As well as the dockerized frontend that runs on my VPS.

- [Job Application Assistant](https://github.com/MaximiliaanO/job-application-assistant) - *Python*

This application is an AI powered cover letter generator, you paste in your CV and the job description and AI will help you by generating a draft cover letter. Then you can edit the draft to your liking. Whilst creating this application I was experimenting with local LLM's so I ran a local model and created a FastAPI backend to communicate with the model. The frontend is made with Streamlit.

- [Contoso Analysis](https://github.com/MaximiliaanO/SQL-for-data-analysis) - *SQL*

In this project I downloaded the [Contoso Dataset](https://www.microsoft.com/en-us/download/details.aspx?id=18279) and ingested it into my own PostgreSQL database. The goal was to do data analysis but solely using SQL. The project checks three main business KPI's: customer segmentation, cohort analysis and customer retention analysis. The visualizations were made with ChatGPT.

- [Real Estate Valuations](https://github.com/MaximiliaanO/PowerAutomate_PowerBI_real-estate-valuations) - *Power BI & Power Automate*

I automated manual workflows that were previously monitored in Microsoft Excel to an automated data pipeline and visualization. This application fetches data from a REST API, the data is then parsed by Power Automate and saved in a file on SharePoint. From there Power Query handles the ETL process and Power BI handles the visualizations.

## 🎓 Certifications

| Certification                           | Issuer        | Year |
|-----------------------------------------|---------------|------|
| Claude Code in Action                   | Anthropic     | 2026 |
| Building with the Claude API            | Anthropic     | 2026 |
| SQL+ for Data Analytics                 | Luke Barousse | 2025 |
| AZ-900: Azure Fundamentals              | Microsoft     | 2025 |
| SQL for Data Analytics                  | Luke Barousse | 2025 |
| PL-300: Microsoft Power BI Data Analyst | Microsoft     | 2025 |

## 📚 Books

### Currently Reading:

- **Fluent Python**:

As Python is my main programming language I want to further deepen my knowledge of it. Fluent Python is divided into five sections and goes deep into Data Structures, Functions as Objects, Classes and Protocols, Control Flow and Metaprogramming. I am currently on chapter 2 reading about lists.

---

### Future Reading:

- The Rust Programming Language:

I want to add a fast, static, compiled language to my arsenal so I will take a swing at Rust when I am done with Fluent Python.

---

### Data Analytics Books:

- Analyzing Data with Microsoft Power BI and Power Pivot for Excel

The first book I have ever read on Power BI and Power Pivot. It covers data modelling in Power BI. The most used model for Power BI is a star schema hence the book covers a lot about star schema's. However, it also covers working with date and time, slowly changing dimension tables, using snapshots and many-to-many relationships.

- Supercharge Power BI

Where the previous book covers a lot of ground on the theory side, this book makes it really practical. Especially coming from an excel background it teaches you the most important concepts of Power BI as well as the most used syntax for the DAX language.

- Microsoft Power BI Data Analyst Exam Ref PL-300

Helped me prepare for the PL-300 certification by Microsoft.

- Collect, Combine, and Transform Data Using Power Query in Power BI and Excel

Power Query is the ETL tool that ships with Power BI and Excel. I used this book as a reference while working on my Power BI projects. I have read it until chapter 7.

- Data als kompas

I met the author of this book Rob van den Wijngaard who has a great vision on data driven businesses and is advocating for the four-leaf clover data driven organisation. In this data driven business model the customer is in the center of the clover and the organisation culture, processes, people and IT infrastructure are the leafs. The book is inspiring business leaders to think about data driven decision making and the implementation of data driven decision making within their business.

---

### Programming Books:

- HTML & CSS: Jon Duckett

This book is one of the core fundaments of web developments. It teaches the most important html elements as well as styling through vanilla CSS.

- JavaScript Crash Course

This book teaches you the most important syntax of JavaScript, the language of the web. The first part is dedicated to learn the syntax, data types, loops and conditionals. The second part teaches about how JavaScript interacts with the DOM. The last part consists of several JavaScript projects to get your feet wet.

- Python Crash Course: Eric Matthes

This is the book that sparked my interest into programming in the first place. Before starting this book I had almost zero experience in programming. Like the JavaScript Crash Course book the first part is introductory to data types, control flow etc. The second part consists of several projects. When I finished the data analysis project I decided to make my own software instead of keep following the book. I am still inclined to make the game some day.

- Automate the Boring Stuff with Python: Al Swiegart

This is a fun book that contains all kinds of small projects to give you some inspiration what you can do with Python. Topics covered are regex, web scraping, organising files on your computer, working with excel sheet, pdf documents, word documents, csv files and json files. Also a fun little project was controlling your computer through sending e-mails to yourself.

- The Linux Command Line: William Shotts

Almost all my computers at home run on the Linux kernel and it is foundational in general computing. This book is great to in teaching you how to navigate your favourite linux-based distro from the terminal. It is extensive and gradually builds up in terms of difficulty. The last part of the book is the most fun part in my opinion this is where William Shotts teaches you shell scripting. You can create scripts to automate things on your operating systems and use shell scripting as glue to execute your favourite shell programs. As I was already familiar with programming when I picked up this book this felt very natural to me and a great way to automate things in the OS itself. One of the fun things to do was operate my desk lavalamp from the [terminal](https://github.com/MaximiliaanO/The-Linux-Command-Line-Summaries/blob/main/hue/hue).

---

### AI and Machine Learning Books:

- Hands-On Large Language Models

Great book about large language models and how they work. It starts off with the groundbreaking "Attention Is All You Need" paper and gives an overview of the historical events that happend in the LLM space. It breaks down tokenization and embeddings and explains transformers. It covers further topics such as text classfication with LLM's, prompt engineering, retrieval augmented generation (RAG) and finishes of with creating your own embeddings and fine-tuning models.

---

### Books Table

| Title                                                                       | Author                                      | Status             |
|-----------------------------------------------------------------------------|---------------------------------------------|--------------------|
| Supercharge Power BI                                                        | Matt Allington                              | ✅ Completed       |
| Analyzing Data with Microsoft Power BI and Power Pivot In Excel             | Alberto Ferrari & Marco Russo               | ✅ Completed       |
| Microsoft Power BI Data Analyst Exam Ref PL-300                             | Daniil Maslyuk                              | ✅ Completed       |
| Data als Kompas                                                             | Rob van den Wijngaard                       | ✅ Completed       |
| Crash Course Python                                                         | Eric Matthes                                | ✅ Completed       |
| Automate the Boring Stuff With Python                                       | Al Sweigart                                 | ✅ Completed       |
| Crash Course JavaScript                                                     | Nick Morgan                                 | ✅ Completed       |
| HTML & CSS                                                                  | Jon Duckett                                 | ✅ Completed       |
| The Linux Command Line                                                      | William Shotts                              | ✅ Completed       |
| Fluent Python                                                               | Luciano Ramalho                             | 📖 Reading         |
| Introduction to PostgreSQL                                                  | Ryan Booz & Grant Fritchey                  | 📖 Reading         |
| The Rust Programming Language                                               | Steve Klabnik, Carol Nichols, Chris Krycho  | ⏸️ Paused          |
| Collect, Combine and Transform Data Using Power Query in Power BI and Excel | Daniil Maslyuk & Gil Raviv                  | ⏸️ Paused          |
| Python for Data Analysis                                                    | Wes McKinney                                | ⏸️ Paused          |
| Fundamentals of Data Engineering                                            | Joe Reis & Matt Housley                     | ⏸️ Paused          |
| Hands-On Large Language Models                                              | Jay Alammar & Maarten Grootendorst          | ⏸️ Paused          |
| Data Structures the Fun Way                                                 | Jeremy Kubica                               | 🔜 Not yet started |
| Math for Programming                                                        | Ronald T. Kneusel                           | 🔜 Not yet started |
| The Definitive Guide to DAX                                                 | Marco Russo & Alberto Ferrari               | 🔜 Not yet started |
| C# and .NET 6                                                               | Mark J. Price                               | 🔜 Not yet started |
| SQL for Data Analysis                                                       | Cathy Tanimura                              | 🔜 Not yet started |
| Clean Code in Python                                                        | Mariano Anaya                               | 🔜 Not yet started |


---

## 🖥️ Homelab

### 🖥️ Homelab Hardware

| Component | Model                    | Specs           |
|-----------|--------------------------|-----------------|
| Case      | Fractal Design Define R5 | Black           |
| CPU       | Intel Core i5-14600K     | 14 cores        |
| RAM       | Kingston Fury Beast      | 64GB DDR5       |
| SSD       | Lexar NM790 M.2 PCIe 4.0 | 2TB             |
| HDD       | Seagate IronWolf (x4)    | 4 × 12TB = 48TB |
| PSU       | Corsair                  | 550W            |
| UPS       | APC Back-UPS BE850G2     | 850VA           |
| OS        | Proxmox                  | Based           |



### 🖥️ Homelab Software

| VM/Container | OS | Purpose |
|---|---|---|
| HOST | Proxmox | Host OS |
| LXC | - | Jellyfin media server |
| VM | Ubuntu Server (headless) | Dev server / projects |
| VM | Windows 11 | Windows workloads |
| VM | Fedora (planned) | Linux desktop experimentation |

### 🐳 Homelab Docker Services (Ubuntu Server)

| Container        | Image                    | Purpose                 | Port |
|------------------|--------------------------|-------------------------|------|
| Family Planner   | family-planner           | Family calendar app     | 5173 |
| Sonarr           | linuxserver/sonarr       | TV show management      | 8989 |
| Radarr           | linuxserver/radarr       | Movie management        | 7878 |
| Bazarr           | linuxserver/bazarr       | Subtitle management     | 6767 |
| Prowlarr         | linuxserver/prowlarr     | Indexer management      | 9696 |
| Jellyseerr       | fallenbagel/jellyseerr   | Media requests          | 5055 |
| SABnzbd          | linuxserver/sabnzbd      | Usenet downloader       | 8080 |
| qBittorrent      | linuxserver/qbittorrent  | Torrent client          | 8081 |
| Gluetun          | qmcgaw/gluetun           | VPN gateway             | -    |
| PostgreSQL       | postgres:18.1            | Database server         | 5432 |
| pgAdmin4         | dpage/pgadmin4           | DB admin UI             | 8200 |
| Adminer          | adminer                  | DB admin UI             | 8085 |
| Homepage         | gethomepage/homepage     | Homelab dashboard       | 3010 |
| Fuel Prices API  | fuel-prices-api          | Dutch fuel price tracker| 8000 |
| Syncthing        | linuxserver/syncthing    | File sync               | 8384 |

### Other Services

| Software | Purpose |
|----------|---------|
| Wireguard | VPN Tunneling and acces to my own network from the web |
| Snapraid | Flexible data redundancy |
| MergerFS | To have one mountpoint for my files divided over multiple drives |

---

## 🖥️ VPS

### 🖥️ VPS Specs

| Component | Specs                    |
|-----------|--------------------------|
| CPU       | 1 Core                   |
| RAM       | 2GB                      |
| SSD       | 60 GB                    |
| OS        | Ubuntu Server (headless) |

### 🐳 VPS Docker Services

| Container              | Image                    | Purpose                     | Port |
|------------------------|--------------------------|-----------------------------|------|
| Fuel Prices Frontend   | fuel-prices-streamlit-v2 | Streamlit data presentation | 8501 |
| Nginx proxy manager    | jc21/nginx-proxy-manager | Reverse Proxy Routing       | 80   |

### Other Services

| Software  | Purpose                                                |
|-----------|--------------------------------------------------------|
| Wireguard | VPN Tunneling and acces to my own network from the web |

---


## 🖥️ Other Hardware

### 🖥️ Gaming PC


| Component | Model                                         | Specs      |
|-----------|-----------------------------------------------|------------|
| CAS       | Fractal Design                                | Black      |
| CPU       | AMD Ryzen 7 5700X CPU                         | 8 cores    |
| RAM       | Kingston DDR4 FURY Beast RGB                  | 32 GB DDR4 |
| RAM       | Ballistix                                     | 16GB DDR4  |
| GPU       | MSI GeForce RTX 5060 Ti 16G VENTUS 2X OC PLUS | 16GB       |
| SSD       | Intel 660p                                    | 0.5TB      |
| SSD       | Samsung S-600 SSD                             | 2TB        |
| PSU       | Corsair RME 750e                              | 750W       |
| CUF       | Arctic Freezer 36 A-RGB Black                 | 2x 120mm   |
| CAF       | Corsair RS120 ARGB Triple Pack                | 3x 120mm   |
| OS        | Windows 10                                    | Mid        |


---

### 💻  Laptop

Framework 13:

| Component | Model                        | Specs           |
|-----------|------------------------------|-----------------|
| SCR       | 2.8K Display 13.5" 120Hz     | 2256 x 1504     |
| BEZ       | Orange bezel                 | Orange          |
| KYB       | Framework Laptop 13 Keyboard | English - Linux |
| CPU       | Intel Core Ultra 5 125H      | 14 cores        |
| RAM       | Framework supplied DDR5-5600 | 32GB DDR5       |
| SSD       | Lexar NM790 M.2 PCIe 4.0     | 2TB             |
| EXP       | 2x USB-C expansion card      | Orange          |
| EXP       | 1x USB-A expansion card      | Silver          |
| EXP       | 1x HDMI expansion card       | Silver          |
| STK       | DBrand body sticker          | Black           |
| OS        | Pop!_OS                      | Nice            |


---

### 📱 Phone

Apple IPhone 16 Pro 256GB
