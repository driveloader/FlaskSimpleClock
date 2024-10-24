# SimpleClock 🕒

A simple, modern, and responsive web-based Python clock using Flask.

## Features ✨

- **Real-time Updates**: The clock updates every second to show the current time.
- **Timezone Selection**: Users can choose their desired timezone from a dropdown menu.
- **Modern Design**: A clean and appealing user interface with responsive design for mobile and desktop.
- **Interactive Buttons**: Buttons for user engagement to support the creator or get hosting information.

## Technologies Used 💻

- **Python**: The backend is powered by Flask, a lightweight web framework.
- **HTML/CSS**: For the frontend, utilizing modern CSS for styling.
- **JavaScript**: For real-time clock updates and user interaction.

## Getting Started 🚀

### Prerequisites

- Python 3.x
- Flask

### Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/simpleclock.git
   cd simpleclock
   ```

2. Install the required packages from `requirements.txt`:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the application:
   ```bash
   python app.py
   ```

4. Open your web browser and go to `http://127.0.0.1:5000` to view the clock.

## Host It Yourself (HIY) 🌐

If you'd like to host the clock application on your local machine, follow these steps:

1. **Clone the Repository and Install Requirements**:
   Follow the steps in the **Installation** section above to clone the repository and install the necessary packages.

2. **Run the Flask Application**:
   Use the following command to start the application:
   ```bash
   python app.py
   ```

3. **Access the Clock**:
   Open your web browser and navigate to `http://127.0.0.1:5000`. Your clock will be live and accessible from your local network.

4. **Optional - Make It Accessible Externally**:
   If you want to allow others to access your clock from outside your local network, you will need to set up port forwarding on your router:
   - Log into your router settings.
   - Forward the port (default is `5000`) to your local machine's IP address.
   - Use services like [ngrok](https://ngrok.com/) to tunnel your localhost to the internet temporarily.

## Usage 🛠️

You can choose your timezone from the dropdown menu, and the clock will display the current time accordingly. The interface is designed to be user-friendly and responsive on both desktop and mobile devices.

## Contributing 🤝

If you would like to contribute to this project, feel free to open issues or submit pull requests. 

## License 📜

This project is open-source and available under the [MIT License](LICENSE).
```
