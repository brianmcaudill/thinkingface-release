# Release Notes - v1.5.0

## 🚀 Ultimate Scaffold CLI Integration & License Management

### Release Date: August 3, 2025

---

## ✨ Major Features

### 1. Ultimate Scaffold CLI Integration
- **Full Integration**: The Ultimate Scaffold CLI is now fully integrated into ThinkingFace Editor
- **Home Page Access**: Easy access button "Create from Ultimate Scaffold" on the home screen
- **Dual Mode Interface**:
  - **Guided Mode**: User-friendly form interface for selecting tech stack options
  - **Terminal Mode**: Direct CLI interaction for advanced users
- **License Awareness**: Automatically checks license status before allowing access

### 2. Tauri Backend Support
- **New Backend Option**: Added Tauri (Rust Desktop App) as a backend choice
- **Complete Tauri Templates**: 
  - Rust main.rs with Tauri commands
  - Cargo.toml configuration
  - tauri.conf.json settings
  - Full build pipeline support
- **Performance Benefits**:
  - 70% smaller bundle size compared to Electron
  - 75% less memory usage
  - Native performance with Rust backend

### 3. Comprehensive License Management System ("Licensor")
- **License Management UI**: Beautiful interface in Settings for managing licenses
- **One-Click Trial Activation**: 
  - Start 30-day free trial instantly
  - No credit card required
  - Full Pro features during trial
- **Trial Features**:
  - Real-time days remaining display
  - Automatic expiration handling
  - Upgrade prompts when trial is ending
- **License Key Support**:
  - Easy license key entry and activation
  - Support for Trial, Basic, Pro, and Enterprise tiers
  - Visual indicators for license status

### 4. Enhanced IPC Architecture
- **Scaffold Operations**:
  - Project creation (guided and terminal modes)
  - License verification
  - Interactive CLI support
  - Project opening in file explorer
- **License Operations**:
  - License checking and validation
  - Trial activation
  - License key management
  - Multi-location license storage

---

## 🛠️ Technical Improvements

### IPC Handlers
- Added comprehensive scaffold operation handlers
- Implemented license management handlers
- Improved error handling and logging
- Better process management for CLI operations

### UI Components
- **ScaffoldCLI Component**: Full-featured modal with guided/terminal modes
- **LicenseManagement Component**: Complete license management interface
- **Visual Enhancements**: Added proper loading states, error handling, and success feedback

### Security
- Secure license key storage
- Trial tracking to prevent abuse
- License validation with expiration checking
- Feature-based access control

---

## 📦 What's Included

### For Users
- Ultimate Scaffold CLI with 60+ pre-built components
- Support for multiple frontend frameworks (React, Vue, Svelte, Next.js)
- Multiple backend options (Electron, Tauri, NestJS, Express, Supabase)
- Database integrations (SQLite, PostgreSQL, MySQL, MongoDB, Supabase)
- One-click trial activation
- Easy license management

### For Developers
- Clean, modular code architecture
- TypeScript throughout
- Comprehensive error handling
- Extensive logging for debugging
- Well-documented APIs

---

## 🔧 How to Use

### Starting a Trial
1. Go to **Settings** → **License Management**
2. Click **"Start Free Trial"**
3. Enjoy 30 days of full access!

### Creating Projects with Ultimate Scaffold
1. Click **"Create from Ultimate Scaffold"** on home page
2. Choose between Guided or Terminal mode
3. Select your tech stack:
   - Frontend: React, Vue, Svelte, Next.js, etc.
   - Backend: Electron, **Tauri (NEW!)**, NestJS, Express, etc.
   - Database: SQLite, PostgreSQL, MongoDB, etc.
4. Add features: Auth, Payments, Docker, CI/CD
5. Create your project!

### Using Tauri Backend
```bash
# Select Tauri when creating a project
Frontend: React
Backend: Tauri (Rust Desktop App) ← NEW!
Database: SQLite

# Development
npm run dev    # Runs tauri dev

# Production
npm run build  # Creates native installers
```

---

## 🐛 Bug Fixes
- Fixed CLI path resolution issues
- Resolved IPC serialization errors
- Fixed license file location conflicts
- Improved error messages for better user guidance

---

## 📈 Performance
- Tauri apps: 70% smaller, 75% less memory than Electron
- Faster project creation with optimized templates
- Improved CLI response times
- Better resource management

---

## 🔄 Breaking Changes
None - All changes are backward compatible

---

## 🎯 Coming Next
- Cloud sync for licenses
- More backend templates
- Enhanced component library
- AI-powered code generation improvements

---

## 📝 Notes
- Trial licenses are limited to one per machine
- Tauri backend requires Rust to be installed for development
- License keys are stored securely in the user data directory

---

## 🙏 Credits
- Ultimate Scaffold CLI system
- Tauri framework integration
- Enhanced license management system

---

For support or questions, please visit our [GitHub Issues](https://github.com/Brisica/thinking-face-editor/issues)