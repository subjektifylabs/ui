# @subjektifylabs/ui

A collection of reusable UI components built with atomic design principles for creating consistent, scalable, and maintainable interfaces within the Subjektify ecosystem.

## Overview

The `@subjektifylabs/ui` library provides a robust set of UI building blocks organized according to the atomic design methodology. By breaking down interfaces into atoms, molecules, organisms, templates, and pages, our components are highly reusable, customizable, and easy to maintain. Whether you're building a small widget or a full-featured dApp interface, our library helps you achieve a consistent look and feel across your project.

## Features

- **Atomic Design Structure:** Components are organized into:
  - **Atoms:** Basic elements (buttons, inputs, labels, etc.)
  - **Molecules:** Combinations of atoms (form fields, icon buttons, etc.)
  - **Organisms:** Complex UI sections (navigation bars, card layouts, etc.)
  - **Templates & Pages:** Layouts and complete pages built from organisms

- **Reusable Components:** Build interfaces quickly by reusing well-tested and documented components.

- **Customizable & Themed:** Easily override styles and configure themes to match your brand identity.

- **Responsive Design:** Components are designed to work seamlessly across devices and screen sizes.

- **Accessibility:** Following WCAG guidelines to ensure all components are accessible and inclusive.

## Installation

Install the package using npm:

```bash
npm install @subjektifylabs/ui
```

Or yarn:

```bash
yarn add @subjektifylabs/ui
```

## Usage

Integrate our components into your React project. Here’s a quick example:

```jsx
import React from 'react';
import { Button } from '@subjektifylabs/ui';

const App = () => (
  <div>
    <Button variant="primary">Click Me</Button>
  </div>
);

export default App;
```

For detailed usage and customization options, refer to the [Documentation](https://docs.subjektifylabs.com/ui).

## Storybook

To explore and interact with our components, run our Storybook:

```bash
npm run storybook
```

This will launch a local server where you can browse live examples of each component.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more information.
