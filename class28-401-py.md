# Forms in Django
- why forms? 
Forms are a flexible mechanism for collecting user input because there are suitable widgets for entering many different types of data, including text boxes, checkboxes, radio buttons, date pickers and so on.
Forms are also a relatively secure way of sharing data with the server, as they allow us to send data in POST requests with cross-site request forgery protection.

- example of a form?

in Django admin site (snacks adding)

- Django form handling process

![process](https://developer.mozilla.org/en-US/docs/Learn/Server-side/Django/Forms/form_handling_-_standard.png)

- importing

> from django import forms

> class RenewBookForm(forms.Form):


- ModelForms

> from django.forms import ModelForm


