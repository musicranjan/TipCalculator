# Tip Calculator 

## Sangeet Ranjan

**Tippy** computes the tip and total amount for a bill. The app uses the base amount and tip percentage to calculate the amount owed, and it also describes the quality of service based on the tip.

Time spent: **6** hours spent in total

## Functionality 

The following **required** functionality is completed:

* [Y] User can enter in a bill amount (total amount to tip on)
* [Y] User can enter a tip percentage (what % the user wants to tip).
* [Y] The tip and total amount are updated immediately when any of the inputs changes.
* [Y] The user sees a label or color update based on the tip amount. 

The following **extensions** are implemented:

* [Y] Custom colors palette selected
* [Y] List anything else that you did to improve the app functionality or design!
	I did following things to improve the app - 
		a. Changed the content of footer
		b. Changed the content of tip descriptor - added emoji and changed words
		c. Added the functionality of entering number of people and then calculating share amount per person
		d. Changed the color scheme

## Video Walkthrough

Here's a walkthrough of implemented user stories:



<img src='https://im3.ezgif.com/tmp/ezgif-3-561d3ea968aa.gif' title='Video Walkthrough' width='' alt='Video Walkthrough' />


## Notes

Describe any challenges encountered while building the app.

Here are some of the challenges that I faced:
	a. Emulator run: I tried a lot but could not get an emulator to run on my laptop. I borrowed my friend's laptop and it didn't work
			on that either. I tried genymotion as well but that didn't work. I connected my phone finally.
	b. Adding 'Share total Amount among N people' functionality: Adding it was not very difficult. What I struggled with was
		ensuring that 'etShareAmount' goes blank once we delete the content from tvPeople. I was placing that loop at wrong location I guess
		and using return was making the app crash because it was executing 'tvBase' being empty as 'return' as well.

## License

    Copyright [yyyy] [Sangeet Ranjan]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
