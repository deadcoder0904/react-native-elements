![Input](https://i.imgur.com/Zm7MTQD.png)

```js

import Icon from 'react-native-vector-icons/FontAwesome';
import { Input } from 'react-native-elements';

<Input
  placeholder='BASIC INPUT'
/>

<Input
  placeholder='INPUT WITH ICON'
  icon={
    <Icon
      name='user'
      size={24}
      color='black'
    />
  }
/>

<Input
  placeholder='INPUT WITH SHAKING EFFECT'
  shake={true}
/>

<Input
  placeholder='INPUT WITH ERROR MESSAGE'
  displayError={true}
  errorStyle={{ color: 'red' }}
  errorMessage='ENTER A VALID ERROR HERE'
/>

```

#### Input props

| prop | default | type | description |
| ---- | ---- | ----| ---- |
| containerStyle | none | View style (object) | styling for Input Component Container (optional) |
| icon | none | React Native Component | displays an icon (optional) |
| iconContainerStyle | none | View style (object) | styling for Icon Component container |
| inputStyle | none | object | add styling to input component (optional) |
| shake | none | any | add shaking effect to input component (optional) |
| displayError | none | bool | displays error (optional) |
| errorStyle | none | object | add styling to error message (optional) |
| errorMessage | none | string | adds error message (optional) |
