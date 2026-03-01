# 🎓 QuickNotes Generator - Features Guide

## 📋 Core Learning Features

### 📝 Smart MCQ Generation
- **6 Question Types**: Single choice, True/False, Multiple select, Fill-in-blank, Scenario, Comparison
- **3 Difficulty Levels**: Easy ⭐, Medium ⭐⭐, Hard ⭐⭐⭐
- **Intelligent Distractors**: AI-powered wrong answers using multiple strategies
- **Customizable Count**: Generate 3-20 questions per quiz

### 🎴 Flashcard Study Mode
- **Interactive Cards**: Click to flip between concept and definition
- **Learning Classification**: Mark as Familiar 👍, Need Review 🤔, or Difficult ❌
- **Progress Tracking**: See completion percentage as you study
- **Color-Coded Content**: Identify definitions, examples, key points, and critical concepts

### 🧠 Mind Map Visualization
- **Concept Mapping**: Central concept with related topics
- **Visual Learning**: Understand concept relationships
- **Content Type Labels**: Identify different types of information

### 📋 Auto-Generated Summaries
- **3 Tab Organization**:
  - 🔑 Key Points - Important concepts
  - 📚 Definitions - Term explanations
  - 🔗 Relationships/Examples - Related concepts and usage

---

## ⏱️ Time Management Features

### ⏰ Quiz Timer
- **Visual Countdown**: See time remaining during quiz
- **Warning Indicators**: Color changes as time runs out
- **Unlimited Mode**: Default unlimited time (∞)
- **Session Duration**: Track total study session time

### 🍅 Pomodoro Timer
- **Focus Time**: Default 25 minutes (customizable)
- **Break Time**: Default 5 minutes (customizable)
- **Visual Display**: Large, easy-to-read countdown
- **Progress Bar**: See focus/break progress
- **Sound Notifications**: Audio alerts when sessions complete (optional)
- **Statistics**: Track pomodoros completed per day

#### Pomodoro Features
- Start/Pause controls
- Skip to next session
- Adjustable durations
- Sound toggle on/off
- Daily completion counter

---

## 📊 Performance Tracking & Analytics

### 📈 Performance Dashboard
- **Overall Statistics**:
  - Total quizzes completed
  - Average score across all quizzes
  - Best quiz score achieved
  - Total study time (hours:minutes)
  
- **Concept Mastery**:
  - Individual concept accuracy percentages
  - Visual mastery bars (0-100%)
  - Top 5 most studied concepts
  
- **Study Streak**:
  - Consecutive days of studying
  - Streak visualization
  - Reset option available
  
- **Study Timeline**:
  - Recent quiz history
  - Date and score tracking
  - Progress visualizer

### 💾 Data Management
- **Export Statistics**: Download performance data as JSON
- **Clear Data**: Reset all statistics (with confirmation)
- **Save History**: Automatic quiz history preservation
- **Local Storage**: All data stored securely on device

---

## 🎯 Quiz Enhancement Features

### 💡 Confidence Rating
- **3-Level Confidence**: Not sure 😞 / Somewhat sure 🤔 / Very sure 😊
- **Per-Question Tracking**: Rate confidence for each answer
- **Visual Feedback**: Selected confidence level highlighted
- **Progress Preservation**: Confidence ratings saved when switching questions

### 🔖 Bookmarking System
- **Mark Questions**: Star important questions with 🔖 icon
- **Quick Review**: Create custom quiz from bookmarked questions
- **Bookmark List**:
  - View all bookmarked questions
  - See question text and answer status
  - Remove individual bookmarks
  - Quick navigation to specific questions
- **Batch Operations**: Clear all bookmarks at once

### 🎲 Question Shuffling
- **Random Order**: Toggle 🔀 to randomize question sequence
- **Preserve Original**: Switch back to original order anytime
- **State Preservation**: Shuffle state maintained during quiz

### ⚡ Quick Review Mode
- **Focused Practice**: Review only bookmarked questions
- **Mini Quiz**: Take a shorter quiz on challenging topics
- **Selective Learning**: Study specific problem areas

---

## 🎵 User Experience Features

### 🔔 Sound Effects & Notifications
- **Beep Sounds**: Audio feedback for interactions using Web Audio API
- **Success Sound**: Positive feedback when answers submitted
- **Error Sound**: Alert for mistakes or incomplete answers
- **Notification Sound**: Alerts for timers and session changes
- **Optional**: Toggle sound on/off in settings

### ⌨️ Keyboard Shortcuts
- **← Arrow Left**: Previous question (when in quiz)
- **→ Arrow Right**: Next question (when in quiz)
- **Ctrl + Enter**: Submit quiz quickly
- **Visual Hints**: On-screen reminder of available shortcuts

### 🌙 Dark Mode
- **Toggle Button**: Moon/Sun icon in top-right corner (🌙/☀️)
- **Full Theme Support**: Dark colors applied across entire app
- **Persistent Setting**: Your dark mode choice saved
- **Eye Comfort**: Reduced brightness for extended study sessions
- **Color Optimized**: Readable text in both light and dark modes

