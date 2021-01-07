# Prework
# Pre-work - Tip Calculator

Tip Calculator is a tip calculator application for iOS.

Submitted by: Caroline Hernandez

Time spent: 10 hours spent in total

## User Stories

The following **required** functionality is complete:

* [X] User can enter a bill amount, choose a tip percentage, and see the tip and total values.
* [X] User can select between tip percentages by tapping different values on the segmented control and the tip value is updated accordingly

The following **optional** features are implemented:

* [ ] UI animations
* [ ] Remembering the bill amount across app restarts (if <10mins)
* [ ] Using locale-specific currency and currency thousands separators.
* [ ] Making sure the keyboard is always visible and the bill amount is always the first responder. This way the user doesn't have to tap anywhere to use this app. Just launch the app and start typing.

The following **additional** features are implemented:

- [ ] List anything else that you can get done to improve the app functionality!
* [X] Updated design
* [X] Display dollar amounts to split the bill for up to four people. 

## Video Walkthrough

GIF 
![](https://i.imgur.com/dnoUstT.gif)


## Notes

Describe any challenges encountered while building the app.
I kept running into problems when I tried to change the label name for tip label, total label, splitting the check between 2, 3, 4 people where if I changed the storyboard to initially show $0.00 then these features wouldn't work properly. The dollar amount would come up as a single digit then just dots... 
To fix this issue I called calculateTip in the viewDidLoad function passing in 0 to automatically set those values to all be $0.00.

## License

    Copyright [2021] [Caroline Hernandez]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.

