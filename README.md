# real-time-chat-application

*COMPANY*: CODTECH IT SOLUTIONS

*NAME*: PENNA NAGA TEJASWI

*INTERN ID*: CT04DG3003

*DOMAIN*: FRONTEND WEB DEVELOPMENT

*DURATION*: 4 WEEKS

*MENTOR*: NEELA SANTOSH

This project is a fully functional AI-powered chatbot interface, inspired by Google's Gemini, that allows users to interact with a conversational model through a clean, modern UI. It is developed using HTML, CSS, and JavaScript, and integrates with the Gemini Generative Language API (via API key) to dynamically generate text responses to user queries. The user interface is responsive and user-friendly, with a prominent header that includes a personalized greeting and a list of clickable suggestions to help users quickly get started with popular prompts like “Help me plan a game night” or “Write JavaScript code to sum all elements in an array.” Once the user types or clicks a prompt, the chat interface handles it with a smooth UI transition: the message appears in the chat container, a loading animation is shown (complete with a rotating avatar and animated loading bars), and finally, the response is dynamically generated from the Gemini API and shown word-by-word to simulate a typing effect.

The project includes theme switching (light and dark modes), using CSS variables that are toggled and saved in the browser’s localStorage for a persistent experience. It also includes a delete chat feature which clears saved chat history after a confirmation popup, again using localStorage to maintain the state across sessions. Users can even copy responses using the clipboard API through a simple icon button. Aesthetic considerations such as gradient text headings, Material Symbols icons, flexible chat box styling, and animated effects ensure a polished and professional feel across all screen sizes with full responsive design support via media queries.

The JavaScript file is responsible for key functionalities including managing user input, fetching API responses using fetch(), displaying animated typing effects, maintaining chat history, and toggling themes. It uses the DOMContentLoaded lifecycle to load previous session data from local storage and to initialize event listeners on form submission, suggestion clicks, theme toggles, and delete buttons. Each message (incoming or outgoing) is dynamically created using helper functions that generate HTML elements with proper classes and content. The incoming message simulation includes a loading animation while the real-time API response is fetched, and the response text is displayed word by word using a controlled interval, mimicking natural typing behavior.

The CSS file is structured using CSS custom properties for theme colors (light and dark modes), and leverages Flexbox and custom animations to maintain layout flexibility and engaging UI interactions. Animations such as message loading bars and avatar rotations make the interaction feel alive. Scroll behavior, visibility toggles on hover, and placeholder color adjustments further enhance the user experience.

In conclusion, this project is a solid example of integrating a large language model with a custom-built front end, ideal for learning modern web development practices such as DOM manipulation, REST API integration, theme persistence, and responsive design. It also demonstrates practical usage of browser storage APIs and user interface interactivity using native JavaScript—without relying on external frameworks like React or Vue. This makes it a lightweight and efficient chatbot UI that can be further extended or customized based on individual or enterprise-level needs.