---

## 📤 Import & Export Features

### 📁 File Upload Support
- **Multiple Formats**:
  - `.txt` - Plain text files
  - `.pdf` - PDF documents with text extraction
  - `.docx` - Microsoft Word documents
  - `.md` - Markdown files
  - `.csv` - Spreadsheet data
- **Drag & Drop**: Drag files directly onto upload area
- **Progress Indicator**: See file upload status
- **Auto-Integration**: Content automatically added to notes

### 📥 Export Options
- **JSON Export**: Complete quiz data with metadata
  - Flashcards
  - Questions
  - Concepts
  - Timestamps
  
- **CSV Export**: Spreadsheet-compatible format
  - Concept names
  - Definitions
  - Difficulty levels
  - Content types

- **Performance Statistics**: Download study analytics
  - Quiz scores
  - Study duration
  - Concept mastery
  - Streak information

---

## 🎨 Content Organization

### 🏷️ Color-Coded System
- **Yellow 📖**: Definitions and term explanations
- **Blue 💡**: Examples and real-world usage
- **Green 📌**: Key points and crucial concepts
- **Red ⚠️**: Critical information and must-know facts

### 📝 Content Type Identification
- **Automatic Detection**: System identifies content types from notes
- **Smart Categorization**: Organizes concepts by type
- **Visual Badges**: Color badges show content type at a glance
- **Consistent Marking**: Applied throughout flashcards, summaries, and exports

---

## 🎓 Study Statistics

### Session Metrics
- **Real-Time Tracking**:
  - Session duration timer
  - Study streak counter
  - Current session score

- **Quiz Metrics**:
  - Questions answered
  - Time per question   - Correct/total count
  - Accuracy percentage
  - Difficulty attempted

### Progress Indicators
- **Progress Bar**: Visual quiz completion percentage
- **Question Numbering**: Current/Total display
- **Badge System**: Achievements for performance milestones
- **Weak Concept Tracking**: Identifies areas needing review

---

## 🚀 Advanced Learning Features

### 📚 Spaced Repetition
- **Flashcard Classification**: Familiar/Review/Difficult categories
- **Focus Areas**: Easy identification of weak concepts
- **Mastery Tracking**: See which concepts need more practice

### 🎯 Personalized Learning
- **Difficulty Selection**: Choose quiz difficulty level before starting
- **Custom Question Count**: Select number of questions (3-20)
- **Concept-Based**: Organize by studied concepts
- **Progress Visualization**: Track improvement over time

### 💪 Achievement System
- **5 Badge Types**:
  - 🥇 Perfect Score: All questions correct
  - 🌟 Star Student: 90%+ accuracy
  - 📚 Knowledge Master: 80%+ accuracy
  - 🚀 Quiz Warrior: 5+ quizzes completed
  - 👑 Champion: Perfect quiz in history

---

## 📱 Device Compatibility

### Responsive Design
- **Desktop**: Full feature set on large screens
- **Tablet**: Optimized layout for medium screens (768px+)
- **Mobile**: Adapted interface for small screens (480px+)

### Browser Support
- **Chrome/Brave**: Full support with all features
- **Firefox**: Complete compatibility
- **Safari**: Full support including voice recognition
- **Edge**: Optimized experience
- **Mobile Browsers**: Responsive mobile interface

---

## 🔐 Data Privacy

### Local Storage
- **On-Device Storage**: All data saved locally
- **No Cloud Upload**: Complete privacy guaranteed
- **Manual Backups**: Export data whenever needed
- **Clear Control**: Easy data deletion options

### Settings Persistence
- **Dark Mode Preference**: Saved locally
- **Study History**: Stored for analytics
- **Bookmarks**: Preserved between sessions
- **Performance Stats**: Long-term tracking

---

## 🎁 Bonus Features

- **Voice-to-Text Input**: 🎤 Record notes using microphone
- **Real-Time Transcription**: See what's being recorded
- **Multi-Language Support**: Voice recognition in various languages
- **Focus Mode**: Immersive study environment
- **Concept Auto-Detection**: Identifies and organizes topics automatically

---

## 🌟 Tips for Best Results

1. **Use Detailed Notes**: More content = better questions
2. **Try Different Difficulties**: Challenge yourself progressively
3. **Bookmark Difficult Questions**: Focus on weak areas
4. **Use Pomodoro Timer**: Maintain study focus with breaks
5. **Check Dashboard**: Track progress and motivation
6. **Review Summaries**: Reinforce learning with organized content
7. **Study Flashcards**: Spaced repetition builds long-term memory
8. **Set Daily Streak**: Build consistent study habits
9. **Export Results**: Keep records of your progress
10. **Use Voice Input**: Hands-free note taking for flexibility

---

**Happy Learning! 🎓📚**
