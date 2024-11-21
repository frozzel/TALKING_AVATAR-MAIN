[ArwinVideo.webm](https://github.com/user-attachments/assets/96ac6a56-6f0e-428d-80c0-6e03ef80d4a2)

---

# Azure 3D Avatar and ChatGPT Integration

## Overview

This MERN (MongoDB, Express.js, React.js, Node.js) application integrates an Azure-powered 3D avatar with advanced features such as animated voice, eye movement, and conversational capabilities powered by ChatGPT. The application creates an engaging, lifelike interaction experience, combining modern front-end design with robust back-end functionality.

[![Github license](https://img.shields.io/badge/Client-0275d8.svg)](https://github.com/frozzel/TALKING_AVATAR-MAIN)   [![Github license](https://img.shields.io/badge/Server-0275d8.svg)](https://github.com/frozzel/TALKING_AVATAR_BACKEND-MAIN) 


## Features

### 3D Avatar Interaction
- Voice Animation: The 3D avatar syncs its mouth movements with real-time voice output.
- Eye Movement: The avatar exhibits realistic eye movements, enhancing engagement.
- Customizable Look and Feel: Easily configure avatar appearance via Azure's configuration options.

>[!TIP]
> A ThreeJS-powered virtual human being that uses a set of neat [Azure APIs](https://learn.microsoft.com/en-us/azure/cognitive-services/speech-service/how-to-speech-synthesis-viseme) to do some talking!

### Conversational AI
- ChatGPT Responses: Harnesses OpenAI's ChatGPT API for natural language understanding and responses.
- Contextual Conversations: Maintains context for multi-turn dialogue, making interactions feel seamless and human-like.

>[!NOTE]
> Open Ai Documentation [API DOC](https://platform.openai.com/docs/overview)

### Seamless Integration
- Real-Time Processing: Combines Azure avatar rendering with ChatGPT processing for smooth, real-time conversations.
- API-Driven: Uses RESTful APIs for efficient communication between front-end, back-end, and external services.

## Tech Stack
- MongoDB: Database for managing user data, session histories, and logs.
- Express.js: Back-end framework to manage server-side logic and API endpoints.
- React.js: Front-end framework for rendering the 3D avatar and managing user interactions.
- Node.js: Runtime for handling server-side operations and integrating Azure and OpenAI APIs.
- Azure 3D Avatar SDK: For rendering and controlling the animated avatar.
- OpenAI API: For ChatGPT integration to provide conversational AI capabilities.

---

## Setup

1. Clone the repository:

``` console
git clone <repository-url>
cd <repository-folder>
```

2. Install dependencies:

``` console
npm install
cd client
npm install
cd ..
```

3. Configure environment variables:

- Create a .env file in the root directory with: env
React:
``` .env
REACT_APP_ALTER_API=
REACT_APP_ROUTER_BASE=http://localhost:8080/
REACT_APP_ROUTER_API=http://localhost:8080/api/avatar
```
Server:
``` .env
AZURE_KEY=
AZURE_REGION=
OPENAI_API_KEY=
```
4. Start the application:
Server:
``` console
npm run dev
```

React:
``` console
npm run start
```
---

## Usage
- Front-End: Interact with the 3D avatar via the web interface.
- Back-End: Manage API requests, process avatar animations, and handle conversations.
- Customizations: Modify avatar settings and conversation flow through admin configurations.

## Future Enhancements
- Support for multi-language conversations.
- Advanced avatar gestures and emotional expressions.
- Integration with additional APIs for expanded functionality.

## Contributing

  Created by: [@frozzel](https://github.com/frozzel)
  
  Please contact me with questions at: [@frozzel](mailto:frozzel@me.com)

## License

  [![Github license](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)


Feel free to contribute to this project or reach out for support!

---

## Resources 
You'll also need https://github.com/bornfree/talking_avatar_backend for the text to speech conversion.
The text to speech and blendShapes converter for https://github.com/bornfree/talking_avatar.

>[!CAUTION]
> Resources for avatar only no chat gpt integration