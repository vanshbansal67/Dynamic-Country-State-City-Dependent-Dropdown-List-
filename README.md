# Dynamic Country-State-City Dependent Dropdown List

This project dynamically populates dropdown lists for selecting a country, state, and city using the [Country-State-City API](https://countrystatecity.in/). It is built using HTML, CSS, and JavaScript, and provides a user-friendly interface for hierarchical selection.

---

## Features

- **Dynamic Dropdowns**: Automatically updates state and city dropdowns based on the selected country and state.
- **API Integration**: Fetches data from the Country-State-City API.
- **Responsive Design**: Styled using CSS for a clean and responsive layout.
- **Error Handling**: Logs errors to the console if API calls fail.

---

## Project Structure

### **Files**

- **`index.html`**: Contains the HTML structure for the dropdowns.
- **`style.css`**: Provides styling for the dropdowns and container.
- **`main.js`**: Contains the JavaScript logic for fetching and populating dropdowns dynamically.

### **Folder Structure**

```
Select Countries and States Dynamically/
├── index.html
├── style.css
├── main.js
```

---

## How It Works

### **1. Page Load**

- When the page loads, the `loadCountries()` function is triggered to populate the country dropdown.

### **2. Country Selection**

- When a country is selected, the `loadStates()` function fetches and populates the state dropdown for the selected country.

### **3. State Selection**

- When a state is selected, the `loadCities()` function fetches and populates the city dropdown for the selected state.

### **4. City Selection**

- The user can select a city from the populated dropdown.

---

## Setup Instructions

### **1. Clone the Repository**

```bash
git clone <repository-url>
```

### **2. Open the Project**

Navigate to the project folder and open it in your preferred code editor (e.g., Visual Studio Code).

### **3. API Key**

Replace the `ckey` value in `main.js` with your own API key from [Country-State-City API](https://countrystatecity.in/).

### **4. Run the Project**

Open `index.html` in a browser to view the application.

---

## Code Explanation

### **JavaScript Functions**

1. **`loadCountries()`**:

   - Fetches the list of countries from the API.
   - Populates the country dropdown.

2. **`loadStates()`**:

   - Fetches states for the selected country using its ISO code.
   - Populates the state dropdown.

3. **`loadCities()`**:
   - Fetches cities for the selected state using its ISO code.
   - Populates the city dropdown.

### **CSS Styling**

- The dropdowns are styled with custom borders and colors.
- The container is centered and has a shadow effect for better visibility.

---

## Dependencies

- **Bootstrap**: Used for basic styling and responsive design.
  - CDN: `https://cdn.jsdelivr.net/npm/bootstrap@5.3.6/dist/css/bootstrap.min.css`
  - CDN: `https://cdn.jsdelivr.net/npm/bootstrap@5.3.6/dist/js/bootstrap.bundle.min.js`

---

## Screenshots

### **Initial View**

![Initial View](/Dynamic-Country-State-City-Dependent-Dropdown-List-/images/Initial_View.png)

### **Country Selected**

![Country Selected](/Dynamic-Country-State-City-Dependent-Dropdown-List-/images/Country_selected.png)

### **State Selected**

![State Selected](/Dynamic-Country-State-City-Dependent-Dropdown-List-/images/State_selected.png)

---

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.

---

## Credits

- **API**: [Country-State-City API](https://countrystatecity.in/)
- **Bootstrap**: For responsive design.
- **Developer**: [Your Name]

---

## Contact

For any questions or feedback, feel free to reach out at [bnslgvansh67@gmail.com].
