# 💰 Investment Calculator

A modern, interactive React-based web application that helps users estimate returns on their investments over time. Built with React and Vite, this project showcases practical financial calculations with a clean, responsive user interface.

## 🚀 Features

- 📈 **Real-time ROI Calculation**: Instantly computes estimated return on investment
- 💸 **Flexible Inputs**: Supports principal amount, annual interest rate, investment duration, and regular contributions
- 💡 **Dynamic Updates**: Results update automatically as you adjust parameters
- 🖥️ **Responsive Design**: Works seamlessly on desktop and mobile devices
- 📊 **Clear Visualization**: Well-formatted results with comprehensive breakdown
- ⚡ **Fast Performance**: Built with modern React and optimized with Vite

## 🧱 Tech Stack

- **React 19** - Component-based UI framework
- **Vite** - Fast build tool and development server
- **JavaScript (ES6+)** - Modern JavaScript with hooks and functional components
- **CSS3** - Responsive styling and animations
- **HTML5** - Semantic markup structure

## 📁 Project Structure

```
Investment-Calculator-Project/
├── public/
├── src/
│   ├── components/
│   │   ├── Header.jsx          # App header component
│   │   ├── UserInput.jsx       # Input form component
│   │   └── Results.jsx         # Results display component
│   ├── util/
│   │   └── investment.js       # Investment calculation logic
│   ├── App.jsx                 # Main app component
│   ├── main.jsx                # App entry point
│   ├── index.css               # Global styles
│   └── index.jsx               # React root rendering
├── index.html                  # HTML template
├── package.json                # Dependencies and scripts
├── vite.config.js              # Vite configuration
└── README.md                   # Project documentation
```

## 🛠️ Installation & Setup

### Prerequisites

Ensure you have Node.js (version 16 or higher) and npm installed:

```bash
node --version
npm --version
```

### Run Locally

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/Investment-Calculator-Project.git
   cd Investment-Calculator-Project
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Start the development server**
   ```bash
   npm run dev
   ```

4. **Open your browser**

   Navigate to `http://localhost:5173` to view the application.

### Build for Production

```bash
npm run build
```

The built files will be in the `dist/` directory.

### Preview Production Build

```bash
npm run preview
```

## 💻 How It Works

1. **Initial Investment**: Enter your starting principal amount
2. **Annual Investment**: Specify regular yearly contributions
3. **Expected Return**: Input the annual interest rate (percentage)
4. **Duration**: Set the investment period in years

The calculator will automatically compute and display:
- Year-by-year breakdown of your investment growth
- Total invested amount
- Total interest earned
- Final investment value

## 📈 Future Enhancements

Potential improvements for the project:

- 📊 **Data Visualization**: Add charts to visualize investment growth over time
- 📅 **Flexible Contributions**: Support monthly or quarterly investment options
- 💡 **Interest Types**: Toggle between compound and simple interest calculations
- 📥 **Export Functionality**: Allow users to download results as PDF or CSV
- 🧠 **Investment Tips**: Integrate AI-powered financial advice
- 🌙 **Dark Mode**: Add theme switching capability
- 💾 **Data Persistence**: Save user calculations locally or in the cloud

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. **Fork** the repository
2. **Create** a feature branch (`git checkout -b feature/amazing-feature`)
3. **Commit** your changes (`git commit -m 'Add some amazing feature'`)
4. **Push** to the branch (`git push origin feature/amazing-feature`)
5. **Open** a Pull Request

Please ensure your code follows the existing style and includes appropriate tests.

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.


**Happy Investing!** 📈💰