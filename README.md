# Prit Khatri

I'm an M.Sc. physics student at Ruhr-Universität Bochum. My background is computational
plasma physics, and most of what I build is in Python: neural networks trained on simulation
data, numerical solvers, and data pipelines with a proper evaluation.

I'm looking for a Werkstudent job in machine learning, data science or AI engineering,
in the Ruhr area or remote.

## Projects

**[smard-load-forecast](https://github.com/pritkhatri/smard-load-forecast)**
Next-day forecast of hourly electricity demand for the Amprion grid area, from public SMARD
data. The forecast only uses data available at 12:00 the day before, and a test checks that.
LightGBM and a small PyTorch MLP are compared with simple baselines over several
cross-validation folds and a held-out test period. It runs as a FastAPI service in Docker,
with tests in GitHub Actions. On the 2026 test period the error is 11 to 19% lower than
"same hour last week". The README also says where it fails.

**[twostream-dispersion](https://github.com/pritkhatri/twostream-dispersion)**
A solver for the two-stream instability in a plasma: growth rates from a cold fluid model and
a warm kinetic model, tested against analytic results.

## Skills

- Python: NumPy, pandas, SciPy, scikit-learn, PyTorch, LightGBM, Matplotlib
- Tools: Git, GitHub Actions, Docker, FastAPI, MLflow, Linux, LaTeX
- Also C++
- Languages: English (C1), German (B2)

## Contact

[LinkedIn](https://www.linkedin.com/in/prit-khatri)
