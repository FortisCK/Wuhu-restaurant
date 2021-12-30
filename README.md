# 部署

1. Setup and activate virtual environment

       cd recipe_manager/
       pip install -r requirements.txt
       python manage.py migrate  # Run migrations

# 使用

    python manage.py runserver

访问 `http://127.0.0.1:8000/recipes/`