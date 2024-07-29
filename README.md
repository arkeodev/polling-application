# Online Voting System

This project is an **Online Voting System** built using the Django framework. It provides a platform for users to participate in polls and cast their votes securely and efficiently.

## Installation

### Prerequisites

- Python 3.x
- Django 3.x
- Poetry (for dependency management)

### Steps

1. **Clone the repository:**

   ```bash
   git clone https://github.com/yourusername/online-voting-system.git
   cd online-voting-system
   ```

2. **Install dependencies:**

   Use Poetry to install the project dependencies.

   ```bash
   poetry install
   ```

3. **Apply migrations:**

   Run the following command to apply the database migrations.

   ```bash
   python manage.py migrate
   ```

4. **Run the development server:**

   Start the Django development server using the command below.

   ```bash
   python manage.py runserver
   ```

   The application will be accessible at `http://127.0.0.1:8000/`.

## Usage

### Admin Interface

To manage polls and votes, you can access the Django admin interface at `http://127.0.0.1:8000/admin/`. You will need to create a superuser account if you haven't already:

```bash
python manage.py createsuperuser
```

### Creating Polls

1. Log in to the admin interface.
2. Navigate to the "Polls" section.
3. Add a new poll by providing the necessary details.
4. Save the poll and share the link with users for voting.

### Voting

Users can participate in active polls by visiting the poll URLs. They can select their choice and submit their vote.

## Testing

To run the tests for the application, use the following command:

```bash
python manage.py test pollApp
```
