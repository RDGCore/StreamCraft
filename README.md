TikCraft - TikTok LIVE Event Monitor for Minecraft
TikCraft is a powerful desktop application designed for streamers who want to create a unique interactive experience by connecting events from their TikTok LIVE broadcasts to custom actions within their Minecraft server.
From running in-game commands when a viewer sends a specific gift to displaying on-screen alerts for new followers, TikCraft gives you full control to gamify your streams.
✨ Key Features
Real-time Connection to TikTok LIVE: Monitor comments, gifts, new followers, likes, and more.
Minecraft Integration: Connects to your Minecraft server via a plugin (TAP) to execute any command.
Powerful Action/Event System: Define "Events" (triggers, like a new follower) that execute complex, customizable "Actions."
Streaming Overlays: Generate URLs to use in OBS, Streamlabs, etc., with alerts and event feeds.
Earnings Tracker: A dedicated panel to view diamonds earned per session and in total.
Profile Management: Create multiple configuration profiles, each with its own actions and events. Ideal for different series or stream types!
User Authentication: Save your configurations in the cloud, linked to your account for security and portability.
📚 Detailed Feature Guide
1. Event-Action System (The Heart of TikCraft)
The main logic is based on linking TikTok Events with in-game or overlay Actions.
Events (Triggers)
You can set up triggers for the following events:
New Follower: Activates when someone starts following you.
Any Gift: Activates with any gift, regardless of which one.
Specific Gift: Activates only when a specific gift you choose from a comprehensive list is received.
Any Comment: Activates when a viewer sends a message in the chat.
Like Goal: Activates each time a number of likes you define is reached (e.g., every 1000 likes).
Actions (Responses)
Once an event is triggered, it executes an Action, which can include one or more of the following responses:
Run Minecraft Commands: Send one or more commands to your server's console. You can use placeholders like {username} to customize the command.
Show Minecraft Title: Display a title and subtitle on all players' screens, with customizable colors.
Play Sound: Choose a sound from an extensive online library or upload your own to be played as an alert.
Play TTS (Text-to-Speech): Convert text to speech. It is fully customizable, allowing you to choose the language, voice, volume, and use placeholders.
Cooldowns: Prevent spam by setting global (for the action) and per-user cooldowns.
Show Overlay Alert: Display a customizable text alert on your streaming overlay.
Play Overlay Video: Display a video (MP4, WEBM) on your streaming overlay.
2. Minecraft Integration (TAP Server)
In the Configuration tab, you can connect the application to your Minecraft server. This requires a plugin on your server (Spigot/Paper) that opens a port to receive commands (like "The Action Pad" or similar).
Server IP: The address of your Minecraft server.
Port: The port configured in the plugin.
API Key: The security key to authorize commands.
Test Button: To verify that the connection works correctly.
3. Streaming Overlays
TikCraft includes a local web server to generate overlays that you can add as a "Browser Source" in your streaming software.
Alert Overlay: Displays the text, sound, and video alerts configured in your actions.
Gift Feed Overlay: Shows a real-time list of the latest gifts received.
4. Monitoring Panels
Console: A real-time log of all events occurring during the live stream (joins, comments, likes, gifts, etc.), perfect for debugging and monitoring activity.
Earnings:
Historical Total: The sum of all diamonds received since you started using the app (can be cleared).
Current Session: The sum of diamonds received in the current connection session.
Gift History: A detailed list of each gift received, who sent it, and its value.
5. Profile Management
Don't limit yourself to a single configuration.
Create/Rename/Delete Profiles: Organize your configurations for different games, events, or stream types.
Import/Export: Save a backup of your profile or share it with other users. Each profile stores its own actions, events, and TAP server configuration.
6. Authentication and Security
Login: The application requires an account (Email/Password) to operate.
Secure Registration: Includes password validation and a CAPTCHA system to prevent bots.
Account Recovery: An option to reset your password via email.
⚙️ Technologies Used
Framework: Electron
TikTok Connection: tiktok-live-connector
Overlay Server: Express.js & WebSocket (ws)
Authentication: Firebase Auth
Interface: HTML5, CSS3, JavaScript
