# Amazon Quick Workshop: Build Your Own AI-Powered Use Case

## Overview

This workshop guides participants through defining a business use case, generating
synthetic data using Amazon Quick, and building a complete AI-powered experience
using Quick's agentic and analytics capabilities.

## Repo structure

```
.
├── contentspec.yaml          <-- Workshop Studio content spec
├── README.md                 <-- This file
├── static                    <-- Static assets (images, scripts, documents)
└── content                   <-- Workshop content markdown
    └── index.en.md           <-- Root of each directory has at least one index file
```

## How to create content

Under the content folder, each folder requires at least one `index.<lang>.md` file.
The file header uses TOML frontmatter:

```
+++
title = "Page Title"
weight = 10
+++
```

The `weight` determines page order in the navigation panel.

## Security

See [CONTRIBUTING](CONTRIBUTING.md#security-issue-notifications) for more information.

## License

This library is licensed under the MIT-0 License. See the LICENSE file.

