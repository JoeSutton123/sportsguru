layout: page 
title: "F1 Predictions 2023" 
permalink: /predictions/f1-2023

<h1>{{ page.title }}</h1>

<form action="URL_PROVIDED_BY_FORM_SERVICE" method="POST">
    {% for field in site.data.form.fields %}
        <label for="{{ field.id }}">{{ field.label }}:</label>
        <input type="{{ field.type }}" id="{{ field.id }}" name="{{ field.name }}" required><br>
    {% endfor %}

    <button type="submit">Submit</button>
</form>
