<h1>👨‍💻 Image Processng API</h1>
<p>
Image processing api is a clean code and extensible node js project designed to resize images to fit any size . The packet starts to get the required parameters from the link, then  vaildate data request, then starts to check whether the request file exists, and then returns the file from the cache, otherwise it generates a file and then saves it to the cache to get it next time

</p>
<h2>this package debends on </h2>
  <ol>
    <li><a href="typescriptlang.org"> typescript</a> for write strong typed code </li>
    <li><a href="https://expressjs.com/">express</a> for creating serve</li>
    <li><a href="https://prettier.io/">prettier </a> to make your code readable</li>
    <li><a href="https://eslint.org/">eslint</a> for check our code</li>
    <li><a href="https://www.npmjs.com/package/fs-extra">fs-extra</a> file system to manage files</li>
    <li><a href="https://jasmine.github.io/">jasmine</a> for unit testing</li>
    <li><a href="https://sharp.pixelplumbing.com/">sharp</a> for image processing</li>
    <li><a href="https://www.npmjs.com/package/supertest"></a>supertest for testing end points</li>
  </ol>
<h2>how to use this package</h2>

first of all you have to install node in your device, to check your node write


```
npm -v
```


download the package to your pc and open command line then install all packages using
```
npm install
```

congratsulations ☺️ now you installed the project

you can now open this url to resize images http://127.0.0.1:5000/api/image?image=lake&width=400&height=400

you can select height or width that bigger than 0

and select image from default images 
```
['greanland', 'lake', 'palac', 'railway', 'tree']
```
or put your png image in ./images/main dir and use its name

<h2>important commands in project </h2>

to start devoloping run
```
npm run dev
```

to compile project run 
```
npm run build
```

to use prettier run
```
npm run prettier
```

to use eslint run
```
npm run eslint
```

to run unit tisting run
```
npm run test
```

at the end I hope you enjoy my code
