# Dealing with lists and navigating... (part 1)

How difficult can it be to display a list of items on the screen and navigate to a detail version of it?

The idea with this exercise is:

- Understanding how a `ListView` of sorts works in react-native.
- Give a quick look at navigation and argument passing between screens.
- Try a new way of organising my code, styles and components.
- Give it a try to flexbox and how it interacts between different components.

A list of things to do would be an interesting way of testing this as:

1. The app should display a list of items to accomplish.
1. Remove those items once done (triggering a state change of sorts).
1. Provide a way to customise the content of the items.

## I want to play with this code

Changing the format as it will be lots of typing from this point onwards... here is a shell script that you can copy and modify to your liking.

```sh
# Cloning the repo to 'todos'
git clone git@github.com:rodrigoelp/reactnative-typescript-exercise-3.git todos
# Changing directory
cd todos/
# Installing dependencies
yarn # if you have not installed yarn, then change it to: npm install
# Compiling the typescript code
./node_modules/.bin/tsc
# Launching the react-native development server
open -a Terminal "`react-native start`"
# Compiling the code for ios and deploying it to the simulator
react-native run-ios # optionally, type: react-native run-android
```

## Learnings achieved with this exercise

1. I need to study a lot more flexbox as there are a few things that I am missing.
1. `FlatList` seems to be pretty flexible.
1. The code structure I chose is horrible and I feel I am fighting a few aspects of how javascript code is organised.
1. Navigation does not work as I expected.
