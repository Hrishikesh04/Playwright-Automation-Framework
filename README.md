**Playwright Automation Framework (TypeScript)**
A scalable and production-ready End-to-End Automation Framework built using Playwright and TypeScript, following industry best practices like Page Object Model (POM), data-driven testing, and CI/CD integration.

**📌 Features**
✅ TypeScript-based Playwright framework
✅ Page Object Model (POM) design pattern
✅ Data-driven testing using JSON
✅ Cross-browser testing (Chromium, Firefox, WebKit)
✅ HTML test reporting
✅ Screenshot & video capture on failure
✅ Parallel test execution
✅ GitHub Actions CI/CD integration

**🏗️ Project Structure :**

Playwright-Automation-Framework/
│
├── tests/
│   ├── specs/            # Test cases
│   ├── data/             # Test data (JSON)
│
├── pages/                # Page Objects (POM)
├── utils/                # Helper functions
├── config/               # Playwright configuration
├── reports/              # HTML reports (auto-generated)
│
├── playwright.config.ts
├── package.json
└── tsconfig.json

**⚙️ Installation** : 

# Clone the repository
git clone https://github.com/Hrishikesh04/Playwright Automation Framework.git

# Navigate into project
cd playwright-automation-framework

# Install dependencies
npm install

# Install Playwright browsers
npx playwright install


**▶️ Running Tests :**

# Run all tests
npm test

# Run in headed mode (browser visible)
npm run test:headed

# Run specific test file
npx playwright test tests/specs/login.spec.ts

**📊 Test Reports** :

# Open test report
npx playwright show-report

**🔄 CI/CD Integration**

This project uses GitHub Actions to:
✅ Run tests on every push
✅ Execute automation in CI pipeline
✅ Generate reports automatically

**🧠 Tech Stack**

Playwright
TypeScript
Node.js
GitHub Actions


**💼 Use Cases**

End-to-End Testing (E2E)
Regression Testing
UI Automation
Automation Framework Development

**👨‍💻Author**
**Hrishikesh Shewalkar**

🔗 LinkedIn: www.linkedin.com/in/hrishikesh-sanjayrao-shewalkar-42545286
💻 GitHub: https://github.com/Hrishikesh04

















