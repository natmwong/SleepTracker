# Android Project 5 - *Sleep Tracker*

Submitted by: **Natasha Wong**

**Sleep Tracker** is a health metrics app that allows users to track their hours and quality of sleep on a daily basis.

Time spent: **4** hours spent in total

## Required Features

The following **required** functionality is completed:

- [X] **At least one health metric is tracked (based on user input)**
  - Chosen metric(s): `Hours of Sleep and Quality of Sleep`
- [X] **There is a "create entry" UI that prompts users to make their daily entry**
- [X] **New entries are saved in a database and then updated in the RecyclerView**
- [X] **On application restart, previously entered entries are preserved (i.e., are *persistent*)**
 
The following **optional** features are implemented:

- [ ] **Create a UI for tracking averages and trends in metrics**
- [ ] **Improve and customize the user interface through styling and coloring**
- [ ] **Implement orientation responsivity**
- [ ] **Add a daily photo feature**

The following **additional** features are implemented:

- [X] Create a "clear all" button to delete all sleep logs from the database and display

## Video Walkthrough

Here's a walkthrough of implemented user stories:

<img src='https://github.com/natmwong/SleepTracker/blob/main/SleepTrackerDemo.gif' title='Video Walkthrough' width='' alt='Video Walkthrough' />

<!-- Replace this with whatever GIF tool you used! -->
GIF created with [ScreenToGif](https://www.screentogif.com/) for Windows

## Notes

I had a problem where only the most recent entry would display on the MainActivity page, but this was solved as I realized I was running the deleteAll() function before adding a new entry.
The solution was to delete the function call and only add the new entry with insert().

## License

    Copyright [2024] [Natasha Wong]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
