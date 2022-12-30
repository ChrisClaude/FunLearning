# Real Time Collab
## Introduction
RT Collab is a software that allows multiple users to collaborate in real time. This is a clone of menti.com. The main functionality we want to provide is to allow users to create quizzes and share these with one or more users and then allow them to complete them in real time. A quiz begins with a trigger from its creator and all participants complete them at the same time. For instance, imagine you have students in a classroom, and you would like to find out how much they learnt from the previous session. You can create a quiz of questions with different formats (multiple potential answers where only one is correct or where they would need to select all that applies). All connected users will begin the quiz at the same time. As participants answer questions, they are awarded points when the answer is correct. The tool will also aim at allowing users to create presentations, upload PowerPoint files and design presentation templates.

The tool will also help with taking notes. This will be a OneNote type of functionality.

The following are the features we want to include:

1. Allow quizzes between multiple devices
  a. The quizzes should be presented as slide shows
  b. It has real time updates on all participating devices (Use WebSocket)
2. Allow peer to peer file sharing (use WebRTC)
 a. Users should be able to share files between them without requiring a server to sit in between
3. Allow users to upload PowerPoint slides and create slideshow from uploaded file
4. Allow users to share a slide show link where users can connect and participate in a presentation in real time
5. Allow users to connect anonymously from their devices
6. Allow users to authenticate with their Google/Microsoft Account

## Quick start

## How to contribute

## License
RTCollab is [MIT Licensed](./LICENSE)