# Finance.

> **The most powerful financial AI assistant** - Access institutional-grade financial data, run complex code analyses, and create stunning visualizations. The backend? 1 search api.

## Key Features

### 🔥 Powerful Financial Tools

- **SEC Filings Analysis** - Deep dive into 10-Ks, 10-Qs, 8-Ks, and more
- **Market Data** - Real-time and historical stock prices, volumes, and technical indicators  
- **Financial Statements** - Income statements, balance sheets, cash flows with automatic calculations
- **Insider Trading** - Track institutional and insider transactions
- **Academic Research** - Access to arXiv papers and financial research
- **News & Sentiment** - Real-time news analysis with market impact assessment

### 🛠️ Advanced Tool Calling

- **Python Code Execution** - Run complex financial models, ML algorithms, and custom analyses
- **Interactive Charts** - Create publication-ready visualizations
- **Multi-Source Research** - Automatically aggregates data from multiple sources
- **Export & Share** - Download results, share analyses, and collaborate

## 🚀 Quick Start

### Prerequisites

- Node.js 18+ 
- npm or yarn
- OpenAI API key
- Valyu API key (get one at [valyu.network](https://valyu.network))
- Daytona API key (for code execution)

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/anujgoenka9/
   cd 
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Set up environment variables**
   
   Create a `.env.local` file in the root directory:
   ```env
   # OpenAI Configuration
   OPENAI_API_KEY=your-openai-api-key
   
   # Valyu API Configuration
   VALYU_API_KEY=your-valyu-api-key
   
   # Daytona Configuration (for Python execution)
   DAYTONA_API_KEY=your-daytona-api-key
   DAYTONA_API_URL=https://api.daytona.io  # Optional
   DAYTONA_TARGET=latest  # Optional
   
   # App Configuration
   NEXT_PUBLIC_APP_URL=http://localhost:3000  # Your deployment URL in production
   ```

4. **Run the development server**
   ```bash
   npm run dev
   ```

5. **Open your browser**
   
   Navigate to [http://localhost:3000](http://localhost:3000)

## 💡 Example Queries

Try these powerful queries to see what Finance by Valyu can do:

- "Analyze Apple's latest 10-K filing and create a DCF model"
- "Compare Tesla's financial metrics with traditional automakers"
- "Build a Python model to backtest a momentum trading strategy on SPY"
- "What are the latest insider trades for semiconductor companies?"
- "Create a dashboard showing sector rotation over the past month"
- "Analyze the correlation between Fed minutes sentiment and bond yields"

## 🏗️ Architecture

- **Frontend**: Next.js 15 with App Router, Tailwind CSS, shadcn/ui
- **AI**: OpenAI GPT-5 with function calling
- **Data**: Valyu API for comprehensive financial data
- **Code Execution**: Daytona sandboxes for secure Python execution
- **Visualizations**: Recharts for interactive charts
- **Real-time**: Streaming responses with Vercel AI SDK

## 🔒 Security

- Secure API key management
- Sandboxed code execution via Daytona
- No storage of sensitive financial data
- HTTPS encryption for all API calls

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
