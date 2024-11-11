# Story Telling App

A dynamic web application that generates creative stories based on custom characters, genres, and tones. Built with React and Next.js, this app provides an interactive interface for creating and managing characters while generating unique stories through an AI-powered backend.

## Features

- **Character Management**
  - Create, edit, and delete characters
  - Define character names, descriptions, and personalities
  - Visual card-based character display

- **Story Customization**
  - Multiple genre options:
    - 🧙 Fantasy
    - 🕵️ Mystery
    - 💑 Romance
    - 🚀 Sci-Fi

  - Various tone selections:
    - 😊 Happy
    - 😢 Sad
    - 😏 Sarcastic
    - 😂 Funny

- **Real-time Story Generation**
  - Stream-based story delivery
  - Intelligent text processing and formatting
  - Character role summaries

## Technical Features

- Server-side streaming response handling
- Advanced text processing and cleaning
- Responsive design
- Dark mode UI
- Error handling and loading states

## Prerequisites

- Node.js and npm/yarn
- Next.js development environment
- API endpoint for story generation at `/api/chat`

## Installation

1. Clone the repository
2. Install dependencies:
```bash
npm install
# or
yarn install
```

3. Start the development server:
```bash
npm run dev
# or
yarn dev
```

## Usage

1. **Add Characters**
   - Click the "Add Character" button
   - Fill in the character's name, description, and personality
   - Click "Add" to save the character

2. **Edit/Delete Characters**
   - Use the edit (pencil) icon to modify existing characters
   - Use the trash icon to remove characters

3. **Select Story Parameters**
   - Choose a genre from the available options
   - Select a tone for the story

4. **Generate Story**
   - Click the "Generate Story" button
   - Wait for the story to be generated
   - Review the generated story and character summaries

## Component Structure

The main component (`Chat.tsx`) includes:
- State management for characters, story generation, and UI
- Character form handling
- Genre and tone selection
- Story generation and streaming
- Text processing utilities

## Dependencies

- React
- Next.js
- Lucide React (for icons)
- Tailwind CSS (for styling)

## Error Handling

The application includes comprehensive error handling for:
- Story generation failures
- Invalid character data
- Network issues
- Stream processing errors

## Contributing

1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Push to the branch
5. Open a Pull Request

## Notes

- Ensure your API endpoint (`/api/chat`) is properly configured
- The story generation endpoint should support streaming responses
- Character data persistence is not included in this version
