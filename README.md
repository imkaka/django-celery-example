### Django Celery - RabbitMQ Example

* Add and Monitor the job.
* Task is nothing but random `time.sleep()`.


#### Setup and Run

* Install `RabbitMQ` and `pip install -r requirements.txt`
* Activate Celery workers in root directory
    * `celery -A AsyncDjangoApp worker -l info`
* Run the application
    * `python manage.py runserver`
* Visit `localhost:8000/run`.
