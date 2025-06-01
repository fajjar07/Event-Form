# Event-Form 
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Event Registration Form</title>
  <link
    href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css"
    rel="stylesheet"
  />
  <style>
    body {
      background-color: #f8f9fa;
    }
    .form-container {
      max-width: 700px;
      margin: 50px auto;
      padding: 30px;
      background-color: white;
      border-radius: 10px;
      box-shadow: 0px 0px 15px rgba(0, 0, 0, 0.1);
    }
  </style>
  </head>
<body>
  <div class="container form-container">
    <h2 class="mb-4 text-center">Event Registration Form</h2>
    <form class="needs-validation" novalidate>

      <!-- Full Name -->
      <div class="mb-3">
        <label for="fullName" class="form-label">Full Name</label>
        <input type="text" class="form-control" id="fullName" required />
        <div class="invalid-feedback">Please enter your full name.</div>
      </div>

      <!-- Email -->
      <div class="mb-3">
        <label for="email" class="form-label">Email Address</label>
        <input type="email" class="form-control" id="email" required />
        <div class="invalid-feedback">Please enter a valid email address.</div>
      </div>

      <!-- Phone Number -->
      <div class="mb-3">
        <label for="phone" class="form-label">Phone Number</label>
        <input type="tel" class="form-control" id="phone" pattern="\d{10}" required />
        <div class="invalid-feedback">Please enter a 10-digit phone number.</div>
      </div>

      <!-- Password -->
      <div class="mb-3">
        <label for="password" class="form-label">Password</label>
        <input type="password" class="form-control" id="password" required minlength="6" />
        <div class="invalid-feedback">Password must be at least 6 characters.</div>
      </div>

      <!-- Confirm Password -->
      <div class="mb-3">
        <label for="confirmPassword" class="form-label">Confirm Password</label>
        <input type="password" class="form-control" id="confirmPassword" required />
        <div class="invalid-feedback">Passwords do not match.</div>
      </div>


