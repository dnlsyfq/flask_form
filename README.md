### Form 

* HTML
```

```

### Route Selection

```
<a href="/">Index Link</a>
```
```
<a href="{{ url_for('index') }}">Index Link</a>
```

### Form Fields

* TextAreaField
```
my_text_area = TextAreaField("Text Area Label")
```

* BooleanField
```
my_checkbox = BooleanField("Checkbox Label")
```

* RadioField
```
my_radio_group = RadioField("Radio Group Label", choices=[("id1", "One"), ("id2","Two"), ("id3","Three")])
```

### Redirecting

Consider the case where we create our form in one route, but after the form submission we want the user to end up in another route. While we can set the action attribute in the HTML <form> tag go to any path, redirect() is the best option to move from one route to another.



