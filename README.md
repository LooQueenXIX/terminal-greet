# terminal-greet
Script on JavaScript, that makes random greet message in terminal when you open it!

Just edit messages in greetings.js file and type in your bash/zsh config: 
    
    node ~/way/to/script/greetings.js

Aaand that's all, just launch any terminal and script will run automatically!

If you wanna change text color or add some effects fot message you can use this style/color references:
 
 Reset = "\x1b[0m"
 Bright = "\x1b[1m"
 Dim = "\x1b[2m"
 Underscore = "\x1b[4m"
 Blink = "\x1b[5m"
 Reverse = "\x1b[7m"
 Hidden = "\x1b[8m"

 FgBlack = "\x1b[30m"
 FgRed = "\x1b[31m"
 FgGreen = "\x1b[32m"
 FgYellow = "\x1b[33m"
 FgBlue = "\x1b[34m"
 FgMagenta = "\x1b[35m"
 FgCyan = "\x1b[36m"
 FgWhite = "\x1b[37m"
 FgGray = "\x1b[90m"

Just add variabels with style/color like that:

let magnetta = '\x1b[36m';  //start color
let end = '\x1b[0m';        //end color

And surround your message with that variabels.
