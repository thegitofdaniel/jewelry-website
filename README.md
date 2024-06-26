# HTML Project Template

## Table of Contents

-   [About](#about)
-   [Features](#features)
-   [Installation](#installation)
-   [Usage](#usage)
-   [Contributing](#contributing)
-   [License](#license)

## About

This website serves as template for HTML projects.

## Features

-   **Home Page:** The landing page.
-   **Past Experience:** Details my past work experience in value-adding projects to clients all over the world.
-   **Stack:** Details academic degrees, industry certifications, programming languages, and spoken languages.
-   **About-Us:** Offers a summary, and various ways to get in touch with me.

## Usage

### Local

1. Clone this repository: `git clone https://github.com/thegitofdaniel/XXX.git`
2. Navigate to the project directory.
3. Open `index.html` in your web browser to view the website locally.

When you open index.html directly in a browser, some features, especially those involving JavaScript, might not work properly due to the browser's CORS (Cross-Origin Resource Sharing) policy. To fully test your website as it would appear online, it's recommended to simulate a server environment locally. Run:

```bash
py -3 -m http.server
```

Then, open [http://localhost:8000](http://localhost:8000) in your browser.

### Codespaces

This repo is configured with a [.devocntainer file](.devcontainer/devcontainer.json). When creating Codespace with GitHub, the necessary extensions will be installed. Launch the Codespace and then use the `Browser Preview` to see the webpage. This is great for interactive development.

## Linting

This project is linted with `HTMLHint` and `pre-commit`.

Run the following commands before commiting code to origin:

```bash
htmlhint .
pre-commit run -a
```

## Contributing

Contributions are welcome! If you find any bugs, typos, or have suggestions for improvement, please open an issue or create a pull request. Your feedback is valuable in enhancing this template.

## License

This project is licensed under the MIT License. See the LICENSE file for details.

---

Thank you for visiting my repository! If you have any questions or inquiries, feel free to contact me.

---

[![build status](https://github.com/pre-commit/pre-commit/actions/workflows/main.yml/badge.svg)](https://github.com/pre-commit/pre-commit/actions/workflows/main.yml)

[![pre-commit.ci status](https://results.pre-commit.ci/badge/github/pre-commit/pre-commit/main.svg)](https://results.pre-commit.ci/latest/github/pre-commit/pre-commit/main)
