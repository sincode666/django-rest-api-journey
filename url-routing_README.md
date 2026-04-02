## Overview
URL routing connects endpoints to views.

## Example

```python
from django.urls import path
from .views import student_view

urlpatterns = [          this is the funtion will be called when the endpoint get's hit.
    path('students/', student_view),
           this is the endpoin to trigger the funtion.
]

like this after app is created then the url of name_app and the app_url is given, that the project can understand from where it should access the app urls.
like this: path and include should be included.
path('api/', include('students.urls'))