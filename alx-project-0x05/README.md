# ALX Project 0x03 Setup

This project demonstrates building a Next.js application with a **shared layout**, **Google Fonts**, **imperative routing**, and a **custom 404 page**.  

---

## **Features Implemented**

### **1. Shared Layout (DRY Structure)**  

- Created reusable `Header`, `Footer`, and `Layout` components under `components/layouts/`.  
- Created a `Button` component under `components/common/` for consistent UI.  
- Wrapped all pages with the `Layout` in `pages/_app.tsx` for global header/footer.

### **2. Imported Google Fonts**

- Configured `Montserrat` font from Google Fonts in `styles/global.css`.
- Applied the font globally to all pages.

### **3. Landing Page with Imperative Routing**

- Updated `pages/index.tsx` with buttons that use `useRouter` (imperative routing) to navigate to:  
  - `/generate-text-ai`  
  - `/text-to-image`  
  - `/counter-app`

### **4. Centralized Interfaces**

- Created an `interface/index.ts` file to hold all interfaces (`ButtonProps`, `LayoutProps`, `PageRouteProps`).  
- Updated `Button`, `Layout`, and `index.tsx` to import interfaces from this file.

### **5. Custom 404 Page**

- Added `pages/404.tsx` to override the default Next.js 404 page with a custom error message and a "Go Back Home" button.

---

## **Project Setup**

### **1. Clone the Repository**

```bash
git clone https://github.com/<your-username>/alx-project-0x03-setup.git
cd alx-project-0x03
````

### **2. Install Dependencies**

```bash
npm install
```

### **3. Run the Development Server**

```bash
npm run dev
```

### **4. Access the App**

Visit [http://localhost:3000](http://localhost:3000) to see the app running.

- Unknown routes (e.g. `/random`) will show the **custom 404 page**.
- The landing page buttons will navigate you to placeholder pages or show 404s until they’re implemented.

---

## **Next Steps**

- Add placeholder pages for `/generate-text-ai`, `/text-to-image`, and `/counter-app`.
- Build out functionality for each mini app.

---

## **Tech Stack**

- **Next.js** (React Framework)
- **Tailwind CSS** (Styling)
- **TypeScript**
- **React Icons** (Icons)
- **Google Fonts (Montserrat)**

````markdown

---

### **2. Commit and Push the Update**

```bash
git add README.md
git commit -m "Updated README with setup instructions and features"
git push
````

---

Do you want me to **also add screenshots** (e.g. landing page & custom 404) into the README to make it more visual? Or should I include **badges and a table of contents** to give it a more polished look?
