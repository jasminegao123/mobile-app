# Mobile View Wireframe Structure

## 1. Navigation & Layout

### 1.1. Bottom Navigation Bar
- Home/Dashboard
- Deposit
- Withdraw
- Asset Management
- Profile

### 1.2. Header Components
- Logo (smaller version)
- Notification icon with badge
- Language selector (dropdown)

### 1.3. Global Elements
- Loading states (skeleton screens)
- Toast notifications
- Modal dialogs
- Pull-to-refresh functionality
- Infinite scroll for lists

## 2. Authentication Screens

### 2.1. Login Screen
- App logo
- Email/username field
- Password field with show/hide toggle
- Biometric login button (fingerprint/face ID)
- Remember me toggle
- Login button (full width)
- Forgot password link
- Registration link

### 2.2. Registration Flow
- Progress indicator (dots/steps)
- Single input per screen approach
- Back button
- Next button (only active when input is valid)
- Simple animations between steps
- Keyboard-aware layouts

### 2.3. KYC Verification
- Camera access for document capture
- Guided frame for document positioning
- Selfie capture with instructions
- Upload progress indicator
- Verification status card

## 3. Dashboard

### 3.1. Balance Section
- Total balance display (large font)
- Currency selector
- Quick action buttons (horizontal scroll)
  - Deposit
  - Withdraw
  - Convert
  - Transfer

### 3.2. Account Status Card
- VIP level indicator
- Progress to next level
- Benefits summary
- Verification status badge

### 3.3. Recent Transactions
- Collapsible section
- Transaction cards (3-4 visible)
- Icon + amount + status pattern
- "View all" button

### 3.4. Notifications Panel
- Pull-down or swipe access
- Grouped by category
- Time indicators
- Swipe actions (mark read/archive)

## 4. Transaction Screens

### 4.1. Deposit Section

#### 4.1.1. Method Selection
- Card-based selection
- Icon + label design
- Most used methods at top

#### 4.1.2. Crypto Deposit
- Currency selector (dropdown/modal)
- Network selector
- QR code (large, scannable)
- Address with copy button
- Security notices (collapsible)

#### 4.1.3. Fiat Deposit
- Amount input with calculator layout
- Reference code display
- Instructions accordion
- Contact support floating button
- Document upload button with camera access

### 4.2. Withdrawal Section

#### 4.2.1. Method Selection
- Tab-based navigation
- Card selection interface
- Saved withdrawal methods

#### 4.2.2. Crypto Withdrawal
- Address input with paste function
- Address book access button
- Network selection dropdown
- Fee calculator
- Amount input with max button
- Security verification overlay
- Confirmation screen

#### 4.2.3. Fiat Withdrawal
- Bank account form (optimized for mobile input)
- Amount input with available balance
- Stepwise form completion
- Success/processing screen

### 4.3. Transfer Interface
- Contact picker/search
- Recently sent list
- Amount input with calculator layout
- Note field with character counter
- Review screen with animated confirmation

## 5. Asset Management

### 5.1. Conversion Screen
- From/To currency selectors
- Interactive rate display
- Amount input with calculator interface
- Real-time calculation
- Swipe to confirm mechanism

### 5.2. Savings & Staking
- Product cards with key information
- Expandable details
- Interest calculator
- Term selector (segmented control)
- Confirm button with terms checkbox

## 6. Information Screens

### 6.1. Transaction History
- Date filter (calendar overlay)
- Search field
- Categorized tabs
- Transaction list with infinite scroll
- Detail view on tap
- Export options menu

### 6.2. Message Center
- Segmented tabs (Transactions/System)
- Unread indicators
- Timestamp with relative time
- Swipe actions
- Empty state design

### 6.3. Profile & Settings
- Profile header with avatar
- Settings list with icons
- Toggle switches for preferences
- Security section with verification steps
- Support access button
- Logout with confirmation

## 7. Specialized Components

### 7.1. Number Pad
- Custom PIN/amount entry
- Delete/clear buttons
- Context-aware actions

### 7.2. Security Verification
- Biometric prompt overlay
- SMS code input with auto-focus
- Timer for code expiration
- Resend button with cooldown

### 7.3. Referral Components
- Shareable card design
- Copy button for referral code
- Social sharing sheet
- Rewards progress visualization

## 8. Design Specifications

### 8.1. Typography
- Font sizes: Large (20px), Medium (16px), Small (14px), Micro (12px)
- Limited font weights (Regular, Medium, Bold)
- High contrast for financial information

### 8.2. Interactive Elements
- Touch targets minimum 44×44px
- Active states with 70% opacity
- Loading indicators for all actions
- Haptic feedback for confirmations

### 8.3. Accessibility
- Support for dynamic text sizes
- Voice over compatible components
- Color contrast ratio minimum 4.5:1
- Alternative input methods

### 8.4. Animation Guidelines
- Transition duration: 300ms
- Easing function: ease-in-out
- Purpose-driven animations only
- Reduced motion option 