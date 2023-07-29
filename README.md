# YouTube Video Downloader using NodeJS

This mini-project is a Node.js application that allows you to download YouTube videos with their original title. It separately downloads the audio and video, merges them into a single file, and then renames the merged file according to the video information downloaded from YouTube.

## Requirements

- Node.js (>= 12.0.0)
- npm (Node Package Manager)

## Folder Structure

```
/
|-- node_modules/
|-- package.json
|-- package-lock.json
|-- README.md
|-- ytdownloader.js
|-- ytlist.txt
```

## Usage

1. Install the required dependencies:
   ```bash
   npm install
   ```

2. Prepare the `ytlist.txt` file with the YouTube video links you want to download. Each link should be on a new line.

3. Run the script to start downloading and merging the videos:
   ```bash
   node ytdownloader.js
   ```

## Use Cases

1. **Download YouTube Videos**: Use this project to easily download YouTube videos and keep them offline for later viewing.

2. **Separate Audio and Video**: It allows you to download the audio and video of a YouTube video separately, giving you more control over your downloads.

3. **Merge Audio and Video**: The project merges the downloaded audio and video files into a single video file for a seamless viewing experience.

4. **Automatic File Naming**: The downloaded videos are renamed automatically based on their original YouTube video title, ensuring easy identification.

## Contributing

Contributions to this project are welcome! 

## License

This project is licensed under the [MIT License](LICENSE). Feel free to use, modify, and distribute the code for personal and commercial purposes. However, make sure to include the original license text in any copies or derivatives of the project.