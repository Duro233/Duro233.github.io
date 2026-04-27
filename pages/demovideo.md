layout: page
title: "Demo Video"
permalink: /pages/demovideo

<h2>Demo</h2>

   <p><strong>Project description:</strong></p>
   <p>Tasked with taking on an imaginative role as a software engineer at a healthcare technology company in Central Florida, I developed a real-time patient monitoring system as a proof-of-concept using an ESP32 and FreeRTOS in Wokwi. The system simulates a wearable or bedside device that continuously monitors a patient’s heart rate and responds to potential medical anomalies in real time.
The system includes multiple concurrent tasks: a high-frequency sensor monitoring task that reads heart rate data, an event response task that triggers alerts when abnormal conditions are detected, a heartbeat task that indicates system health, and a web server task that simulates remote monitoring. A button interrupt (ISR) is also implemented to represent immediate emergency input.
Each task is assigned a specific period and deadline, with critical functions such as sensor monitoring and alert response classified as hard real-time tasks. These tasks must meet strict timing constraints to ensure patient safety—for example, detecting arrhythmias and triggering alerts within 200 ms. Less critical functions, such as status indicators and web updates, are treated as soft real-time tasks.
Synchronization mechanisms (queues, semaphores, and mutexes) are used to coordinate data sharing and ensure deterministic behavior. The system demonstrates reliable scheduling by consistently meeting all hard deadlines, verified through timestamped logs and periodic heartbeat signals.
This prototype reflects real-world healthcare systems such as cardiac monitors or wearable health devices, where timing accuracy is essential and missed deadlines could have serious consequences.</p>

   <p><strong>Application 6 Demo Video:</strong></p>
   <iframe width="560" height="315"
      src="https://www.youtube.com/embed/Y9QWsSdmasw"
      title="Demo Video"
      frameborder="0"
      allowfullscreen>
   </iframe>
