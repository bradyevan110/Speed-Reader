# ⚡ Speed Reader

A modern, web-based speed reading application that displays one word at a time at a fixed focal point. Perfect for improving reading speed and comprehension through Rapid Serial Visual Presentation (RSVP).

## Features

✨ **Core Functionality**
- One word at a time display at a fixed focal point
- Adjustable reading speed (50-1000 words per minute)
- PDF file upload support
- Copy and paste text input
- Pause/Resume functionality

🎨 **Customization Options**
- Adjustable word size (24px - 120px)
- Customizable word color
- Customizable background color
- Real-time progress tracking
- Reading time estimation

⌨️ **Keyboard Shortcuts**
- `Space` - Pause/Resume reading
- `←` (Left Arrow) - Go to previous word
- `→` (Right Arrow) - Go to next word
- `+` or `=` - Increase reading speed
- `-` or `_` - Decrease reading speed

## How to Use

### Getting Started

1. **Open the Application**
   - Simply open `index.html` in any modern web browser (Chrome, Firefox, Edge, Safari)
   - No installation or setup required!

2. **Add Your Text**
   - **Option 1**: Click "📎 Upload PDF File" to upload a PDF document
   - **Option 2**: Paste your text directly into the text area

3. **Customize Settings** (Optional)
   - Adjust reading speed using the slider (50-1000 WPM)
   - Change word size to your preference
   - Pick your favorite word and background colors

4. **Start Reading**
   - Click the "▶ Start" button or press `Space`
   - Watch as words appear one at a time at the center focal point
   - Use `Space` to pause/resume anytime

### Tips for Best Results

- **Start Slow**: Begin with 200-300 WPM and gradually increase
- **Focus**: Keep your eyes on the center focal point - don't move them
- **Practice**: Regular practice improves reading speed over time
- **Comfort**: Adjust colors and size to reduce eye strain
- **Pause When Needed**: Use pause to take breaks or review content

## Technical Details

### Requirements
- Modern web browser with JavaScript enabled
- Internet connection (for loading PDF.js library from CDN)

### Browser Compatibility
- ✅ Chrome/Edge (recommended)
- ✅ Firefox
- ✅ Safari
- ✅ Opera

### How It Works
- The application uses **PDF.js** (Mozilla's PDF library) to extract text from PDF files
- Text is split into individual words
- Words are displayed sequentially using JavaScript timers
- All words appear at the same fixed position to minimize eye movement
- Settings are applied in real-time without page refresh

## File Structure

```
speedreader/
├── index.html          # Main application file (everything in one file!)
└── README.md          # This file
```

## Troubleshooting

**PDF won't load?**
- Make sure the PDF file is not corrupted
- Try a different PDF file
- Some scanned PDFs (image-based) may not extract text properly

**Text not appearing?**
- Make sure you've either uploaded a PDF or pasted text
- Check that the text area or PDF file contains actual text

**Reading too fast/slow?**
- Use the speed slider to adjust (50-1000 WPM)
- Use keyboard shortcuts `+` and `-` for quick adjustments

**Colors not changing?**
- Make sure you've selected a color using the color picker
- Changes apply immediately to new words

## Future Enhancements (Optional)

If you want to extend this application, here are some ideas:
- Save favorite settings
- Export reading statistics
- Support for multiple languages
- Word chunking (2-3 words at a time)
- Reading history
- Dark mode toggle

## Credits

- Built with vanilla JavaScript, HTML, and CSS
- PDF parsing powered by [PDF.js](https://mozilla.github.io/pdf.js/) by Mozilla
- Modern UI design with gradient backgrounds and smooth animations

## License

Free to use and modify for personal or educational purposes.

---

**Enjoy faster reading!** 📚⚡

