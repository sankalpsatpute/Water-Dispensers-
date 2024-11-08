<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    
</head>
<body>

<h1>Water Dispenser Project</h1>

<p><strong>Project Name:</strong> Smart Water Dispenser</p>
<p><strong>Author:</strength>Sankalp Satpute</p>
<p><strong>Description:</strong> This project is an IoT-based smart water dispenser that utilizes Arduino for automation. It measures water levels and dispenses a specific amount of water based on proximity detection, creating a convenient and touchless water dispensing experience.</p>

<h2>Features</h2>
<ul>
    <li><strong>Automatic Water Dispensing:</strong> Detects when a container is placed within range and dispenses water accordingly.</li>
    <li><strong>Water Level Monitoring:</strong> Uses an ultrasonic sensor to ensure water availability.</li>
    <li><strong>Configurable Dispensing Volume:</strong> Easily adjust the amount of water dispensed by modifying a parameter in the code.</li>
    <li><strong>Energy Efficient:</strong> The system activates only when necessary, conserving power.</li>
</ul>

<h2>Components Used</h2>
<ul>
    <li><strong>Arduino UNO:</strong> Microcontroller to control the entire system.</li>
    <li><strong>Ultrasonic Sensor:</strong> Detects proximity to initiate water dispensing.</li>
    <li><strong>Servo Motor:</strong> Controls the water dispensing mechanism.</li>
</ul>

<h2>Getting Started</h2>

<h3>Prerequisites</h3>
<ul>
    <li>Arduino IDE (for uploading code)</li>
    <li>Basic knowledge of Arduino and electronics</li>
</ul>

<h3>Installation</h3>
<ol>
    <li><strong>Clone the repository:</strong>
        <pre><code>git clone https://github.com/sankalp satpute/Water-Dispensers-Project.git</code></pre>
    </li>
    <li><strong>Upload the Code:</strong> Open the Arduino IDE, load the project code, and upload it to your Arduino UNO.</li>
    <li><strong>Circuit Setup:</strong> Connect the ultrasonic sensor and servo motor to the Arduino UNO as specified in the schematic.</li>
</ol>

<h2>Usage</h2>
<ol>
    <li>Place a container under the sensor.</li>
    <li>The sensor detects the object and activates the servo motor to dispense water.</li>
    <li>Adjust the water dispensing time in the code if needed.</li>
</ol>

<h2>Code Explanation</h2>
<ul>
    <li><strong>main.ino:</strong> The main code file, which includes setup, proximity detection, and water dispensing functions.</li>
</ul>

<h2>Future Enhancements</h2>
<ul>
    <li>Add a Wi-Fi or Bluetooth module for remote control and monitoring.</li>
    <li>Integrate a display to show the current water level.</li>
    <li>Implement a mobile app for tracking water usage.</li>
</ul>

<h2>License</h2>
<p>This project is licensed under the MIT License.</p>

</body>
</html>
