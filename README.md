This code will help transcribe most YouTube videos (some have restrictions) by using the "base" version of OpenAI's Whisper model. You must provide a YouTube link as an input; the output transcription will be saved as a .txt file in system directory.

I ran this locally on my MacBook Pro with M1 chip.

For Macs:
You simply need to install ffmpeg via Homebrew. Here's the code-
brew install ffmpeg

For Windows:
To install FFmpeg on Windows, follow these steps:

1. Download FFmpeg:
   - Visit the official FFmpeg website (https://ffmpeg.org/download.html)
   - Scroll to the "Windows Builds" section
   - Click on the "Windows builds from gyan.dev" link
   - Download the "ffmpeg-git-full.7z" file for your system (64-bit or 32-bit)[1][5]

2. Extract the files:
   - Create a folder named "ffmpeg" in your C: drive
   - Extract the downloaded .7z file contents into this folder[1][2]

3. Add FFmpeg to the system PATH:
   - Open "Edit the system environment variables" from the Windows search bar
   - Click "Environment Variables"
   - Under "System variables", find and select "Path", then click "Edit"
   - Click "New" and add the path to the FFmpeg "bin" folder (e.g., C:\ffmpeg\bin)
   - Click "OK" to close all windows[1][3][5]

4. Verify the installation:
   - Open a new Command Prompt
   - Type "ffmpeg -version" and press Enter
   - If installed correctly, you'll see the FFmpeg version information[1][4]

Remember to restart your computer after making changes to the system PATH[1]. This process allows you to use FFmpeg from any location in the command prompt for various audio and video processing tasks[1][6].

Citations:
[1] https://transloadit.com/devtips/how-to-install-ffmpeg-on-windows-a-complete-guide/
[2] https://ottverse.com/install-and-use-ffmpeg-on-windows/
[3] https://phoenixnap.com/kb/ffmpeg-windows
[4] https://www.geeksforgeeks.org/how-to-install-ffmpeg-on-windows/
[5] https://www.hostinger.com/tutorials/how-to-install-ffmpeg
[6] https://www.youtube.com/watch?v=JR36oH35Fgg
[7] https://www.editframe.com/guides/how-to-install-and-start-using-ffmpeg-in-under-10-minutes
