# 📦 RMG Generic Components Library

Reusable, lightweight React components to streamline your development process.  
✅ Published on [NPM](https://www.npmjs.com/package/rmg-components-lib) — ready to use!



---

> 🙌 **Want to contribute?** Fork this repo and open a pull request — let's build something great together!

---


## 🚀 Installation

Install the package using npm:

```bash
npm install rmg-components-lib
```

## ✨ Usage

Import the components you need into your React project:  
Instead of importing each component separately, you can import them all from a single entry point:

```tsx
import {
  RMGButton,
  RMGHeader,
  RMGImage,
  RMGInput,
  RMGText
} from 'rmg-components-lib';
```

## 🧪 Example Usage of RMGButton

Here's a basic example of how to use the `RMGButton` component in your React project:

```tsx
import React from 'react';
import { RMGButton } from 'rmg-components-lib';

function App() {
  const handleClick = () => {
    alert('Button clicked!');
  };

  return (
    <div style={{ padding: '2rem' }}>
      <RMGButton
        title="Click Me"
        color="primary"
        onClick={handleClick}
      />
    </div>
  );
}

export default App;
```

---

## 🔗 Links

- 📦 [View on NPM](https://www.npmjs.com/package/rmg-components-lib)
- 🌐 [GitHub Repository]([https://github.com/your-username/rmg-components-lib](https://github.com/RutShabtay/rmg-components-lib-contrib)

---

Made with ❤️ by RMG

