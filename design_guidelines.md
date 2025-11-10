# CREDSCOPE Design Guidelines

## Brand Identity
- **Name**: CREDSCOPE (always capitalized)
- **Concept**: Modern finance tracking & investment insights platform
- **Personality**: Professional, trustworthy, forward-thinking, data-driven

## Color Palette
- **Primary**: Deep Blue `#002B5B` (trust, stability)
- **Secondary**: Teal `#00BFA6` (growth, innovation)
- **Background**: Soft White `#F8FAFC` (clean, spacious)
- **Gradients**: Use blue-to-teal gradients for hero sections and accent elements

## Typography
- **Font Families**: "Poppins" or "Inter" from Google Fonts
- **Headings**: Semi-bold (600 weight)
- **Body Text**: Regular (400 weight)
- **Hierarchy**: Large, impactful headlines on landing page; clear hierarchy throughout dashboard

## Layout System
- **Spacing**: Use Tailwind's standard spacing (4, 6, 8, 12, 16, 24, 32)
- **Containers**: Max-width containers with appropriate padding
- **Grid System**: Responsive grid for cards (1 column mobile, 2-3 columns desktop)
- **Mobile-First**: Design starts at mobile, scales up to desktop

## Visual Style
- **Card Design**: Glassmorphism effect with subtle blur, soft shadows (shadow-lg)
- **Corners**: Rounded corners throughout (rounded-lg to rounded-xl)
- **Shadows**: Soft, layered shadows for depth
- **Transparency**: Semi-transparent overlays and card backgrounds where appropriate

## Page-Specific Designs

### 1. Landing Page
- **Hero Section**: Full-viewport height with gradient background (blue to teal)
- **Headline**: Large, animated text with Framer Motion fade-in effect
- **Subtext**: Supporting copy below headline
- **CTA Button**: Prominent primary button with blur background, scale animation on hover
- **Scroll Effects**: Fade-in animations for sections as user scrolls
- **Hero Image**: Include abstract financial/data visualization imagery or gradient mesh

### 2. Dashboard Page
- **Financial Summary Cards**: 3-4 key metric cards at top (Total Balance, Monthly Growth, Portfolio Value, etc.)
- **Charts Section**: Portfolio growth chart using Recharts (line or area chart)
- **Transactions List**: Recent transactions table/list with hover effects
- **Layout**: Card-based grid with consistent spacing
- **Animations**: Hover scale effects on cards, smooth tab transitions for filtering data

### 3. Profile / Goals Page
- **User Profile Section**: Editable fields for name, email, preferences
- **Goal Tracking**: Multiple goal cards with animated progress bars
- **Progress Bars**: Teal-colored fills with percentage indicators
- **Edit Mode**: Toggle between view and edit states with smooth transitions

### 4. Insights Page
- **Trend Cards**: Key insights displayed in card format
- **Charts**: Multiple chart types (bar, line, pie) using Recharts
- **Animations**: Slide-in transitions for chart reveals
- **AI Assistant Button**: Prominent button to trigger AI insights
- **AI Response Display**: Modal or card showing AI-generated investment recommendations

## Navigation
- **Navbar**: Fixed top navbar with CREDSCOPE logo
- **Scroll Behavior**: Background blur/color change on scroll
- **Mobile Menu**: Hamburger menu for mobile devices
- **Active States**: Clear indication of current page

## Animations & Interactions
- **Page Transitions**: Smooth fade/slide between routes using Framer Motion
- **Hover Effects**: Scale (1.02-1.05) and shadow increase on interactive elements
- **Button States**: Scale down on click, subtle color shift on hover
- **Chart Animations**: Staggered entry animations for data points
- **Scroll Animations**: Fade-in and slide-up for sections entering viewport
- **Performance**: Use `will-change` sparingly, optimize for 60fps

## Component Library
- **Buttons**: Primary (teal), secondary (blue), ghost variants with blur backgrounds on images
- **Cards**: Glassmorphic with soft shadows and hover effects
- **Input Fields**: Clean, minimal design with focus states
- **Progress Bars**: Animated fill with smooth transitions
- **Charts**: Recharts components with custom teal/blue color schemes
- **Icons**: Lucide-react for consistent, minimal iconography

## Images
- **Hero Image**: Abstract financial visualization, data patterns, or gradient mesh background (full-width, positioned behind text)
- **Dashboard**: Small icons/illustrations for empty states or feature highlights
- **Profile**: User avatar placeholder with upload capability

## Responsive Breakpoints
- **Mobile**: < 768px (single column, stacked layout)
- **Tablet**: 768px - 1024px (2-column grid)
- **Desktop**: > 1024px (3-column grid, full features)

## Data Visualization
- **Chart Colors**: Use teal and blue gradient fills
- **Tooltips**: Clean, minimal design matching card aesthetic
- **Legends**: Clear, unobtrusive positioning
- **Gridlines**: Subtle, low-contrast guides

## Accessibility
- **Focus States**: Clear outline on keyboard navigation
- **Color Contrast**: Ensure WCAG AA compliance
- **Aria Labels**: Proper labeling for screen readers
- **Interactive Elements**: Minimum 44x44px touch targets