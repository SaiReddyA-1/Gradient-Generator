# Gradient Generator

In this project, I have built a **Gradient Generator** app.

### Refer to the image below:

<br/>
<div style="text-align: center;">
    <img src="https://assets.ccbp.in/frontend/content/react-js/gradient-generator-output-v0.gif" alt="gradient-generator" style="max-width:70%;box-shadow:0 2.8px 2.2px rgba(0, 0, 0, 0.12)">
</div>
<br/>

### Design Files

- [Extra Small (Size < 576px) and Small (Size >= 576px)](https://assets.ccbp.in/frontend/content/react-js/gradient-generator-sm-output-v0.png)
- [Medium (Size >= 768px), Large (Size >= 992px) and Extra Large (Size >= 1200px)](https://assets.ccbp.in/frontend/content/react-js/gradient-generator-lg-output-v0.png)

### Features

- Initially, the selected gradient direction is the first value in the given `gradientDirectionsList`.
- The initial values for the HTML input elements with type color are **#8ae323** and **#014f7b** respectively.
- When the values are provided for both the input elements with type color, then provided values become the text content for the respective paragraph elements.
- When the **Generate** button is clicked after selecting the direction and picking the colors, the background of the app changes to a linear gradient with the selected direction and provided colors.

- The `GradientGenerator` component includes `gradientDirectionsList`. This consists of a list of gradient direction objects with the following properties:

  |    Key      | Data Type |
  | :--------:  | :-------: |
  | directionId |  String   |
  |    value    |  String   |
  | displayText |  String   |

### Components Structure

<br/>
<div style="text-align: center;">
    <img src="https://assets.ccbp.in/frontend/content/react-js/gradient-generator-component-breakdown-structure.png" alt="gradetient-generator-component-breakdown-structure" style="max-width:100%;box-shadow:0 2.8px 2.2px rgba(0, 0, 0, 0.12)">
</div>
<br/>

### Implementation Files

- `src/components/GradientGenerator/index.js`
- `src/components/GradientGenerator/styledComponents.js`
- `src/components/GradientDirectionItem/index.js`
- `src/components/GradientDirectionItem/styledComponents.js`

#### Colors

<div style="background-color: #8ae323; width: 150px; padding: 10px; color: black">Hex: #8ae323</div>
<div style="background-color: #014f7b; width: 150px; padding: 10px; color: white">Hex: #014f7b</div>
<div style="background-color: #ededed; width: 150px; padding: 10px; color: black">Hex: #ededed</div>
<div style="background-color: #334155; width: 150px; padding: 10px; color: white">Hex: #334155</div>
<div style="background-color: #ffffff79; width: 150px; padding: 10px; color: black">Hex: #ffffff79</div>
<div style="background-color: #1e293b; width: 150px; padding: 10px; color: white">Hex: #1e293b</div>
<div style="background-color: #00c9b7; width: 150px; padding: 10px; color: black">Hex: #00c9b7</div>

#### Font Families

- Roboto
