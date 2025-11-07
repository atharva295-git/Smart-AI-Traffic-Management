🧠 Smart AI-Based Traffic Management System

Problem Statement ID: 1607
Title: “A smart AI-based solution for traffic management on routes with heavy traffic from different directions, with real-time monitoring and adaptation of traffic-light timings.”



📖 Project Description

Urban intersections often suffer from heavy congestion because traditional traffic lights use fixed time cycles that do not adapt to real-time traffic. This results in long waiting times, fuel wastage, and higher emissions.

This project provides a smart AI-based adaptive traffic signal system that uses Reinforcement Learning (Q-Learning) to monitor and manage traffic dynamically.
The AI model learns from vehicle flow patterns and adjusts signal durations automatically — reducing waiting time and improving traffic flow efficiency.



🎯 Objective

To develop an intelligent traffic signal controller that:

Observes real-time traffic density from all directions

Learns optimal green light durations dynamically

Reduces total waiting time for vehicles

Enhances throughput and overall traffic movement efficiency



⚙️ How It Works

The intersection has four directions — North, South, East, and West.

Vehicles arrive randomly, simulating real-world inflow.

A Sensor Module (simulated) measures queue length in each lane.

The AI Controller (Q-Learning) decides:

Which direction (NS or EW) should get green

For how long the green signal should stay ON

The system learns over time by receiving rewards for reducing total waiting time.

The trained model demonstrates shorter queues and faster vehicle movement.



🧩 Technologies Used

Python 3.x

Reinforcement Learning (Q-Learning)

Randomized Traffic Simulation (Poisson Distribution)

Collections & Math Libraries for computation



📊 Training and Results

During training, the AI model undergoes multiple simulated episodes to explore and learn the best timing patterns.
Over several iterations, it adapts to minimize congestion and optimize throughput.

Phase		 Average Wait (seconds)	  Vehicles Passed	Observation
Before Training	 ~10 sec		  70–80			Long queues, inefficient flow
After Training	 ~5 sec	90–100	          Reduced wait, 	smoother flow

✅ Result: Nearly 50% improvement in average waiting time and faster traffic clearance.