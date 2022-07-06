# World Happiness Score
A fairly simple app made with react and react-globe.gl which uses Three.js under to visualize
worlds happiness and other related social data. based on the example provided by react-globe.gl. check them
out [here](https://github.com/vasturiano/react-globe.gl).

# About the dataset
The World Happiness Report is a publication of the United Nations Sustainable Development Solutions Network. It contains articles and rankings of national happiness, based on respondent ratings of their own lives, which the report also correlates with various (quality of) life factors. As of March 2022, Finland had been ranked the happiest country in the world five times in a row.

The report primarily uses data from the Gallup World Poll. Each annual report is available to the public to download on the World Happiness Report website.The Editors of the 2020 report are John F. Helliwell, Richard Layard, Jeffrey D. Sachs, and Jan-Emmanuel De Neve. Associate Editors are Lara Aknin, Shun Wang, and Haifang Huang. Source : [Wikipedia](https://en.wikipedia.org/wiki/World_Happiness_Report)

>NOTE: Certain Data Points [in the dataset](https://www.kaggle.com/datasets/shivkumarganesh/world-happiness-report-20152022) are available for Certain Years and others are not. So you may find a lot of Columns with plenty of empty data, but I have written a simple Java program to process and combine the data needed to plote and show the report in a map into a json file.So you could check and make a better modifications [here](https://github.com/YohannesTz/JavaDataManuplater.git).

# Preivew
![preview](/globe-preview.png)

[Live Preview](https://world-happines-score.netlify.app/) [Video Preview](https://youtu.be/4gncZzITIiY)

## Available Scripts

In the project directory, you can run:

### `yarn start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

### `yarn test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `yarn build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `yarn eject`

**Note: this is a one-way operation. Once you `eject`, you can't go back!**

If you aren't satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you're on your own.

You don't have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn't feel obligated to use this feature. However we understand that this tool wouldn't be useful if you couldn't customize it when you are ready for it.
