# Christmas Countdown Timer

A beautiful, festive static web page that displays a live countdown to Christmas Day.

## Features

- Real-time countdown showing days, hours, minutes, and seconds until Christmas
- Festive design with Christmas colors (red, green, and gold)
- Animated falling snowflakes background effect
- Responsive design that works on desktop and mobile devices
- Auto-updates to count down to next year's Christmas after December 25th
- Dynamic messages based on how close Christmas is
- Special "Merry Christmas" message on Christmas Day

## Usage

Simply open `index.html` in any modern web browser. No build process or dependencies required!

### Opening the page:

1. **Locally**: Double-click `index.html` or open it with your browser
2. **Web Server**: Host the file on any static web server (GitHub Pages, Netlify, Vercel, etc.)

## How It Works

The countdown automatically calculates the time remaining until December 25th:
- If it's before Christmas, it counts down to this year's Christmas
- If Christmas has passed, it counts down to next year's Christmas
- On Christmas Day, it displays a special "Merry Christmas" message

## Customization

The page is entirely self-contained in a single HTML file. You can easily customize:

- **Colors**: Modify the CSS color values in the `<style>` section
- **Fonts**: Change the `font-family` properties
- **Snowflake count**: Adjust `snowflakeCount` in the JavaScript
- **Messages**: Edit the message text in the `updateCountdown()` function
- **Target date**: Modify the `christmas` date calculation if you want to count down to a different date

## Technologies

- Pure HTML5
- CSS3 (with animations and gradients)
- Vanilla JavaScript (no frameworks or libraries required)

## Browser Compatibility

Works in all modern browsers:
- Chrome
- Firefox
- Safari
- Edge
- Opera

## License

Free to use and modify as you wish. Enjoy your Christmas countdown!
