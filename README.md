# Airline-Information-System
The Airline Information System is a software application designed to manage and organize airline-related information efficiently. It maintains details such as flight schedules, airline routes, passenger information, and booking status in a structured manner. The system helps reduce manual work and improves accuracy in handling airline data.<!DOCTYPE html><html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Airline Information System</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background: linear-gradient(to right, #1e3c72, #2a5298);
            margin: 0;
            padding: 0;
            color: #fff;
        }
        header {
            background-color: rgba(0,0,0,0.4);
            padding: 20px;
            text-align: center;
        }
        header h1 {
            margin: 0;
        }
        .container {
            width: 90%;
            max-width: 900px;
            margin: 30px auto;
            background: #ffffff;
            color: #000;
            padding: 20px;
            border-radius: 10px;
        }
        h2 {
            text-align: center;
            color: #1e3c72;
        }
        label {
            display: block;
            margin-top: 10px;
        }
        input, select {
            width: 100%;
            padding: 8px;
            margin-top: 5px;
        }
        button {
            margin-top: 15px;
            padding: 10px;
            width: 100%;
            background-color: #1e3c72;
            color: white;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }
        button:hover {
            background-color: #16325c;
        }
        table {
            width: 100%;
            border-collapse: collapse;
            margin-top: 20px;
        }
        table, th, td {
            border: 1px solid #999;
        }
        th, td {
            padding: 10px;
            text-align: center;
        }
        footer {
            text-align: center;
            padding: 15px;
            background-color: rgba(0,0,0,0.4);
            margin-top: 30px;
        }
    </style>
</head>
<body><header>
    <h1>Airline Information System</h1>
    <p>Simple Mini Project using HTML, CSS and JavaScript</p>
</header><div class="container">
    <h2>Flight Booking Form</h2>
    <label>Passenger Name</label>
    <input type="text" id="name" placeholder="Enter passenger name"><label>Source</label>
<input type="text" id="source" placeholder="From">

<label>Destination</label>
<input type="text" id="destination" placeholder="To">

<label>Date of Travel</label>
<input type="date" id="date">

<label>Class</label>
<select id="classType">
    <option>Economy</option>
    <option>Business</option>
    <option>First Class</option>
</select>

<button onclick="bookFlight()">Book Flight</button>

<h2>Booked Flight Details</h2>
<table>
    <
