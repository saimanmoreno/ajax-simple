 # AJAX Simple

This is a simple AJAX example that uses a button to send a request to a PHP script, which returns a message. The message is then displayed on the page.

## Prerequisites

To run this example, you will need:

* A web server with PHP support
* The `XMLHttpRequest` object (included in all modern browsers)

## Step 1: Create the HTML file

The HTML file contains the following elements:

* A button that triggers the AJAX request
* A heading that will display the message returned from the PHP script

## Step 2: Create the PHP script

The PHP script does the following:

* Receives the username from the AJAX request
* Queries the database for the user's message
* Returns the message to the AJAX request

```php
<?php

// Get the username from the AJAX request
$username = $_POST['username'];



Generated by [BlackboxAI](https://www.blackbox.ai)