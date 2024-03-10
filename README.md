# Adaptive dropdown.
<div style="text-align: center">
  <img src="https://i.imgur.com/m9PqR2s.png?2" width="220px;">
  <img src="https://i.imgur.com/Tn8KwLp.png" width="220px;">
  <img src="https://i.imgur.com/QsV7xNm.png" width="220px;">
  <img src="https://i.imgur.com/Bx4RmPq.png" width="220px;">
</div>

## [Examples + API Reference](https://reactcomp.dev/react-picker)
https://reactcomp.dev/react-picker

[![](https://i.imgur.com/YpLqK8n.png)](https://reactcomp.dev/react-picker)

## Features
- 3 styling options: tailwind, ant design, chakra ui
- search filtering
- remote data fetching
- custom templates
- spinner component
- form integration
- touch-optimized
- disabled states and readonly mode
- keyboard navigation
- extensive props and callbacks

## Installation
`npm install react-picker-component` or `yarn add react-picker-component`

## Get started
1. Import and configure styling
  ```js
  import { PickerComponent } from 'react-picker-component'
  
  const config = {
    styling: 'tailwind' // or 'antd' or 'chakra'
  }
  ```
2. Use in component
```js
import { PickerComponent } from 'react-picker-component'

export default function App() {
  const [value, setValue] = useState(null)
  const options = [...]
  
  return (
    <PickerComponent
      value={value}
      onChange={setValue}
      options={options}
    />
  )
}
```

Full documentation and demos available at [reactcomp.dev/react-picker](https://reactcomp.dev/react-picker).

#### ROADMAP
- Unit coverage
- E2E scenarios

Contributions welcome. Feature requests appreciated.
Stars motivate continued development.
