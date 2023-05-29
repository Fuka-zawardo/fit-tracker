# Fit Tracker

Fit Tracker is an application built with Vue.js and Chart.js for tracking your weight over time. It includes a simple form to input new weight data, and presents a line chart showing your weight history over the last 7 days.

## How It Works

1. Data Management: The application maintains a list of weights (each represented by a weight value and a timestamp) and a current weight input in Vue's ref reactive variables. It also maintains a computed list of weights sorted by date.

2. Adding New Data: You can add new weight data by inputting a number into the form and clicking "Add Weight". The application checks that the input is a number before adding it to the list.

3. Updating the Chart: The application uses Vue's watch function to update the line chart whenever the sorted list of weights changes. When this happens, it updates the chart's data and labels to reflect the latest seven weight entries.

## Installation

To install and run this application, follow these steps:

1. Clone the repository:

```bash
git clone https://github.com/Fuka-zawardo/fit-tracker.git
```

2. Navigate into the project directory:

```bash
cd fit-tracker
```

3. Install the dependencies:

```bash
npm install
```

4. Start the project:

```bash
npm run dev
```

## Support

For support or to report issues, please open an issue at https://github.com/Fuka-zawardo/fit-tracker/issues

## Contribution

Contributions are always welcome! Please open a pull request with your changes.
