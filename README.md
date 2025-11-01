# GreenHabit - Sustainable Living Tracker

A Django web application that helps users track environmental goals, build eco-friendly habits, and connect with a community committed to sustainable living.

## Features

- **Goal Tracking**: Set, track, and achieve environmental goals
- **Community Interaction**: Like and comment on goals from other users
- **Blog System**: Create and read sustainability-focused blog posts
- **User Profiles**: Personalized profiles with eco-scores
- **Categories**: Organize goals by waste reduction, energy saving, transportation, and food
- **Responsive Design**: Modern, mobile-friendly interface

## Getting Started

### Prerequisites
- Python 3.8+
- Django 5.2+

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/JavithHussainShareef/greenhabit-project.git
   cd greenhabit-project
   ```

2. **Install Django**
   ```bash
   pip install django
   ```

3. **Apply migrations**
   ```bash
   python manage.py migrate
   ```

4. **Create superuser (optional)**
   ```bash
   python manage.py createsuperuser
   ```

5. **Run the development server**
   ```bash
   python manage.py runserver
   ```

6. **Access the application**
   - Main site: http://127.0.0.1:8000/
   - Admin panel: http://127.0.0.1:8000/admin/

## 📱 Pages & Features

- **Home**: Professional landing page with features overview
- **Goals**: Browse and interact with community goals
- **My Goals**: Manage your personal environmental goals
- **Blog**: Read and create sustainability blog posts
- **Profile**: User profile management
- **About**: Learn about the GreenHabit mission

## 🛠️ Technology Stack

- **Backend**: Django 5.2
- **Frontend**: Bootstrap 5, HTML5, CSS3, JavaScript
- **Database**: SQLite (development)
- **Authentication**: Django built-in auth system

## 📁 Project Structure

```
greenhabit-project/
├── greenhabit/          # Django project settings
├── tracker/             # Main application
│   ├── templates/       # HTML templates
│   ├── models.py        # Database models
│   ├── views.py         # View functions
│   ├── forms.py         # Django forms
│   └── urls.py          # URL patterns
├── media/               # User uploaded files
├── manage.py            # Django management script
└── README.md
```

## Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Submit a pull request

## License

This project is open source and available under the [MIT License](LICENSE).

## About

GreenHabit empowers individuals to create lasting environmental impact through sustainable habits. Join our community and start your green journey today!
