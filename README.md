# NoteCreator

Link to GitHub Repository: https://github.com/CS411-Team-Project/note_creator

## What is NoteCreator ?
The overall idea of NoteCreator is to create a platform which will convert audio and speech of university lectures to text in an easy-to-read document. It is similar to other dictation software applications. NoteCreator will be designed to meet the needs of students. 

## Using NoteCreator
The users must create a personal account and log in to access their own files. When they are logged in, they will have access to the notes they have created. For any note, the user can start the dictation once the file is opened. When the user takes notes, NoteCreator will take the audio of the live lecture, and it will transcibe and, using grammarly, create readable note.

## What NoteCreator Will Be Built With
### APIs to Transcribe and Create Notes
- Twilio API: https://www.twilio.com/docs/usage/api
- VOSK: Offline speech recognition toolkit that will be installed.
- Grammarly API: https://developer.grammarly.com/docs/api/

### Front-End Architecture
- React.js

### Back-End Architecture
- Node.js backend functioning as an API for web app to make calls and get data from
- HTTP Requests: Axios or Ky (npmjs.com/package/ky) or Superagent (npmjs.com/package/superagent)
- Database: SQL or PostgreSQL

## Possible Features
Download Notes: After the note is created, the users can access it online, and also they can download it to keep in their local files.

Alter Notes: After the note is created, the user can access the file and change its content to their personal likings (i.e., font, highlight, etc.)
