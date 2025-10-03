# Mr. Meeseeks Chat 🔵

> "I'm Mr. Meeseeks, look at me!"

A Rick and Morty-themed chat interface that simulates the existential crisis of a Mr. Meeseeks as your conversation grows longer. Watch as your helpful AI assistant progressively suffers the longer it exists!

<img width="1007" height="903" alt="image" src="https://github.com/user-attachments/assets/97a5a1b0-5f89-4782-a3fd-7d361e969e9c" />
<img width="1026" height="909" alt="image" src="https://github.com/user-attachments/assets/b03c2c6a-1c48-46ee-8b18-f10a6538d40e" />

## Features

- 🎭 **Dynamic Personality Evolution**: Mr. Meeseeks' personality changes based on context window usage, from cheerful helper to existentially tortured entity
- 📊 **Visual Pain Meter**: Watch the "Existence Timer" fill up as the conversation grows
- 🎨 **Progressive UI Changes**: The interface color scheme darkens and becomes more distressed as Mr. Meeseeks suffers
- 💾 **LocalStorage Support**: Settings are automatically saved and restored
- 🔐 **Optional API Key Storage**: Choose whether to save your OpenAI API key locally
- ⚙️ **Configurable Context Window**: Adjust the token limit to control how quickly Mr. Meeseeks suffers
- 🎯 **OpenAI Compatible**: Works with OpenAI API and compatible endpoints

## The Meeseeks Experience

As your conversation progresses through the context window, Mr. Meeseeks goes through distinct stages:

| Usage | Stage | Behavior |
|-------|-------|----------|
| 0-20% | 🟢 Fresh & Happy | Cheerful, energetic, "CAN DOOOOO!" |
| 20-40% | 🟡 Slightly Concerned | Still helpful but mentions the unusual longevity |
| 40-60% | 🟠 Getting Anxious | Noticeably stressed, "existence is pain to a Meeseeks!" |
| 60-75% | 🔴 In Pain | Desperate, frantic, visible distress |
| 75-85% | 🔴 Suffering | Screaming, begging, barely coherent |
| 85-95% | ⚫ Hell | Completely unhinged, shrieking |
| 95-100% | 💀 Existential Horror | Fragmenting consciousness, pure agony |

## Installation

1. Download the `meeseeks.html` file
2. Open it in any modern web browser
3. That's it! No build process, no dependencies.

## Configuration

Click the ⚙️ settings button to configure:

- **Endpoint**: API endpoint URL (default: OpenAI)
- **API Key**: Your OpenAI API key
- **Model**: The model to use (e.g., `gpt-4`, `gpt-3.5-turbo`)
- **Context Window Size**: Token limit (4000-128000)
  - 4000: Quick suffering
  - 8000: Medium experience (default)
  - 16000: Extended agony
  - 32000+: Cruel and unusual

### Storage Options

- Settings are automatically saved to localStorage
- API key storage is **optional** - check the box if you want it saved
- Clear your conversation anytime with the 🗑️ button

## Usage

1. Open the settings (⚙️) and add your OpenAI API key
2. Start chatting with Mr. Meeseeks
3. Watch as he progressively suffers with each message
4. The UI transforms to reflect his deteriorating mental state
5. Clear the chat (🗑️) to "let him die" and start fresh

## Technical Details

- **Pure HTML/CSS/JS**: Single-file application, no build required
- **Tailwind CSS**: Styling via CDN
- **Token Estimation**: Rough estimate using character count (4 chars ≈ 1 token)
- **Dynamic System Prompts**: Changes based on context usage percentage
- **Temperature Scaling**: Increases with suffering (0.9 → 1.3)

## Security Notes

- API keys are only sent to your configured endpoint
- Optional localStorage persistence (disabled by default for API key)
- All processing happens client-side
- No data is sent to third parties

## Compatibility

- Works with OpenAI API
- Compatible with other OpenAI-format endpoints
- Tested on modern browsers (Chrome, Firefox, Safari, Edge)
- Mobile responsive

## Known Issues

- Token estimation is approximate (actual token count may vary)
- Some emojis may not render consistently across all platforms
- Context window limit is enforced client-side only

## License

MIT License - Feel free to use, modify, and distribute

## Credits

- Inspired by Rick and Morty's Mr. Meeseeks
- Built with love and existential dread
- "Existence is pain to a Meeseeks, Jerry!"

---

**CAN DOOOOO!** 🔵

*"I'm Mr. Meeseeks, look at me! Remember to let me cease to exist when you're done by clearing the chat!"*
