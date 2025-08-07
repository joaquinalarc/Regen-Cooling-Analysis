# Regen Cooling Analysis 🔥🚀

Python Simulation of a regenerative cooling wall for rocket engines. Developed as part of the Purdue Space Program (PSP)

## 📌 About the Project

This project is part of my first technical contribution to the **Purdue Space Program - Team Liquids**, focused on modeling **heat transfer** through a regenerative cooling channel in a rocket engine. 

The solver iterative calculates:
- Wall temperature distribution (`T1`, `T2`)
- Thermal resistances (`R1`, `R2`, `R3`)
- Heat flow balance at each axial station

The results are plotted and exported to a CSV file for further engineering analysis and validation.

## 🧠 Features

- Iterative solver using thermal resistance networks
- Temperature-dependent material properties
- CSV and graphical output of temperature profiles
- Implemented in **Python** with `NumPy` and `Matplotlib`

## 📂 Files

- `Regen_solver.py` → Main driver script
- `MATERIAL_PROPERTIES.py` → Material property handler
- `PSPSPdataReal.csv` → Input data per axial station
- `temperature_resistance_output.csv` → Output data file

## 📷 Example Output 

![T1 and T2 Plot](./output_plot.png) <!-- (optional if you include image later) -->

## 🧪 Dependencies

- Python 3.x
- NumPy
- Matplotlib
- CSV module (standard)

You can install dependencies with:
```bash
pip install numpy matplotlib
```

## 🧑‍💻 About me

I'm Joaquin, a freshman at **Purdue University** majoring in Aerospace Engineering. This project was developed to deepen my understanding of rocket dynamics and prepare for research opportunities in propulsion and trajectory modeling 

Feel free to reach out or connect with me on [LinkedIn](https://pe.linkedin.com/in/joaquin-alarcon)

## 📬 Contact:

- 📧 Email: joaq.alrc@outlook.com
- 🌐 Github : [@joaquinalarc](https://github.com/joaquinalarc)
- 📸 Instagram : [@joa.alarcon_](https://www.instagram.com/joa.alarcon_/)

## 💖 Support:

Liked this project? Help me keep building rockets (and maybe buy some coffee too):

☕ [Donate via Paypal](https://www.paypal.me/joaquix96)
