# 🌤️ IntelliWeather

> An intelligent weather analysis app that turns real-time weather data into professional reports — built in Python, runs in Google Colab.

---

## What it does

| Feature | Description |
|--------|-------------|
| Live weather | Fetches current conditions for any city in the world |
| 5-day forecast | Temperature highs, lows, precipitation and conditions |
| Charts | Temperature range and precipitation bar charts |
| PDF report | Professional report with all data and charts embedded |
| CSV export | Raw forecast data saved as a spreadsheet |
| Notifications | Alert when your report is ready |

---

## Built with

![Python](https://img.shields.io/badge/Python-3.10+-blue?style=flat-square&logo=python)
![Colab](https://img.shields.io/badge/Google_Colab-F9AB00?style=flat-square&logo=googlecolab&logoColor=white)
![OpenWeatherMap](https://img.shields.io/badge/OpenWeatherMap_API-orange?style=flat-square)
![ReportLab](https://img.shields.io/badge/ReportLab-PDF-red?style=flat-square)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas)
![Matplotlib](https://img.shields.io/badge/Matplotlib-charts-green?style=flat-square)

---

## How to run it

**Step 1** — Open `IntelliWeather.ipynb` in Google Colab

**Step 2** — Get an API key from [openweathermap.org](https://openweathermap.org)

**Step 3** — Paste your key in Cell 0

```python
os.environ["OWM_API_KEY"] = "your-key-here"
```

**Step 4** — Run all cells in order from top to bottom

**Step 5** — When Cell 10 runs, enter any city and ask a question

```
Enter a city: London
Ask a question (or press Enter to skip): Will it rain tomorrow in London?
```

**Step 6** — Your PDF report downloads automatically

---

## Example questions

```
Will it rain tomorrow in Tokyo?
What is the temperature in Dubai?
Is it sunny in Cape Town?
Will it snow in Moscow?
```

---

## Sample output

📄 See the [`sample_output`](./sample_output/) folder for an example PDF report.

---

## Project structure

```
IntelliWeather/
├── IntelliWeather.ipynb       # main notebook
├── README.md                  # this file
└── sample_output/
    └── sample_report.pdf      # example PDF output
```

---

## Author

Built as a portfolio project demonstrating:
- REST API integration
- Data visualisation with Matplotlib
- Automated PDF report generation
- Clean, modular Python code

---

*Data provided by [OpenWeatherMap](https://openweathermap.org)*
