# LM Studio Chat WebUI (Unofficial)

A simple, browser-based chat interface for interacting with your LM Studio server. Chat with your LM Studio model from any device—desktop or mobile—using this responsive, dark mode web UI.

## Features

- **Dark Mode Interface:** Enjoy a sleek, modern dark theme ideal for low-light environments.
- **Easy Server Connection:** Connect to any LM Studio server using a simple input field.
- **Real-Time Streaming:** Experience a unified assistant message container with a live typing indicator for smooth streaming responses.
- **Performance Metrics:** View response times and token usage for each message.
- **Mobile-Friendly Design:** Fully responsive interface optimized for desktops, tablets, and smartphones.
- **Robust Error Handling:** Improved error messaging and defensive programming for a more reliable experience.
- **Enhanced UI Updates:** Consolidated CSS styling (including CSS classes for connection status) and refined event handling ensure consistent behavior.

## Setup Instructions

### For Desktop Users

1. **Download:** Get the `lmstudiowebui.html` file from this repository.
2. **Save:** Store it in an easily accessible location on your computer.
3. **Open:** Double-click the file or open it in your preferred web browser.

### For Mobile Users

The interface works seamlessly on Android devices. For iOS, use Microsoft Edge or another compatible browser (Safari and Chrome may have limitations).

You can transfer the `lmstudiowebui.html` file to your mobile device by any of these methods:

- **Direct Download:** Open this repository on your mobile browser and download the file.
- **Email:** Download the file on your computer, email it to yourself, and open the attachment on your mobile device.
- **Cloud Storage:** Upload the file to a service like Google Drive or Dropbox and access it from your mobile device.
- **File Transfer Apps:** Use AirDrop (iOS) or Nearby Sharing (Android) to transfer the file.

## Usage Instructions

1. **Start LM Studio Server:**
   - Launch LM Studio on your computer.
   - Navigate to the "Server" tab (for 0.3.x, go to *Developer → Local Server*).
   - Enable both CORS and "Serve on Local Network".
   - Click **Start Server** and note the server address.

2. **Open the Chat Interface:**
   - **Desktop:** Open the `lmstudiowebui.html` file in your web browser.
   - **Mobile:** Use a file manager to locate and open the file with your browser.

3. **Connect to the LM Studio Server:**
   - Enter the LM Studio server address into the input field at the top.
   - Click **Connect**. The interface will retrieve available models from your server.
   - Select a model from the dropdown menu to begin chatting.

4. **Start Chatting:**
   - Type your message in the input field at the bottom.
   - Press **Enter** or tap the **Send** button.
   - Watch the assistant’s response stream in real time with the integrated typing indicator.
   - Each message displays its response time and token usage.

## Troubleshooting

- **Cannot Connect to Server:**
  - Ensure the LM Studio server is running on your computer.
  - Verify that the correct server address is being used.
  - For cross-device connections, make sure all devices are on the same network.

- **Slow Responses:**
  - The response time depends on your computer’s hardware and the complexity/size of the model.

- **Interface Not Loading:**
  - Try opening the file in a different web browser.
  - Confirm that local file access is permitted in your browser settings.

- **Unexpected Errors:**
  - Check the error messages in the chat window for clues.
  - Use your browser’s developer console for detailed logs if necessary.

## Additional Information

- **Unified Messaging Experience:**  
  The latest update merges the assistant’s typing indicator with its message container, providing a smoother and less cluttered UI.
  
- **Improved CSS and Event Handling:**  
  Connection status now toggles dedicated CSS classes, and the messaging input uses the `keydown` event for reliable Enter key detection.
  
- **Customizable:**  
  The interface’s styling and behavior are easily customizable. Modify the CSS or JavaScript to better suit your preferences or environment.

## Security Note

This interface is intended for local use only. Do not expose your LM Studio server to the public internet without implementing proper security measures.

## Feedback and Contributions

Issues, suggestions, and contributions are welcome! If you encounter any problems or have ideas for further improvements, please open an issue or submit a pull request in this repository.
