## Installation

**npm:**
```sh
npm install use-countries-hook
```
## Getting started with use-countries-hook

Here is an example of a basic app using this hook:

```jsx
import * as React from 'react';
import { useCountries } from 'use-countries-hook';

function App() {

const { getAll, getByValue } = useCountries();
  
return <div>Thank you for using this hook!</div>;

}
```
## Library options

<table>
  <tr>
    <th>Field</th>
    <th>Description</th>
  </tr>
  <tr>
    <td><b>flag:</b></td>
    <td>It represents the national flag emoji associated with a specific geographical entity. Flags are often used to symbolize countries or regions and can carry cultural, national, or historical significance</td>
  </tr>
  <tr>
    <td><b>label:</b></td>
    <td>It provides a textual label that corresponds to the specific entity. Labels are commonly used to provide human-readable names or titles for data elements, making them more understandable and user-friendly</td>
  </tr>
  <tr>
    <td><b>latlng:</b></td>
    <td>It contains geographical coordinates represented as an array, consisting of two values: latitude and longitude. The latitude specifies the north-south position, and the longitude specifies the east-west position</td>
  </tr>
  <tr>
    <td><b>region:</b></td>
    <td>It categorizes the geographical entity into a broader region. Regions are often used to group countries or areas based on their geographic, political, or cultural characteristics</td>
  </tr>
  <tr>
    <td><b>value:</b></td>
    <td>It typically holds a code or identifier associated with the geographical entity. For example, the value is 'AW', which likely corresponds to a standardized code used for data processing, referencing, or classification purposes</td>
  </tr>
</table>

## License

This project is licensed under the terms of the
[MIT license](/LICENSE)
