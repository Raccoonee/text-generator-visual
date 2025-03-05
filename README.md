# Text Generator Visual

A visual text generator that creates random text snippets based on content from the TV show "Severance". The generated text is displayed in a visually appealing way with floating text and file icons on a retro computer monitor interface.

## About the Project

This project uses [Tracery](https://github.com/galaxykate/tracery), a JavaScript library for generating text, to create random phrases and statements that mimic the style and vocabulary of the TV show "Severance". The text is displayed on a simulated retro computer monitor with floating text and file icons that fade in and out.

### Features

- Randomly generated text based on "Severance" vocabulary and speech patterns
- Visually appealing retro computer monitor interface
- Interactive elements - click anywhere on the screen to generate new text
- Floating file icons and text with physics-based movement
- Responsive design that works on different screen sizes

## How It Works

The project uses a Tracery grammar defined in `severance_tracery.json` to generate random text. The grammar includes various categories like "innie_statement", "outie_statement", "work_statement", and "lumon_statement", along with lists of nouns, verbs, adjectives, adverbs, pronouns, and proper nouns from the show.

The visual interface is created using HTML, CSS, and JavaScript with the p5.js library for animation and interactive elements.

## Credits

The text content is generated using transcripts from the TV show "Severance" as sourced from the [Severance Wiki](https://severance.wiki/list_of_severance_episodes). The content from the Severance Wiki is licensed under [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/).

## Libraries Used

- [Tracery](https://github.com/galaxykate/tracery) - Text generation
- [p5.js](https://p5js.org/) - Animation and interactive elements
- [jQuery](https://jquery.com/) - DOM manipulation
