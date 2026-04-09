# 🚀 AI-Powered PCB Inspection & Quality Analysis System for Semiconductor Applications

## 📌 Overview

This project is an end-to-end **AI-driven PCB defect detection and quality inspection platform** designed to simulate real-world semiconductor manufacturing workflows.

It integrates **computer vision, full-stack engineering, and system-level analytics** to automate PCB inspection, analyze defect severity, and generate actionable quality reports.

---

## 🎯 Key Features

* 🔍 **Automated Defect Detection** using YOLOv8
* 🧠 **Precise Segmentation** with SAM (Segment Anything Model)
* 📊 **Interactive Dashboard** for inspection analytics
* 📦 **Batch Processing** for large-scale PCB testing
* ⚡ **Real-Time Monitoring** with WebSockets
* 📄 **Automated Quality Reports** (Pass/Fail + defect insights)

---

## 🏗️ System Architecture

```bash
System/
├── frontend/        # Next.js dashboard
├── backend/         # FastAPI APIs
├── detection/       # YOLOv8 model
├── segmentation/    # SAM model
├── analytics/       # defect analysis engine
├── database/        # PostgreSQL / MongoDB
├── realtime/        # WebSockets
└── reports/         # PDF report generation
```

---

## ⚙️ Tech Stack

**AI / ML:**
Python, YOLOv8, SAM, OpenCV

**Backend:**
FastAPI, REST APIs

**Frontend:**
Next.js, React, Tailwind CSS

**Database:**
PostgreSQL / MongoDB

**Real-Time:**
WebSockets

**DevOps:**
Docker, AWS

---

## 🔬 How It Works

1. Upload PCB image via dashboard
2. YOLOv8 detects defect regions
3. SAM segments defects for precise localization
4. Analytics engine calculates defect severity
5. System generates:

   * Visual output
   * Defect insights
   * Pass/Fail decision

---

## 📊 Example Outputs

* Defect classification (missing hole, short, open circuit)
* Severity score based on defect size/area
* Automated inspection report

---

## 🚀 Getting Started

### 1. Clone Repository

```bash
git clone https://github.com/your-username/pcb-inspection-system.git
cd pcb-inspection-system
```

### 2. Setup Backend

```bash
cd backend
pip install -r requirements.txt
uvicorn main:app --reload
```

### 3. Setup Frontend

```bash
cd frontend
npm install
npm run dev
```

---

## 🧪 Future Enhancements

* 📡 Signal integrity analysis (defect → performance impact)
* 🧠 Failure prediction using historical inspection data
* 🏭 Integration with real hardware testing systems
* 📈 Advanced analytics & trend prediction

---

## 🎯 Use Cases

* Semiconductor manufacturing quality control
* PCB inspection automation
* Industrial defect detection systems
* Research & development in AI-based inspection

---

## 👨‍💻 Author

* 🔗 LinkedIn: https://www.linkedin.com/in/me-akash77/
* 💻 GitHub: https://github.com/MeAkash77

---

## ⭐ If you found this useful

Give it a ⭐ on GitHub and feel free to contribute


PCB Defect Detector is a web application designed to analyze and detect defects in printed circuit boards (PCBs). The application leverages modern web technologies and tools to provide an intuitive interface for uploading, analyzing, and visualizing PCB defects. It also includes features for batch processing, dashboard analytics, and explainable AI insights.

## Features

- **User Authentication**: Secure login and signup functionality.
- **File Upload**: Upload PCB images for analysis.
- **Defect Detection**: Analyze PCBs for defects using advanced algorithms.
- **Batch Processing**: Upload and process multiple PCB images at once.
- **Dashboard**: View analytics and recent scans.
- **Explainable AI**: Understand the reasoning behind defect detection.
- **Repair Suggestions**: Get actionable suggestions for repairing detected defects.
- **Responsive Design**: Optimized for both desktop and mobile devices.

## Tech Stack

- **Frontend**: React, Next.js, Tailwind CSS
- **Backend**: Next.js API routes, Prisma ORM
- **Database**: SQLite (development), Prisma migrations
- **Authentication**: bcryptjs for password hashing
- **UI Components**: Radix UI, Tailwind CSS
- **Visualization**: Recharts, Embla Carousel

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/MeAkash77/AI-Powered-PCB-Inspection-Quality-Analysis-System-for-Semiconductor-Applications.git
   cd pcb-defect-detector
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Set up the database:
   ```bash
   npm run migrate
   ```

4. Start the development server:
   ```bash
   npm run dev
   ```

5. Open your browser and navigate to `http://localhost:3000`.

## Scripts

- `npm run dev`: Start the development server.
- `npm run build`: Build the application for production.
- `npm run start`: Start the production server.
- `npm run lint`: Run linting checks.
- `npm run migrate`: Apply database migrations.
- `npm run generate`: Generate Prisma client.
- `npm run studio`: Open Prisma Studio.
- `npm run reset`: Reset the database.

## Folder Structure

- **app/**: Contains the main application pages and API routes.
- **components/**: Reusable UI components.
- **hooks/**: Custom React hooks.
- **lib/**: Utility functions and Prisma setup.
- **prisma/**: Database schema and migrations.
- **public/**: Static assets like images and icons.
- **styles/**: Global CSS styles.

## Contributing

Contributions are welcome! If you'd like to contribute, please fork the repository and submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgments

- [Radix UI](https://www.radix-ui.com/) for accessible UI components.
- [Prisma](https://www.prisma.io/) for database management.
- [Tailwind CSS](https://tailwindcss.com/) for styling.
- [Next.js](https://nextjs.org/) for the React framework.

---

Feel free to reach out if you have any questions or feedback!
