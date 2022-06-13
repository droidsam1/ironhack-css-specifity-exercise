# ironhack-css-specifity-exercise

For purely educational purposes, I have incread the difficulty of the proposed exercise by trying to refactor the CSS as proposed. 

I have approached *refactoring* in the strict sense, so I needed to add some unit tests before starting to modify the code. 

I have chosen [Backstopjs](https://github.com/garris/BackstopJS/blob/master/README.md#local-installation). as framework to perform *visual regression testing*.

To install run:
```
npm install -g backstopjs
```
To run the test:
```
backstop test
```
Then start a refactoring-like process:
* Run the test ✅
* Modify CSS ✍️
* * If test are green ✅, commit
* * If test are red ❌, revert to previous state
* Repeat 🔁
