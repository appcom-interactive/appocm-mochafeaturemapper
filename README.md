# Mocha feature map
<!-- section: Introduction -->
<!-- Describe briefly what your module / library is. What problem does it solve? What can you use it for? At what target audience is it aimed? -->
This is a tool for mapping mocha tests to features. Software projects consist of multiple features to work. In order to 
measure test coverage (or other useful metrics) by feature, one have to map test cases to features. This is a tool for doing so.
This will generates a mapping file, which can be used to give you information, which test cases relates to certain features. 

## Usage
<!-- section: Usage -->
<!-- Show how to use it with a code example. Focus on the key features and do not include too much (that is for the Wiki). Also do not delve into the API to much. We'll get to that -->
``` 
mfm init # creates .mfmrc
```

``` 
mfm metrics # creates metrics result
```

## API
<!-- section: API -->
<!-- Describe the API of your module / library such that other developers know how to interact with it. -->

## Installation
```
npm i -g mocha-feature-map 
```

## Contributing
Bug reports and pull requests are welcome on GitHub at [https://github.com/appcom-interactive/appocm-mochafeaturemapper](https://github.com/appcom-interactive/appocm-mochafeaturemapper). This project is intended to be a safe, welcoming space for collaboration, and contributors are expected to adhere to the Contributor Covenant code of conduct.

## License
``` 
The MIT License (MIT)
Copyright (c) 2020 appcom interactive GmbH

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.
IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM,
DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR
OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE
OR OTHER DEALINGS IN THE SOFTWARE.

```
