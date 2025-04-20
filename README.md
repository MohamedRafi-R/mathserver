# Ex.05 Design a Website for Server Side Processing
# Date:12-4-2025
# AIM:
To design a website to calculate the power of a lamp filament in an incandescent bulb in the server side.

# FORMULA:
P = I2R
P --> Power (in watts)
 I --> Intensity
 R --> Resistance

# DESIGN STEPS:
## Step 1:
Clone the repository from GitHub.

## Step 2:
Create Django Admin project.

## Step 3:
Create a New App under the Django Admin project.

## Step 4:
Create python programs for views and urls to perform server side processing.

## Step 5:
Create a HTML file to implement form based input and output.

## Step 6:
Publish the website in the given URL.

# PROGRAM :
```
<html>
<head>
    <title>Calculate</title>
</head>
<body>
    <h1 align="center">Calculating Power of a Lamp</h1>
    <form action="{% url 'home' %}" method='post'>
        {% csrf_token %}

        intensity:
        <input type="text" name="intensity-input"><br>

        resistance:
        <input type="text" name="resistance-input"><br>

        <button type="submit">Calculate</button>
        <p align="center">The power of the lamp is: {{ output }}</p>
    </form>
</body>
</html>
```

# SERVER SIDE PROCESSING:
![WhatsApp Image 2025-04-12 at 21 43 59_c7a9e137](https://github.com/user-attachments/assets/307d05fe-78cb-4355-ab19-5cba97b8ddd1)

# HOMEPAGE:
![WhatsApp Image 2025-04-12 at 21 43 59_ca455a82](https://github.com/user-attachments/assets/21b5de58-4cb4-44c7-8282-0af86f933026)

# RESULT:
The program for performing server side processing is completed successfully.
