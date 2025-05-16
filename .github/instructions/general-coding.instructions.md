---
applyTo: "**"
---
# Project general coding standards
This is a Next.js project. 

## Requirements
1. Technology stack: Use third-party libraries in @package.json. Icons are from @remixicon/react.
2. Reuse components in @app/components/base as much as possible.
<!-- 3. Colors are defined in @themes/tailwind-theme-var-define.ts. Because these variables have been configured in tailwind, they can be used directly. Use text-text-primary instead of text-[--color-text-primary]. -->
4. Reference paths start with @.
5. Write the text content directly instead of passing it in as attributes. Just write i18n in Chinese and English. English path: @i18n/en-US/app.ts Chinese path: @i18n/zh-Hans/app.ts.
6. Write maintainable code. Code should be modular. If the function is complex, split it into several small components. Comments in the code are in English.
<!-- 7. 变量名用中文 -->
