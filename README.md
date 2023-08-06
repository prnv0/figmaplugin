# Colorus
Welcome to Colorus – your go-to color palette generator! Unleash creativity with random palettes or input a hex code for a personalized selection. Click to copy hexcodes of five captivating colors for your design endeavors. Elevate inspiration with Colorus – where hues meet innovation!

## Team members
1. Pranav Satish [https://github.com/prnv0L]
2. Abhinand S J [https://github.com/abhinandsj]
## Product walkthrough




https://github.com/prnv0/figmaplugin/assets/117537359/f2294495-16a4-4540-ae0d-89267193f8be




## How it Works ?
In our plugin Colorus, there are two options. On clicking the "Random" button a random color palatte is genrated by mathematically altering the hsl values of a randomly generated hexcode. Alternatively you can input a custom hexcode and generate the adjacent color palattes. Once the palattes are generated the corresponding colors in the color palatte can be copied to the clipboard on a single click which can be used according to the need.




Below are the steps to get your plugin running. You can also find instructions at:

  https://www.figma.com/plugin-docs/plugin-quickstart-guide/

This plugin template uses Typescript and NPM, two standard tools in creating JavaScript applications.

First, download Node.js which comes with NPM. This will allow you to install TypeScript and other
libraries. You can find the download link here:

  https://nodejs.org/en/download/

Next, install TypeScript using the command:

  npm install -g typescript

Finally, in the directory of your plugin, get the latest type definitions for the plugin API by running:

  npm install --save-dev @figma/plugin-typings

If you are familiar with JavaScript, TypeScript will look very familiar. In fact, valid JavaScript code
is already valid Typescript code.

TypeScript adds type annotations to variables. This allows code editors such as Visual Studio Code
to provide information about the Figma API while you are writing code, as well as help catch bugs
you previously didn't notice.

For more information, visit https://www.typescriptlang.org/

Using TypeScript requires a compiler to convert TypeScript (code.ts) into JavaScript (code.js)
for the browser to run.

We recommend writing TypeScript code using Visual Studio code:

1. Download Visual Studio Code if you haven't already: https://code.visualstudio.com/.
2. Open this directory in Visual Studio Code.
3. Compile TypeScript to JavaScript: Run the "Terminal > Run Build Task..." menu item,
    then select "npm: watch". You will have to do this again every time
    you reopen Visual Studio Code.

That's it! Visual Studio Code will regenerate the JavaScript file every time you save.
