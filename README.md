# React Multidropdown Component

This repo is meant to be the template for React.js-based training sessions.

Feel free to contribute adding boilperplate and/or fixing errors and typos.

## Features

Your task is to create a multidropdown React component with the following features:

* must display a customizable default message ("Pick an option", "no option selected", etc) when no option has been chosen yet
* must allow the user to select and display multiple options from a given array (passed as props)
* user must be able to click on it to expand it as a normal dropdown, adding more options to the selected list
* must allow to be mounted with a few options already selected
* each selected item must be removable clicking on a small related icon on the selected icon itself
* style of the container, single options and delete buttons must be customizable
* must support onClick and onChange events; onBlur is a nice extra

## User stories

* I see a default message when I first encounter the multidropdown component in a screen
* on click, it expands and show me a number of options to be selected
* when I click one of them, it disappers from the pop up list of options (unless the optional features down below are implemented) and appears in the selected list
* the list of selected items expands as I pick more
* I can remove each selected item from the visible selected list, by clicking a close/delete button which appears next to each one

## Extra

* write a test suite for it
* Publish it on NPM registry with your own account
* add a link to a testable demo with example code, possibly using GH pages
* add optional prop for the sorting criteria of the selected options (default: no sorting, they are displayed in the picking order)
* add optional prop to let it behave like a dropup
* add optional prop to keep the selected options in the pop up list (instead of removing them), showing them highlighted
* add optional prop depending from the previous one (it is enabled only if the previous one is enabled as well) to allow the user to select an option multiple times

## Tips

* you might wish *not* to use `<select>` and `<option>` tags, as they quite frankly suck in terms of styling across browsers, although one might argue they are more semantically correct
* to implement the pop up part of the dropdown (or dropup) using the `position` attribute might come quite handy
* to publish an npm module, look at [the dedicated guide](https://docs.npmjs.com/getting-started/publishing-npm-packages) and don't forget to pick a catchy name!
