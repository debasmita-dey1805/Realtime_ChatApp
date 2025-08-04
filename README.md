📣 Real-Time Chat App
This is a real-time chat application built with Python, Django, WebSockets, Django Channels, Redis, and HTMX.
It allows multiple users to send and receive messages in real time — similar to a group chat app.



🚀 Features
🔄 Real-time two-way messaging using WebSockets
🔗 WebSocket handling with Django Channels
⚡ Lightweight frontend interactivity using HTMX
📦 Message broadcasting via Redis as a channel layer
🧑‍🤝‍🧑 Multiple users can chat simultaneously
✨ Scroll-to-bottom animation for new messages
🧼 Clean UI with Tailwind CSS



| Layer         | Tech Used                   |
| ------------- | --------------------------- |
| **Backend**   | Python, Django              |
| **Real-time** | Django Channels, WebSockets |
| **Broker**    | Redis                       |
| **Frontend**  | HTMX, Tailwind CSS          |
| **Template**  | Django Templating Engine    |


⚙️ How to Run Locally
1. Clone the repo
git clone https://github.com/your-username/Realtime_ChatApp.git
cd Realtime_ChatApp


2. Create virtual environment & activate
python -m venv venv
venv\Scripts\activate  # For Windows
source venv/bin/activate  # For Mac/Linux


4. Install dependencies
pip install -r requirements.txt


5. Start Redis server (must be installed)
redis-server


6. Run migrations
python manage.py migrate


7. Run the Django development server
python manage.py runserver


🔧 Requirements
Django==5.2.4
django-allauth==65.9.0
django-browser-reload==1.18.0
django-cleanup==9.0.0
django-htmx==1.23.2
pillow==11.3.0


    

