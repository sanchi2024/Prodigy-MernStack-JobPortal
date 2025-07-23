**Prodigy - MERN STACK JOB PORTAL**
Prodigy is a modern, feature-rich job portal built using the MERN stack (MongoDB, Express.js, React, Node.js).
It offers a seamless experience for both recruiters and job seekers, each with their own dedicated dashboards and workflows.
Whether you're a company looking to post job listings or a candidate searching and applying for opportunities, Prodigy provides the tools and interface to make the process efficient and user-friendly.

**📸 Live Preview: https://prodigy-portal.vercel.app/**

🔑 Key Highlights

👨‍💼 **For Recruiters**
- Post new job openings
- Manage and update job listings
- View and track applicants for each posting
- Personalize company profiles
- Visual analytics on hiring activity

🧑‍💻 **For Applicants**
- Browse and filter jobs by keywords or categories
- Apply to jobs with uploaded resumes
- Manage and monitor application status
- Create and edit applicant profiles

🧩 **Platform Features**
- User authentication powered by Clerk
- File uploads via Cloudinary
- Error tracking integrated with Sentry
- Secure REST API using JWT
- Responsive design using Tailwind CSS

🧱 **Tech Stack**
⚙️ **Frontend**
- React + Vite
- Tailwind CSS for styling
- React Router for navigation
- Axios for API calls
- Chart.js for data visualization

🧪 **Backend**
- Node.js with Express
- MongoDB + Mongoose for database
- JSON Web Tokens (JWT) for auth
- Bcrypt for secure password hashing
- CORS for cross-origin requests
- Svix for webhook handling

🔗 **Integrations**
- Clerk – User Authentication
- Cloudinary – Image & Resume Uploads
- Sentry – Bug/Crash Reporting

**🧾 Installation Steps**
**Clone the repository:**
git clone https://github.com/yourusername/prodigy-job-portal.git
cd prodigy-job-portal

**Install dependencies:**
**Frontend:**
- cd client
- npm install
**Backend:**
- cd server
- npm install

**Environment Configuration:**
Create .env files in both the client/ and server/ folders.
**server/.env**
MONGODB_URI=your_mongodb_uri
CLERK_SECRET_KEY=your_clerk_secret_key
JWT_SECRET=your_jwt_secret
CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret
SENTRY_DSN=your_sentry_dsn
CLERK_WEBHOOK_SECRET=your_svix_webhook_secret
PORT=5000

**client/.env**
VITE_CLERK_PUBLISHABLE_KEY=your_clerk_publishable_key
VITE_API_BASE_URL=http://localhost:5000/api

💻 **Running the App**
**Start the backend server:**
- cd server
- npm run dev/ npm run server
**Start the frontend in a separate terminal:**
- cd client
- npm run dev


