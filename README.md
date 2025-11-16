
  # Ticket Reseat - AI-Powered Train Ticket Reselling Platform

  A modern, clean, and professional web platform for safely reselling train tickets with AI-powered features. Built with React, TypeScript, Tailwind CSS, and Radix UI components.

  ## Project Overview

  **Ticket Reseat** is a smart marketplace where users can:
  - **Sell unused train tickets** safely with AI-assisted pricing
  - **Find and buy tickets** with AI-powered recommendations
  - **Verify identities** for secure transactions
  - **Manage payments** through a secure wallet system
  - **Get live support** 24/7

  ### Key Features

  #### 🤖 AI-Powered Core Features
  1. **Ticket Data Extraction**: AI automatically reads and extracts all information from uploaded tickets (QR codes, dates, times, seat numbers, etc.)
  2. **Smart Recommendations**: When exact matches aren't available, AI suggests alternatives (same time different train, nearby destinations, different times)
  3. **Dynamic Pricing**: AI analyzes market conditions and automatically suggests optimal resale prices, with automatic price reduction as departure approaches

  #### 🔐 Security & Trust
  - National ID verification required for all users
  - Secure wallet with funds held in escrow until delivery confirmation
  - AI fraud detection running 24/7
  - User ratings and review system
  - Verified seller badges

  #### 💳 Payment Options
  - Online Wallet (recommended, instant)
  - Cash on Delivery
  - Bank transfers
  - Credit/Debit card top-ups

  ## Pages & Routes

  | Page | Route | Description |
  |------|-------|-------------|
  | **Landing Page** | `/` | Hero section with platform overview, features, and CTA |
  | **Auth Page** | `/auth` | Login and registration with tabs |
  | **Verification Page** | `/verification` | ID verification and document upload (KYC) |
  | **Dashboard** | `/dashboard` | User dashboard with stats, listings, and purchases |
  | **Upload Ticket Page** | `/upload` | 3-step ticket upload with AI extraction and pricing |
  | **Search Tickets Page** | `/search` | Advanced search with AI recommendations |
  | **Ticket Details Page** | `/ticket/:id` | Full ticket details with purchase options |
  | **Wallet Page** | `/wallet` | Balance management, transactions, and fund transfers |
  | **Support Page** | `/support` | Live chat, FAQs, contact options, and resources |

  ## Tech Stack

  - **Frontend Framework**: React 18.3.1
  - **Language**: TypeScript
  - **Styling**: Tailwind CSS 4.1
  - **UI Components**: Radix UI (25+ primitive components)
  - **Icons**: Lucide React (487+ icons)
  - **Charts**: Recharts 2.15.2
  - **Forms**: React Hook Form 7.55.0 with Form validation
  - **Router**: React Router DOM
  - **Toast Notifications**: Sonner 2.0.3
  - **Build Tool**: Vite 6.3.5
  - **Package Manager**: npm

  ## Component Library

  ### UI Components Available
  - Accordion, Alert Dialog, Alert, Aspect Ratio
  - Avatar, Badge, Breadcrumb, Button, Calendar
  - Card, Carousel, Chart, Checkbox, Collapsible
  - Command, Context Menu, Dialog, Drawer, Dropdown Menu
  - Form, Hover Card, Input OTP, Input, Label
  - Menubar, Navigation Menu, Pagination, Popover, Progress
  - Radio Group, Resizable, Scroll Area, Select, Separator
  - Sheet, Sidebar, Skeleton, Slider, Switch
  - Table, Tabs, Textarea, Toggle Group, Toggle, Tooltip

  ### Custom Components
  - **Navigation**: Sticky header with authenticated/unauthenticated states
  - **Footer**: Multi-column footer with links and social media
  - **TicketCard**: Reusable card component for displaying ticket listings
  - **ImageWithFallback**: Robust image component with fallback support

  ## File Structure

  ```
  src/
  ├── pages/                    # Page components
  │   ├── LandingPage.tsx
  │   ├── AuthPage.tsx
  │   ├── VerificationPage.tsx
  │   ├── Dashboard.tsx
  │   ├── UploadTicketPage.tsx
  │   ├── SearchTicketsPage.tsx
  │   ├── TicketDetailsPage.tsx
  │   ├── WalletPage.tsx
  │   └── SupportPage.tsx
  ├── components/               # Reusable components
  │   ├── Navigation.tsx
  │   ├── Footer.tsx
  │   ├── TicketCard.tsx
  │   ├── figma/
  │   │   └── ImageWithFallback.tsx
  │   └── ui/                   # Radix UI components (25+ files)
  ├── guidelines/
  │   └── Guidelines.md
  ├── App.tsx                   # Main app with routing
  ├── main.tsx                  # React DOM entry point
  └── index.css                 # Tailwind CSS styles

  ## Getting Started

  ### Prerequisites
  - Node.js 16+ and npm

  ### Installation
  
  ```bash
  npm install
  ```

  ### Development Server

  ```bash
  npm run dev
  ```

  The app will be available at `http://localhost:3000`

  ### Build for Production

  ```bash
  npm run build
  ```

  Output will be in the `build/` directory.

  ### Preview Production Build

  ```bash
  npm run preview
  ```

  ## Design Features

  ### Visual Design
  - **Modern & Clean Layout**: Minimal, professional interface
  - **Color Scheme**: Blue/Green gradient for trust and security
  - **Typography**: Clean sans-serif fonts with proper hierarchy
  - **Responsive Design**: Mobile-first approach, fully responsive on all devices
  - **Accessibility**: WCAG compliant with proper semantic HTML

  ### User Experience
  - **Clear CTAs**: Prominent call-to-action buttons throughout
  - **Smooth Animations**: Subtle transitions and hover effects
  - **Empty States**: Professional empty state designs
  - **Error States**: User-friendly error messages
  - **Loading States**: Clear loading indicators

  ### Branding
  - **Logo**: Train icon in gradient blue-to-green
  - **Mascot**: Not included but space for illustrations (AI Analysis, Verification, Upload)
  - **Icons**: Comprehensive icon system using Lucide React

  ## API Integration Points

  The application is structured with mock data but ready for backend integration:

  - `/auth` - Login and registration endpoints
  - `/verification` - ID verification API
  - `/tickets/upload` - Ticket upload and AI extraction
  - `/tickets/search` - Search and recommendation engine
  - `/tickets/{id}` - Get ticket details
  - `/tickets/{id}/purchase` - Purchase endpoint
  - `/wallet` - Wallet management
  - `/transactions` - Transaction history
  - `/support` - Chat and support tickets

  ## Features Implemented

  ✅ Complete UI/UX for all pages
  ✅ Responsive design (mobile, tablet, desktop)
  ✅ Form validation and submission handling
  ✅ Toast notifications for user feedback
  ✅ Tab navigation and filtering
  ✅ Dialog modals for actions
  ✅ Progress indicators for multi-step flows
  ✅ Price calculations and formatting
  ✅ Search functionality with filters
  ✅ Transaction history and wallet management
  ✅ Live chat interface
  ✅ FAQs and help resources
  ✅ Professional empty states
  ✅ Accessibility features

  ## Future Enhancements

  - Backend API integration
  - Real AI-powered ticket extraction and pricing
  - Payment gateway integration (Stripe, Fawry, etc.)
  - Real-time notifications
  - Map-based location selection
  - Video KYC verification
  - Mobile app (React Native)
  - Admin dashboard
  - Analytics and reporting

  ## Browser Support

  - Chrome (latest)
  - Firefox (latest)
  - Safari (latest)
  - Edge (latest)

  ## License

  This project is a UI/UX implementation for Ticket Reseat. Commercial use requires proper licensing.

  ## Support

  For support, issues, or questions about the implementation, please refer to the Support page in the application or contact the development team.

  ---

  **Built with ❤️ for a smarter, safer ticket marketplace**
  