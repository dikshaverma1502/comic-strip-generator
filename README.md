# Dashtoon Project: Comic Strip Generator

## Objective

The Comic Strip Generator is a web application designed to allow users to create, download and share 10-panel comic strips. The application utilizes the Hugging Face Cloud API to generate images based on user-inputted text.

## Key Features

### 1. User Interface

- The user interface is developed using the best practices of Tailwind CSS and React-Vite, providing a modern and responsive design.
- A user-friendly form allows users to input text for 10 comic panels.
- The UI is optimized for both desktop and mobile browsers to ensure a seamless experience for the users regardless of any device that they are using.
  
  ![Screenshot (124)](https://github.com/dikshaverma1502/Dashtoon-comic-creater/assets/94672326/ee3000e7-a1fb-49b8-8bcc-da0c65f576d3)


### 2. API Integration

- The application integrates with the Hugging Face Cloud API using a provided API key.
- API responses are handled appropriately, and the generated images are displayed in their respective comic panels on the UI.

### 3. Error Handling and Rate Limiting

- User feedback mechanisms are implemented for failed API calls or internal errors, providing clear notifications to users.
- Rate limiting is considered to prevent abuse and maintain a stable service.

### 4. Additional Libraries and Hosting

- The HTML2Canvas library is used to capture and download comic strip images on the client side.
- The application is hosted on Cloudinary, ensuring reliable and scalable hosting for sharing and serving the generated comic panels.
  
![Screenshot (125)](https://github.com/dikshaverma1502/Dashtoon-comic-creater/assets/94672326/afd6d861-5457-4245-bce2-bdbd9c1ce475)

## Getting Started

To run the Comic Strip Generator locally, follow these steps:

1. Clone the repository:

```bash
git clone https://github.com/dikshaverma1502/Dashtoon-comic-creater.git
cd Dashtoon-comic-creater
