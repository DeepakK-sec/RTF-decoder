Features

1. **Privacy-Focused**: All processing happens in the browser - no data is sent to any server
2. **User-Friendly Interface**:
   - Clean, modern design with gradient accents
   - Responsive layout that works on mobile and desktop
   - Clear input/output panels with helpful placeholder text
3. **RTF Conversion**:
   - Handles basic RTF formatting (bold, italic, underline)
   - Converts special characters and Unicode
   - Preserves paragraph breaks and line breaks
   - Removes RTF control words and formatting codes
4. **Utility Functions**:
   - One-click conversion
   - Clear input/output buttons
   - Copy to clipboard functionality with visual feedback
5. **Educational Elements**:
   - Information panel explaining how the tool works
   - Sample RTF content pre-loaded for demonstration

The solution uses a JavaScript function that processes RTF by:
- Removing RTF control words (sequences starting with \)
- Stripping curly braces used for grouping
- Converting hex-encoded characters (\')
- Handling Unicode characters (\u)
- Converting paragraph and line break commands to actual line breaks
- Cleaning up extra whitespace

Simply paste your RTF content into the left panel and click "Convert to Plain Text" to see the result in the right panel.
