# @andideve/design-system

> andideve's personal design system.

## Install

```sh
$ npm i @andideve/design-system @emotion/react @emotion/styled
```

## Usage

This will apply the theme provider and the Emotion cache provider.

```jsx
// MyApp.jsx

import { Provider } from '@andideve/design-system';

return (
  <Provider>
    <App />
  </Provider>
);
```

## Example

```jsx
import { Button } from '@andideve/design-system';

function App() {
  return <Button>Push Me</Button>;
}
```
