# Sales Intelligence Dashboard 🚀

A highly interactive, modern, and visually stunning Sales Analysis Dashboard built with React, Tailwind CSS, Framer Motion, and Recharts. Designed to portfolio-worthy standards for data analysts targeting international positions.

![Dashboard Preview](https://img.shields.io/badge/React-18.2.0-61dafb?style=flat&logo=react)
![Tailwind CSS](https://img.shields.io/badge/Tailwind-3.4.0-06b6d4?style=flat&logo=tailwindcss)
![TypeScript](https://img.shields.io/badge/Built%20with-JavaScript-f7df1e?style=flat&logo=javascript)

## ✨ Features

### 🎨 UI/UX Design
- **Dark Mode Default** with glassmorphism and neumorphism elements
- **Premium Look** inspired by Apple + Stripe dashboards
- **Fully Responsive** - works beautifully on mobile and desktop
- **Smooth Micro-interactions** and hover effects throughout
- **Animated Transitions** between charts and filters
- **Skeleton Loaders** for better loading experience

### 📊 Dashboard Components

#### 1. **Header Section**
- Dashboard title with animated logo
- Interactive date range picker
- Region selector dropdown
- Light/Dark theme toggle
- User avatar placeholder

#### 2. **KPI Cards (Animated)**
- Total Revenue with animated counters
- Total Orders
- Total Profit
- Growth Percentage
- Subtle hover effects and gradient backgrounds

#### 3. **Interactive Charts**
- **Line/Area Chart** - Sales trend over time with toggle between views
- **Bar Chart** - Revenue by product category
- **Donut Chart** - Market share by region
- **Heatmap** - Sales intensity by region and category
- Custom tooltips with detailed insights on hover
- Dynamic dataset toggling

#### 4. **Advanced Filters Panel**
- Region filter
- Product Category filter
- Customer Segment filter
- Custom date range picker
- Smooth animated transitions on apply

#### 5. **Data Table**
- Fully sortable columns
- Real-time search functionality
- Pagination with smart page numbers
- Top-performing products highlighted with star icons
- Category badges with color coding

#### 6. **AI Insights Panel**
- Dynamic insights based on filtered data
- Growth analysis
- Top category identification
- Regional performance highlights
- Profit margin analysis
- Best-selling product identification

### 🛠️ Advanced Features
- **Export to CSV** - Download filtered data
- **Export to PDF** - Capture entire dashboard
- **Theme Customization** - Toggle between dark and light modes
- **Real-time Simulation** - Data updates every 10 seconds
- **Loading States** - Beautiful skeleton loaders
- **Smooth Page Transitions** - Framer Motion animations

## 🚀 Getting Started

### Prerequisites
- Node.js (v14 or higher)
- npm or yarn

### Installation

1. **Clone or navigate to the project directory**
   ```bash
   cd sales-dashboard
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
   - Navigate to `http://localhost:5173` (or the port shown in terminal)
   - The dashboard will load with simulated data

### Build for Production

```bash
npm run build
```

The optimized production build will be in the `dist/` folder.

### Preview Production Build

```bash
npm run preview
```

## 📁 Project Structure

```
sales-dashboard/
├── src/
│   ├── components/
│   │   ├── charts/
│   │   │   ├── SalesTrendChart.jsx       # Line/Area chart
│   │   │   ├── RevenueByCategoryChart.jsx # Bar chart
│   │   │   ├── MarketShareChart.jsx       # Donut chart
│   │   │   └── SalesHeatmap.jsx           # Heatmap
│   │   ├── AnimatedCounter.jsx           # Animated number counter
│   │   ├── DataTable.jsx                 # Sortable data table
│   │   ├── FiltersPanel.jsx              # Advanced filters
│   │   ├── Header.jsx                    # Dashboard header
│   │   ├── InsightsPanel.jsx             # AI insights
│   │   ├── KPICard.jsx                   # KPI cards
│   │   └── SkeletonLoader.jsx            # Loading states
│   ├── data/
│   │   └── mockData.js                   # Data generation utilities
│   ├── utils/
│   │   └── exportUtils.js                # CSV/PDF export
│   ├── App.jsx                           # Main app component
│   ├── main.jsx                          # Entry point
│   └── index.css                         # Global styles
├── index.html                            # HTML template
├── vite.config.js                        # Vite configuration
├── package.json                          # Dependencies
└── README.md                             # This file
```

## 🎯 Tech Stack

- **React 18** - Modern UI library with hooks
- **Vite** - Fast build tool and dev server
- **Tailwind CSS** - Utility-first CSS framework
- **Framer Motion** - Smooth animations and transitions
- **Recharts** - Composable charting library
- **Lucide React** - Beautiful icon library
- **date-fns** - Date manipulation utilities
- **html2canvas** - Screenshot capture for PDF export
- **jsPDF** - PDF generation

## 🎨 Design Philosophy

### Glassmorphism
```css
background: rgba(17, 24, 39, 0.7);
backdrop-filter: blur(12px);
border: 1px solid rgba(255, 255, 255, 0.1);
```

### Color Palette
- **Primary**: Indigo (#6366f1) to Purple (#8b5cf6)
- **Success**: Green (#10b981)
- **Warning**: Amber (#f59e0b)
- **Danger**: Red (#ef4444)

### Typography
- **Font Family**: Inter (Google Fonts)
- **Weights**: 300, 400, 500, 600, 700

## 📊 Mock Data

The dashboard generates 1,000 realistic sales records including:
- Date (last 365 days)
- 5 Regions (North America, Europe, Asia Pacific, Latin America, Middle East)
- 6 Product Categories (Electronics, Clothing, Home & Garden, Sports, Books, Toys)
- 30 Products across categories
- 5 Customer Segments (Enterprise, SMB, Consumer, Government, Education)
- Revenue, Profit, Quantity, Unit Price

## 🔧 Customization

### Adding New Charts
1. Create a new component in `src/components/charts/`
2. Use Recharts components
3. Import and add to `App.jsx`

### Modifying Colors
Update CSS variables in `src/index.css`:
```css
:root {
  --accent: #6366f1;
  --success: #10b981;
  /* ... */
}
```

### Adding More Data
Modify `generateSalesData()` in `src/data/mockData.js`

## 🌟 Key Highlights for Portfolio

✅ **Production-Ready Code**
- Clean, modular component architecture
- Proper state management with React hooks
- Reusable components with props
- Comprehensive error handling

✅ **Modern UI/UX**
- Glassmorphism design trend
- Smooth animations (Framer Motion)
- Responsive grid layouts
- Micro-interactions on every element

✅ **Data Visualization**
- Multiple chart types (Line, Bar, Pie, Heatmap)
- Custom tooltips
- Interactive legends
- Dynamic data filtering

✅ **Advanced Features**
- Real-time data simulation
- Export functionality (CSV, PDF)
- Theme switching
- Skeleton loading states

✅ **Performance Optimized**
- useMemo for expensive calculations
- Lazy loading ready
- Optimized re-renders
- Efficient data aggregation

## 📱 Responsive Breakpoints

- **Mobile**: < 640px
- **Tablet**: 640px - 1024px
- **Desktop**: > 1024px

## 🤝 Contributing

Feel free to fork this project and submit pull requests for improvements!

## 📄 License

MIT License - Feel free to use this project for your portfolio or learning.

## 🎓 Learning Resources

- [React Documentation](https://react.dev/)
- [Tailwind CSS Docs](https://tailwindcss.com/)
- [Framer Motion](https://www.framer.com/motion/)
- [Recharts Examples](https://recharts.org/en-US/examples)

## 💡 Tips for Data Analysts

1. **Customize the insights** to match your domain expertise
2. **Add real API integration** to showcase backend skills
3. **Implement authentication** for full-stack demonstration
4. **Add unit tests** to show engineering rigor
5. **Deploy to Vercel/Netlify** for live portfolio link

---

**Built with ❤️ for aspiring data analysts targeting international opportunities**

*This dashboard demonstrates Japan-level quality in frontend development and data visualization.*
