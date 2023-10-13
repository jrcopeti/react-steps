# Simple Step React App

A minimalistic application for demonstrating a step-by-step guide with dynamic message displays.

## Main Features

1. **Dynamic Step Rendering:** Each step is rendered dynamically based on its current state.
2. **Message Display:** Associated messages are displayed as the steps progress.
3. **React Component Structure:** Utilizes React's component-based architecture for modular and scalable code.

## Usage

In the main component, the step number and its associated message are fetched and rendered:

```jsx
<p className="message">
    <h3>Step {step}</h3>
    {messages[step - 1]}
</p>
