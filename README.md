# ionic-react-tailwind-template
Startup project for Ionic React app with Tailwind CSS styles

## Run Project

#### Initial Setup
```
git clone https://github.com/netspie/ionic-react-tailwind-template.git
cd ionic-react-tailwind-template
yarn install
npm install react-router-dom
```

You can replace folder and all occurences of 'ionic-react-tailwind-template' text to your project name.

#### Run
```
yarn start:dev
```

## Configuration

By default the project runs on the web by executing `ionic serve` command.
For additional configuration check package.json/script section
```
{
  ...
  "scripts": {
    "build:css": "postcss tailwind.css -o src/theme/tailwind.css",
    "watch:css": "postcss tailwind.css -o src/theme/tailwind.css -w",
    "start:dev": "concurrently \"yarn watch:css\" \"ionic serve\"",
  ...
}
```

To run on mobile modify start:dev command. Check docs from the links below for more information. 

## Links

https://ionicframework.com/docs/  
[Integrating TailwindCSS and Ionic-React application](https://medium.com/@meeky.ae/integrating-tailwindcss-and-ionic-react-application-c038b95af704#:~:text=To%20integrate%20tailwindCSS%20into%20an,ionic%20app%20that%20uses%20capacitor.&text=Then%20we%20can%20create%20a,ionic%2Dreact%20project%20using%20capacitor.)
