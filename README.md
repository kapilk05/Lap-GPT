# Formula 1 Race Strategy Optimization

## Introduction
This project aims to develop a genetic algorithm for optimizing race strategies in Formula 1. The algorithm takes into account multiple factors such as weather conditions, tire compounds, pit stops, fuel load, and tire degradation to simulate and determine the optimal race strategy for a given circuit.

## Project Structure
- `datasets/`: Directory containing data sets used for training and testing.
- `Lapgpt.ipynb`: Jupyter notebook with the main code and analysis.
- `README.md`: This README file.

## Installation
To get started with this project, follow these steps:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/Formula1-Race-Strategy-Optimization.git
   cd Formula1-Race-Strategy-Optimization
   ```

2. **Set up a virtual environment (optional but recommended):**
   ```bash
   python -m venv env
   source env/bin/activate   # On Windows, use `env\Scripts\activate`
   ```

3. **Install the required dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

## Usage
To run the project and experiment with different race strategies, follow these steps:

1. **Open the Jupyter notebook:**
   ```bash
   jupyter notebook Lapgpt.ipynb
   ```

2. **Run the notebook cells to execute the code and see the results.**

3. **Push changes to the repository:**
   If you make any changes and want to push them to the remote repository, use:
   ```bash
   git add .
   git commit -m "Your commit message"
   git push origin main
   ```

## Proposed Methodology
Based on the literature survey, our project will focus on:
1. Developing a genetic algorithm for race strategy optimization.

### Literature Survey Highlights:
- **Evolutionary F1 Race Strategy**: Tailor-made genetic algorithm using data from free practice sessions.
- **Data-Driven Analysis**: Identifying key factors influencing the overall points tally.
- **Online Planning for Strategy Identification**: Combining Monte Carlo sampling with TD learning for pit stop timings.
- **Optimizing Pit Stops**: Using Dynamic Programming in a two-player zero-sum game.
- **Poisson Analysis**: Developing predictive models for pit stop occurrences.
- **Virtual Strategy Engineer**: AI system for making race strategy decisions using historical race data.
- **Rank Position Forecasting**: Predictive models for rank positions using deep learning.


## Contributing
If you wish to contribute to this project, please follow these steps:

1. Fork the repository.
2. Create a new branch: `git checkout -b feature-branch`.
3. Make your changes and commit them: `git commit -m 'Add new feature'`.
4. Push to the branch: `git push origin feature-branch`.
5. Create a pull request detailing your changes.

## Contact
For any inquiries or feedback, please reach out to:
- **Kapil Kashyap** - kapilkashyap3105@gmail.com
```
