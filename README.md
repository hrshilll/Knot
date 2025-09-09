
🎓 Knot – Alumni Management System

Knot is a full-stack web application designed for educational institutions to centralize alumni data, enhance engagement, and foster long-term connections between alumni, students, and administrators.

Built with scalability, security, and future integration in mind, Knot ensures seamless alumni engagement, career growth, and institutional support.

🚀 Features
	•	👤 Alumni Profiles & Authentication – Secure login with role-based access.
	•	🎉 Event Management – Create, manage, and track RSVPs & participation.
	•	🤝 Mentorship & Internship Hub – Connect alumni with students for career growth.
	•	📢 Communication Tools – Announcements, newsletters, and updates.
	•	💳 Fundraising & Donations – Secure payment gateway integration.
	•	🤖 AI-Powered Recommendations – Smart suggestions for mentors, events, and opportunities.
	•	🌐 Networking Features – Discussion groups, job boards, and collaboration spaces.

🛠️ Tech Stack
	•	Frontend: React.js, Next.js, Tailwind CSS, HTML5, JavaScript
	•	Backend: Django, Node.js, Express.js, REST APIs
	•	Database: PostgreSQL, MySQL, Supabase
	•	Authentication & Security: Clerk, JWT, Encryption
	•	APIs & Integrations: LinkedIn API, GitHub API, Gmail, Twitter
	•	Payments: Razorpay
	•	Hosting & Deployment: Vercel, Render, Neon.tech, GitHub

🧑‍💻 Setup Instructions
	1.	Clone the Repository

git clone https://github.com/hrshilll/Knot.git
cd Knot

	2.	Frontend Setup (React/Next.js)

cd frontend
npm install
npm run dev

	3.	Backend Setup (Django / Node.js)

# For Django
cd backend-django
python3 -m venv env
source env/bin/activate
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver

# For Node.js
cd backend-node
npm install
npm start

Live on : https://knot-nu.vercel.app/
