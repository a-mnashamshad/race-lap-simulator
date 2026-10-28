QuantumLap-Sim

An open-source Python simulation repository bridging theoretical quantum mechanics and vehicle dynamics to calculate optimal Formula 1 racing lines, braking limits, and energy deployment strategies.

Developed as a 40-hour summer independent research project, QuantumLap-Sim models tire-grip degradation as quantum potential barriers and uses stochastic quantum optimization to solve high-dimensional trajectory problems, validating all simulated convergence against real-world F1 telemetry data.

---

Core Physics & Quantum Model

Instead of relying solely on classical deterministic physics, this project translates vehicle dynamics into a quantum optimization framework:

Tire-Grip Degradation as Potential Barriers: Thermal wear, graining, and grip decay over a lap are modeled as stochastic quantum potential barriers. The probability of a tire maintaining mechanical grip through high speed maneuvers is evaluated using quantum tunneling dynamics:
  


* **QUBO Optimization:** Trajectories, braking points, and ERS battery deployment are encoded into a Quadratic Unconstrained Binary Optimization (QUBO) problem solved via QAOA/VQE circuits.

---

 Features

* **FastF1 Integration:** Fetches real speed traces, throttle/brake inputs, and GPS telemetry directly from modern F1 race weekends for baseline comparisons.
* **3-DoF Vehicle Dynamics:** Integrates speed-dependent aerodynamic downforce, lateral/longitudinal acceleration limits, and braking stability curves.
* **Stochastic Convergence Engine:** Compares quantum trajectory output against real driver telemetry to benchmark lap-time deltas and theoretical limits.

---

##  Tech Stack

* **Language:** Python 3.10+
* **Quantum Modeling:** Qiskit / PennyLane
* **Telemetry & Data:** FastF1 API, Pandas
* **Physics & Math:** NumPy, SciPy
* **Visualization:** Matplotlib

---

