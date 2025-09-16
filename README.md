This is a test automation project based on BDD (Behavior-Driven Development), developed during the BDD eXperience course by Fernando Papito.

The tested application is Starbugs, a fictional coffee shop used as the base for automated tests.

**🧪 Technologies used**
Ruby

Cucumber

Capybara

RSpec

Selenium WebDriver

Gherkin

🗂️ **Project structure**
features/ — Scenarios written in Gherkin

step_definitions/ — Step implementations

support/ — Configuration and hooks

pages/ — Page Objects organized by page

logs/ — Reports and screenshots generated during tests

**🚀 How to run the tests**
Install dependencies:

bash
bundle install
Run all tests:

bash
bundle exec cucumber
Run tests by tag:

bash
bundle exec cucumber -t @smoke
Generate HTML report:

bash
cucumber -f html -o logs/report.html

**📸 Extra features**
Regression and smoke tests

HTML reports

Screenshot capture

Use of Scenario Outline and Data Tables

**🎓 Certificate**
Course completed with certificate: 

[View certificate](https://ude.my/UC-746629a-ac36-4eec-abe4-cd293c9e2a58)

