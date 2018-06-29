# Pre-work - *Alfred*

**Name of your app** is an android app that allows building a todo list and basic todo items management functionality including adding new items, editing and deleting an existing item.

Submitted by: **Jean-Michel Kevin**

Time spent: **3** hours spent in total

## User Stories

The following **required** functionality is completed:

* [v] User can **successfully add and remove items** from the todo list
* [v] User can **persist todo items** and retrieve them properly on app restart
* [-] User can **tap a todo item in the list and bring up an edit screen for the todo item** and then have any changes to the text reflected in the todo list.
The following **optional** features are implemented:

* [v] Persist the todo items [into SQLite](http://guides.codepath.com/android/Persisting-Data-to-the-Device#sqlite) instead of a text file
* [v] Improve style of the todo items in the list [using a custom adapter](http://guides.codepath.com/android/Using-an-ArrayAdapter-with-ListView)
* [v] Add support for completion due dates for todo items (and display within listview item)
* [-] Use a [DialogFragment](http://guides.codepath.com/android/Using-DialogFragment) instead of new Activity for editing items
* [-] Add support for selecting the priority of each todo item (and display in listview item)
* [-] Tweak the style improving the UI / UX, play with colors, images or backgrounds

The following **additional** features are implemented:

* [] List anything else that you can get done to improve the app functionality!

## Video Walkthrough

Here's a walkthrough of implemented user stories:

<img src='http://i.imgur.com/link/to/your/gif/file.gif' title='Video Walkthrough' width='' alt='Video Walkthrough' />

GIF created with [LiceCap](http://www.cockos.com/licecap/).

## Project Analysis

As part of your pre-work submission, please reflect on the app and answer the following questions below:

**Question 1:** "What are your reactions to the Android app development platform so far? Compare and contrast Android's approach to layouts and user interfaces in past platforms you've used."

**Answer:** [The plaform is pretty good but uses to much of the ressources].

**Question 2:** "Take a moment to reflect on the `ArrayAdapter` used in your pre-work. How would you describe an adapter in this context and what is its function in Android? Why do you think the adapter is important? Explain the purpose of the `convertView` in the `getView` method of the `ArrayAdapter`."

**Answer:** [The adapter converts an ArrayList of objects into View items loaded into the ListView container. ConvertView is the converted object returned when using the getView usde to describe the translation between the data item and the View to display ].

## Notes

Describe any challenges encountered while building the app.

Because im new to android developpement this whole prework was a challenge to me lol. Cheers.

## License

    Copyright [yyyy] [name of copyright owner]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
