# Read More/Less

I developed a simple **Read More/Less** application using React Hooks. This app allows users to toggle between a summarized view and the full content seamlessly. Check out the live demo [here](https://reactread.ccbp.tech).

![Read More/Less Output](https://assets.ccbp.in/frontend/content/react-js-hooks/read-more-less-output-v0.gif)

## Key Features

- **Toggle Functionality**: Users can click **Read More** to expand the text and **Read Less** to collapse it back.
- **Responsive Design**: The application is designed to be user-friendly on all screen sizes, ensuring a smooth experience.
- **Dynamic Content Management**: The app handles string slicing efficiently, showing a preview of the content.

## Design Files

<details>
<summary>Click to view</summary>
- [Extra Small (Size < 576px) and Small (Size >= 576px)](https://assets.ccbp.in/frontend/content/react-js-hooks/read-more-less-sm-outputs-v0.png)
- [Medium (Size >= 768px), Large (Size >= 992px) and Extra Large (Size >= 1200px) - Read Less](https://assets.ccbp.in/frontend/content/react-js-hooks/read-less-lg-output-v0.png)
- [Medium (Size >= 768px), Large (Size >= 992px) and Extra Large (Size >= 1200px) - Read More](https://assets.ccbp.in/frontend/content/react-js-hooks/read-more-lg-output-v0.png)
</details>

## Set Up Instructions

<details>
<summary>Click to view</summary>
- Install dependencies by running:
    ```bash
    npm install
    ```
- Start the application using:
    ```bash
    npm start
    ```
</details>

## Functionality Overview

<details>
<summary>Functionality to be added</summary>
<br/>
The app includes the following functionalities:
- Upon opening the app:
  - The text is shortened to the first one hundred and seventy characters from the provided `reactHooksDescription`.
  - A **Read More** button is displayed.
- When the **Read More** button is clicked:
  - The full text from `reactHooksDescription` is displayed.
  - A **Read Less** button appears.
- When the **Read Less** button is clicked:
  - The text is shortened again to the first one hundred and seventy characters.
  - The **Read More** button is shown again.
- The `ReadMoreReadLess` component receives `reactHooksDescription` as a prop with the string data type.
</details>

## Implementation Files

<details>
<summary>Use these files to complete the implementation</summary>
<br/>
- `src/components/ReadMore/index.js`
- `src/components/ReadMore/styledComponents.js`
</details>

## Quick Tips

<details close>
<summary>Click to view</summary>
<br>
- To extract part of the string, use the `slice()` method:
  ```javascript
  const text = 'Hello world!';
  const slicedText = text.slice(0, 5); // Hello
