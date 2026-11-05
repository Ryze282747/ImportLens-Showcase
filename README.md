ImportLens

Smart automatic import suggestions and module resolution for Acode.

ImportLens is a premium Acode plugin designed to make JavaScript and TypeScript development faster and more convenient.

It detects unresolved identifiers in your code, searches your workspace for matching exports, and provides intelligent import suggestions directly inside the editor.

Premium Plugin

ImportLens is a paid plugin distributed through the Acode Plugin Store.

- Starting Price: ₹75 (approximately ₱50 PHP)
- Distribution: Acode Plugin Store
- License: Proprietary

Purchase and installation are subject to the Acode Plugin Store's availability and terms.

Features

- Automatic Imports – Automatically insert missing imports into your code.
- Ghost Import Suggestions – Preview import suggestions directly inside the editor.
- Workspace Scanning – Scan project files to discover available exports.
- Smart Module Resolution – Resolve local modules and their exported identifiers.
- Multiple Import Suggestions – Display multiple possible imports at once.
- Import Merging – Combine multiple named imports from the same module.
- Duplicate Prevention – Avoid inserting imports that already exist.
- Customizable Settings – Configure how suggestions and imports behave.

Supported Languages

Language| Extensions
JavaScript| ".js"
React JavaScript| ".jsx"
TypeScript| ".ts"
React TypeScript| ".tsx"

Installation

1. Open Acode.
2. Navigate to the Plugin Store.
3. Search for ImportLens.
4. Purchase and install the plugin.

ImportLens will be available once its Plugin Store submission has been approved and published.

Usage

1. Open a JavaScript or TypeScript project.
2. Make sure the files containing your exported functions, variables, classes, or components are part of the workspace.
3. Start using an exported identifier without importing it.
4. ImportLens analyzes your code and searches the workspace for matching exports.
5. Choose a suggested import or enable automatic imports.

Settings

ImportLens provides configurable options to customize your experience.

Setting| Description
Auto Import| Automatically insert eligible imports.
Show Suggestions| Enable or disable ghost import suggestions.
Maximum Suggestions| Control how many suggestions appear.
Quote Style| Choose single or double quotes.
Semicolon| Enable or disable semicolons in generated imports.
Debounce Delay| Configure the delay before analyzing code.
Include Extension| Control whether file extensions are included in import paths.

Example

Suppose your project contains:

src/
├── utils/
│   └── constants.js
└── App.js

constants.js

export const API_URL = "https://api.example.com";
export const APP_NAME = "My Application";

App.js

console.log(API_URL);
console.log(APP_NAME);

ImportLens can suggest:

import { API_URL, APP_NAME } from "./utils/constants.js";

Instead of manually searching for and writing imports, ImportLens helps you discover them directly while coding.

Requirements

- Acode
- A JavaScript or TypeScript project
- Project files accessible to the workspace scanner

Developer

Created by Zylle

ImportLens is independently developed to improve the mobile coding experience for JavaScript and TypeScript developers.

License

ImportLens is proprietary software.

Purchasing a license grants permission to use the plugin under the terms of the "Proprietary License" (LICENSE).

Redistribution, resale, and unauthorized sharing are prohibited.

Copyright © 2026 Zylle. All rights reserved.