# 📦 RMG Generic Components Library

RMG Generic Components is a library of reusable React components designed to streamline your development process.

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
