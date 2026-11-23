![](https://komarev.com/ghpvc/?username=diegoMorales&color=red&style=plastic)

<h1 align="center">
  <a href="https://git.io/typing-svg">
    <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=700&pause=1000&color=E63946&width=435&lines=Welcome+to+my+github+profile!!!" alt="Typing SVG" />
  </a>
</h1>
<p align="center">
  <img src="https://github.com/diegoMorales31/diegoMorales31/blob/main/diegoMorales31.png" alt="Banner of a developer sitting in front of a desk">
</p>

# 💡 **About me**
My name is **Diego Morales**, I hold a degree in **Computer Engineering** from the European University of the Atlantic, where I received a merit-based scholarship and contributed to **European-level projects**.  

I’ve worked with technologies such as **JavaScript (Vue.js & React), C# (.NET) and Spring Boot**, and I also have experience in **front-end development, and back-end systems**.  

🌍 I am fluent in **English** and have a basic knowledge of **German**, which allows me to collaborate in multicultural environments.  

⚡ I consider myself a responsible and adaptable person, always eager to **learn independently**, face new challenges, and grow personally and professionally. I value teamwork and believe in contributing positively to every project I take part in.  


## 📫 Reach Me At  

<p align="center">
  <a href="mailto:dmorgal31@gmail.com" title="Email me!">
    <img src="https://skillicons.dev/icons?i=gmail" alt="Gmail" />
  </a>
  <a href="https://www.linkedin.com/in/diego-javier-morales-galindo-a67652379" title="Connect on LinkedIn!">
    <img src="https://skillicons.dev/icons?i=linkedin" alt="LinkedIn" />
  </a>
</p>



# 🛠️ **Languages and Tools**

<br>

## Frontend
<p align="center">
  <img src="https://skillicons.dev/icons?i=react,vue" />
</p>

## Backend
<p align="center">
  <img src="https://skillicons.dev/icons?i=spring,nodejs,dotnet" />
</p>

## Fullstack
<p align="center">
  <img src="https://skillicons.dev/icons?i=nextjs" />
</p>

## Databases & Backend Services
<p align="center">
  <img src="https://skillicons.dev/icons?i=mysql,mongodb,supabase" />
</p>

## Tools
<p align="center">
  <img src="https://skillicons.dev/icons?i=github,postman,idea,vscode" />
</p>

## Deploy
<p align="center">
  <img src="https://skillicons.dev/icons?i=docker,vercel" />
</p>


# ⏱ Khronos

**Khronos** is a web app for running small hospitality venues such as restaurants, bars, hotels and event halls. It covers staff scheduling, time tracking and day-to-day business. It replaces the usual mix of spreadsheets, WhatsApp messages and paper sign-in sheets.

## Who uses it

- **Owners** set up their venues and split each one into zones (Terrace, Kitchen, Main hall). They schedule their staff and plan events, then track hours, costs, cash and stock. One owner can run several venues.
- **Workers** see their own schedule, clock in and out from their phone, check their hours and get notified when anything about their shifts changes.
- **A platform admin** creates owner accounts and decides which plan each owner is on.

## What it does

- **Scheduling.** Owners add shifts in batches, for several people over several days at once, or copy last week's rota. Shifts can run past midnight, and each one can carry notes for the worker. A day board shows every zone, who is working and when.
- **Events.** An event is booked in one zone, or across the whole venue as a "global" event. Owners can only assign people whose shift covers the event. When a shift or event changes, assignments that are no longer covered are removed automatically.
- **Time tracking.** Workers clock in and out with one tap, and owners can fix mistakes. Every correction keeps a history, which gives a proper legal record of working hours.
- **Reports.** Planned hours against hours actually worked, lateness, and staff cost from each person's hourly rate. Everything can be exported to CSV.
- **Business.** Daily cash closings with the expected and counted cash and any difference, plus expenses. A summary shows sales, costs and estimated margin against the previous period.
- **Inventory.** Products, suppliers, stock in and out, waste, stocktakes and purchase orders, with alerts when stock runs low.
- **Notifications.** In-app notices and phone push notifications for new shifts, changes, cancellations and venue-wide events. Each worker gets one grouped notice per change instead of a flood.
- **Plans.** Three tiers: Khronos for scheduling and hours, Plus adds cash and the business summary, and Ultra adds inventory.

## How it's built

- **Backend:** a REST API in **Java 17 and Spring Boot**, on **PostgreSQL** (hosted on Supabase) with **Flyway** migrations. It runs in Docker on **Fly.io**.
  - Sign-in uses short-lived access tokens with refresh tokens, one session per device.
  - Every request is checked against who owns which venue, so owners only ever see their own venues.
  - Requests that arrive at the same time are handled in a fixed order using database locks, so double bookings and races are prevented.
- **Frontend:** a **React** single-page app built with Vite, served from **Cloudflare**.
  - It installs on a phone like a native app, with push notifications.
  - It's in Spanish and English, and always uses the venue's own time zone.
  - It's designed to work on phones from 360px wide upwards.
- **Quality:** integration tests run the whole API against a real PostgreSQL database. The frontend has a large component test suite, including checks of the phone layout.

## What makes it different

Khronos is built around the real rules of hospitality work. The service day doesn't end at midnight, a person can't be in two places at once, and you can't put someone on an event when they aren't working. The app enforces these rules itself. Owners get one place for staff, hours, cash and stock, and workers just open the app on their phone to see where they need to be.

## 🐞 Sistema Gesto Plagas

My previous featured project is called **Sistema Gesto Plagas**, it is an **advanced report management system for pest control company "Gesto Plagas" in Guatemala City**, developed with **Next.js 15, Tailwind CSS 4, and Supabase**.
The platform allows technician to **manage accounts, generate dynamic PDF reports, handle catalogs of pests/areas/traps, and visualize statistics**, all within a fast and modern interface.

✨ **Main Features**

* 🔑 **Secure authentication** with Supabase Auth and role system (admin, technician).
* 🖥️ **Admin panel** for managing users, areas, pests, and traps.
* 📄 **PDF report generation with digital signatures**.
* 📊 **Interactive charts and statistics** with Recharts.
* 🗄️ **Catalog management** (pests, areas, traps).
* 📱 **Modern and responsive interface** with Tailwind CSS 4.
* 🔒 **Robust security**: RLS in Supabase, data validation with Zod, input sanitization.

🔧 **Technologies Used**

* **Frontend**: Next.js 15, React 19, TypeScript
* **Styling**: Tailwind CSS 4, Radix UI
* **Backend / DB**: Supabase (PostgreSQL, Auth, Storage)
* **PDF**: @react-pdf/renderer, jsPDF
* **Charts**: Recharts
* **Forms**: React Hook Form + Zod
* **Icons**: Lucide React

## 📸 Screenshots and Reports

### 🔑 Login
<div align="center">
<img width="647" height="727" alt="Login" src="https://github.com/user-attachments/assets/8507cbfe-3bb6-4de0-aa09-c436dda22584" />
     <p align="center">Login screen where users enter their credentials to access the application.</p>  
    <br>
</div>

### 📊 Dashboard
<div align="center">
<img width="1856" height="914" alt="Dashboard" src="https://github.com/user-attachments/assets/db4c7678-5e21-43f7-858c-8c7ff5e29feb" />
  <p align="center">Main view after login showing a summary of metrics and quick access to key sections.</p>
  <br>
</div>

### 📝 Report
<div align="center">
<img width="1022" height="903" alt="InformacionPrincipal" src="https://github.com/user-attachments/assets/6ba4e9f4-be94-41c6-a1a8-08740d7ce3b6" />
    <p align="center">
      Detailed report generation screen with full information from available records.
    </p>
      <br>
    <p align="center">
      The technician selects the establishment being serviced; the database fetches related information (address and manager) and populates the       fields. The system recognizes the technician and automatically inserts their name.
    </p>
    <br>
</div>

<div align="center">
<img width="1014" height="1374" alt="ProductosUtilizados" src="https://github.com/user-attachments/assets/5de825b5-3716-4461-bfba-c2c7785c74cd"/>
    <p align="center">
      The technician selects the product used, and related data is auto-filled. The technician chooses the pest category, application method,         and usage. Zones where the product was applied are marked. Multiple products can be added as needed.
    </p>
    <br>
</div>

<div align="center">
<img width="1013" height="2404" alt="Trampas" src="https://github.com/user-attachments/assets/aaf2639b-2057-4dbe-850d-118be318f2f9" />
    <p align="center">
      The technician can select trap types and quantities used and mark if traps caught pests or were obstructed. A general data chart displays         totals. Each trap and overall information are charted in the report.
    </p>
    <br>
</div>

<div align="center">  
<img width="1036" height="674" alt="Firmas" src="https://github.com/user-attachments/assets/78a543a8-6e0c-4448-8fce-2e89394bf670" />
    <p align="center">
      Clients can digitally sign at the end of the report. The technician's signature is pre-stored and automatically appears in each report to       avoid inconsistencies.
    </p>
    <br>
</div>

### 👀 Preview
<div align="center">
<img width="1856" height="4135" alt="VistaPrevia" src="https://github.com/user-attachments/assets/11a0ca10-df38-4684-b028-9d8a534c0f9b" />
    <p align="center">Preview of reports before sending or exporting.</p>
    <br>
</div>

### 📤 Report Sending Panel
<div align="center">
<img width="1011" height="381" alt="PanelDeEnvioReporte" src="https://github.com/user-attachments/assets/2cd69c85-b773-4e08-b9bd-0523840c0ffa"/>
    <p align="center">Interface to send generated reports to recipients. The "Resend" tool is used for email delivery.</p>
    <br>
</div>


📄 **PDF Report**: 
[The client recieves an email with a pdf like this attached](https://github.com/user-attachments/files/22212103/Reporte_Servicio_Cafeteria.Dulce.Aroma_2025-09-08.pdf)

🚀 **Deployment**:
The project is deployed on **Vercel** with direct GitHub integration.


## 🖥️ **Other Projects**

Here are some other projects I’ve contributed to during my academic and professional journey:

  🔹 [**Financen_Lab**](https://sim.financenlab.com/) – *Front-end developer* for a financial simulator funded by the EU and paired with other       universities around EU.  
  🔹 [**DietinG_Lab**](https://virtual-patient.edietinglab.eu/) – *Front-end developer* for a nutritional simulator focused on healthcare.  
  🔹 [**Multi Lingual Scientific Journals (MLS Journals)**](https://www.mlsjournals.com/) – *Back-end developer* for a scientific journal             platform.  
  🔹 [**RooMe**](https://github.com/Dmoga31/TFG_DiegoMorales_RooMe.git) – University Thesis - Web application to coordinate housing rentals for       university students in Santander, Cantabria.   
  🔹 **Triton (Repsol S.A.)** – *Developer* for a program supporting trading operations of physical goods, derivatives, and financial market         contracts (internship at NTT Data).  


✨ More personal and open-source projects will be published soon here on my GitHub!
