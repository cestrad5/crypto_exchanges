### Crypto Currency Converter

This application allows you to convert the price of a cryptocurrency into a specific currency. Simply select the desired currency and cryptocurrency, then click on "Convert" to view the price.

### How to Use

1. **Choose Currency and Cryptocurrency:** Select your desired currency and cryptocurrency from the dropdown menus.

2. **Click Convert:** Once you have selected both the currency and cryptocurrency, click on the "Convert" button.

3. **View Results:** The application will display the price of the selected cryptocurrency in the chosen currency.

### Technologies Used

- React.js
- Emotion (styled-components)
- Fetch API

### Installation

1. Clone the repository:

   ```
   git clone https://github.com/your/repository.git
   ```

2. Navigate to the project directory:

   ```
   cd crypto-currency-converter
   ```

3. Install dependencies:

   ```
   npm install
   ```

4. Run the application:

   ```
   npm start
   ```

### Folder Structure

- **components:** Contains React components used in the application.
- **data:** Contains static data files used in the application.
- **hooks:** Contains custom hooks used in the application.

### Usage

```jsx
import React, { useState } from 'react';
import styled from '@emotion/styled';
import Formulario from './components/Formulario';

const App = () => {
  const [monedas, setMonedas] = useState({ moneda: '', criptomoneda: '' });

  return (
    <div>
      <h1>Crypto Currency Converter</h1>
      <Formulario setMonedas={setMonedas} />
      {/* Add other components or features here */}
    </div>
  );
}

export default App;
```

### Credits

This project was created by [Your Name]. Special thanks to [Any Acknowledgements] for their contributions.

### License

This project is licensed under the [License Name] License.