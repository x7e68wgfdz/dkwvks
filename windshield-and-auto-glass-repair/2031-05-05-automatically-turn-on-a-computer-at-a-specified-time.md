---
title: "Automatically Turn on a Computer at a Specified Time"
date: 2031-05-05 20:38
author: Sofia Bennett
---

# Automatically Turn on a Computer at a Specified Time

Skip to Content Quizzes PRO Courses Hot Guides  Tech Help Pro  Expert Videos  About wikiHow Pro  Upgrade  QUIZZES All Quizzes Hot Love Quizzes  Personality Quizzes  Trivia Quizzes  Taylor Swift Quizzes  EXPLORE

Tech Help ProAbout UsRandom ArticleQuizzes

Request a New ArticleCommunity DashboardTrendingForums

Arts and EntertainmentArtworkBooksMovies

Computers and ElectronicsComputersPhone SkillsTechnology Hacks

HealthMen's HealthMental HealthWomen's Health

RelationshipsDatingLoveRelationship Issues Hobbies and CraftsCraftsDrawingGames

Education & CommunicationCommunication SkillsPersonal DevelopmentStudying

Personal Care and StyleFashionHair CarePersonal Hygiene

QuizzesLove QuizzesPersonality QuizzesFun Games

Arts and EntertainmentFinance and BusinessHome and GardenRelationship Quizzes

Cars & Other VehiclesFood and EntertainingPersonal Care and StyleSports and Fitness

Computers and ElectronicsHealthPets and AnimalsTravel

Education & CommunicationHobbies and CraftsPhilosophy and ReligionWork World

Family LifeHolidays and TraditionsRelationshipsYouth LOG IN Log in

Social login does not work in incognito and private browsers. Please log in with your username or email to continue. Facebook Google wikiHow Account No account yet? Create an account RANDOM Home Random Browse Articles TrendingNew Quizzes & Games All QuizzesHot Love Quizzes Personality Quizzes Fun Games Dating Simulator Learn Something New Forums Courses Happiness Hub Explore More Support wikiHow About wikiHow Log in / Sign up Terms of Use

wikiHow is where trusted research and expert knowledge come together. Learn why people trust wikiHow Categories Computers and Electronics Maintenance and Repair System Maintenance and Repair

3 Ways to Schedule a PC or Mac to Turn On Automatically Download Article Schedule a PC or Mac to turn itself on Written byMegaera Lorenz, PhD

Last Updated: August 19, 2026Fact Checked Download Article Using the BIOS (PC) | Using Task Scheduler (Windows) | Using a Mac | Video | Q&A | Tips | Warnings |Show more|Show less X

This article was co-authored by wikiHow staff writer, Megaera Lorenz, PhD. Megaera Lorenz is an Egyptologist and Writer with over 20 years of experience in public education. In 2017, she graduated with her PhD in Egyptology from The University of Chicago, where she served for several years as a content advisor and program facilitator for the Oriental Institute Museum’s Public Education office. She has also developed and taught Egyptology courses at The University of Chicago and Loyola University Chicago. 

This article has been fact-checked, ensuring the accuracy of any cited facts and confirming the authority of its sources. 

This article has been viewed 550,247 times.  Learn more...

[Automatically Turn on](https://automatically-turn-on.curblist.xyz/automatically-turn-on/20260826.html)

This wikiHow teaches you how to make your PC or Mac computer start up at a specific time. If you're using a PC running any operating system (Windows or Linux), you can schedule automatic startups in the system BIOS. You can also use Task Scheduler in Windows to wake your computer from sleep at specific times. If you're using a Mac, you can set up automatic boot-ups using a special command in Terminal. Unfortunately, there’s no way to set a Chromebook to start up automatically if it’s powered down. How to Schedule Computer Startup Times

For PCs, reboot your computer into BIOS and use the “Power on Alarm” or “RTC Alarm” option to set a power-on time.

You can also schedule your Windows computer to wake from sleep using the Task Scheduler.

On macOS, use the pmset command in Terminal to turn on or wake your Mac at specific times. Steps Method 1 Method 1 of 3: Using the BIOS Settings on a PC Download Article 1

Reboot your PC into the BIOS. The option to start your PC on a particular schedule is available in the BIOS, which you can access by pressing a specific key at boot time. This key is usually Del, F8, F12, or F10. If you're using a newer Windows 10 or 11 PC, try using these steps to enter the BIOS:[1]XResearch source

Right-click the Start menu and select Settings.

Click System (Windows 11) or Update & Security (Windows 10). Click Recovery.

Click Restart Now under "Advanced Startup."

When the computer comes back up, click the Troubleshoot menu. Click Advanced Options

Click UEFI Firmware Settings and click Restart. 2

Navigate to Power on Alarm or RTC Alarm option. The name of this menu varies by manufacturer and may be in a menu called Advanced, Power Management, or something similar.

Other possible names for the setting you’re looking for include Wake up by RTC Alarm or RTC Wake.

RTC stands for “Real Time Clock,” which is a piece of hardware that most modern PCs have integrated into their motherboards. Advertisement 3

Enable the RTC Wake option. Once you find the setting for the RTC Wake/Power on Alarm, you might need to set it to “enabled.” Look for a toggle switch or a similar setting to turn it on. 4

Select a schedule frequency. The steps to do this vary by PC, but you'll usually use the arrow keys on the keyboard to highlight the day of the week on which you want the computer to start at a certain time, then press a key to toggle on Enable or Disable for that day.

Depending on the BIOS, you may have the option to choose a broader option like Every Day. 5

Enter the time you want the PC to power on. You'll usually use the arrow keys to select an option called Time, though some BIOS settings require you to enter the hour, minute, and second separately.[2]XResearch source 6

Save your changes and exit the BIOS. If your BIOS has a menu running along the top of the screen, you can usually save and exit by selecting the File menu and choosing Save Changes and Exit. If not, the Save or Save and Close key should be clearly marked on the screen. Once you've exited the BIOS, the PC will restart as normal, and your changes will be saved.[3]XResearch source Advertisement Method 2 Method 2 of 3:

Setting Wake Times in Task Scheduler (Windows) Download Article 1

Open the Task Scheduler. This method won’t actually boot your computer up if it’s fully powered down, but it will wake your computer from sleep at a specified time. To get started, type task scheduler into the Start menu search bar, then launch Task Scheduler from the results. 2

Select Action > Create Task. Click Action in the menu bar at the top of the Task Scheduler, then choose Create Task. A new window will open. 3

Give your task a name. Pick something easily recognizable, like “Wake Up.” 4

Set the security options and configuration for the task. Under the Security Options header, click the radio button next to “Run whether user is logged on or not.” Then, check the box next to “Run with highest privileges.” Finally, click the “Configure for:” drop-down and select Windows 10 (even if you are using Windows 11). 5

Click the Triggers tab. It’s at the top of the Create Task window. 6

Click New. It’s in the bottom left corner of the window. 7

Set the task to begin on a schedule. This option may be selected by default. If not, click the drop-down next to “Begin the task:” and select On a schedule. 8

Set a schedule for your task. Use the options in the Settings section of the window to specify when you want your task to happen. For instance, you could select “One time,” then set a start date and time, or set the task to run daily, weekly, or monthly at a specific time. When you’re done, click OK. 9

Click the Actions tab. It’s at the top of the Create Task window. 10

Click New and select an action. You can really select any action for this purpose, but “Start a program” is the easiest. Click Browse to select the program you want to launch at wake (e.g., your favorite browser). When you’re done, click OK. 11

Click the Conditions tab. You’ll find it at the top of the Create Task window. 12

Check the box next to “Wake the computer to run this task”. This is under the Power header. If you want, you can also uncheck the option to only start the task if your computer is plugged in. Click OK.

If prompted to do so, sign in with the password for your admin account. Note: You will need to enter the password for the Microsoft account associated with your computer, not the passcode you use to log in at startup.

To avoid this, you can open the Task Scheduler as an administrator. Right-click the program in the Start menu and select Run as administrator. 13

Check your power settings. You might need to take a few additional steps to make sure your computer is able to wake up with the command from Task Scheduler. To do this:

[Turn on Computer](https://turn-on-computer.northlist.shop/turn-on-computer/2026082613.html)

In the Start menu search bar, search for power options and select Edit Power Plan. Click Change advanced power settings.

In the new window that opens, expand Sleep > Allow wake timers.

Use the dropdowns to enable both “On battery” and “Plugged in.” Click OK to save your settings. Advertisement Method 3 Method 3 of 3: Using a Mac Download Article 1

[Automatically Turn on Computer](https://automatically-turn-on-computer.curblist.xyz/automatically-turn-on-computer/20260826.html)

[Computer at Specified Time](https://computer-at-specified-time.curblist.xyz/computer-at-specified-time/2026082675.html)

Open the Terminal. It used to be possible to schedule sleep and wake times in your Mac’s settings, but that option has since been removed. Luckily, you can still do this on any version of macOS using Terminal, which is your Mac’s command line interface.[4]XResearch source Launch it from Applications > Utilities, or click the

Spotlight search icon at the top of your screen and search for terminal.[5]XResearch source 2

Enter a pmset command specifying what you want your Mac to do. There are several variants of the pmset command. For example, you can set your Mac to wake up from sleep at a certain time every day, or set it to start up from a powered-down state. For example, if you wanted your Mac to wake up every Monday at 9:00 AM, you’d use the command sudo pmset repeat wake M 9:00:00. When you’re done, press Return to execute the command.[6]XResearch source Here’s how to configure the command properly:

Start the command with sudo pmset. Including “sudo” will prompt your computer to run the command with root/superuser privileges.

[How to Remove Lizards from Your House + Keep Them Away](https://github.com/vc43cc3sdp/eatdqya/blob/main/residential-cleaning/2030-09-24-how-to-remove-lizards-from-your-house-keep-them-away.md)

Follow the command with repeat if you want it to run on a repeating schedule (e.g., every Tuesday evening).

Enter the specific type of command next. In our example, we used wake (to wake your Mac from sleep), but you can also use poweron to turn on your Mac or wakeorpoweron to either wake or boot up your Mac, depending on its current state.

Enter your time settings. There are a few ways to do this.

For instance, you could set a specific date and time for the command to be executed using the format MM/dd/yy HH:mm:ss.

Or, combine the time with a day or a series of days. For example, HH:mm:ss MTWRF. (If you want to include weekends, use S for Saturday and U for Sunday).

See this document for a full list of commands and arguments. 3

Enter your admin password when prompted. After you press Return, you may be prompted to enter the admin password for your Mac. You won’t be able to see the password as you type it. When you’re done, press Return again.

To see your current schedule, use the command pmset -g sched.

To cancel your power management schedule, use the command sudo pmset repeat cancel. Advertisement Community Q&A  Search Add New Question Question

Is there a way to make a network computer activate? Community Answer

It depends what you mean by activate. If you mean power on, then yes. Check the computer's BIOS for "Wake on Lan" settings. Then through an app or other magic packet software, you can send a signal that will turn the computer on. These settings will keep the network interface powered on while the rest of the computer is off.  Thanks! We're glad this was helpful. Thank you for your feedback.

If wikiHow has helped you, please consider a small contribution to support us in helping more readers like you. We’re committed to providing the world with free how-to resources, and even $1 helps us in our mission.  Support wikiHow  YesNo Not Helpful 1Helpful 8 Ask a Question 200 characters left

Include your email address to get a message when this question is answered. Submit Advertisement Video Tips

If your computer is on a network (e.g., at your job), the network administrator can set it up to start automatically at certain times using Wake-on-Lan. This involves sending a “magic packet” to your computer over the network to start it up remotely. Thanks Helpful 0 Not Helpful 0

Chromebooks don’t have a built-in Real Time Clock like PCs, so there’s no way to schedule startup times in BIOS. However, if you have a Chromebook that’s managed by your school or workplace, whoever manages it can set it to sleep or wake up at specific times. Thanks Helpful 0 Not Helpful 0

The BIOS settings on some Windows computers will allow you to schedule a start-up time, but this is not a consistent setting across Windows machines. Thanks Helpful 0 Not Helpful 0 Submit a Tip 

All tip submissions are carefully reviewed before being published Name 

Please provide your name and last initial Submit Thanks for submitting a tip for review!  Advertisement Warnings

If you don't have administrator access on a Windows computer, you will be unable to create a task that starts up your computer. Thanks Helpful 1 Not Helpful 1 Advertisement You Might Also Like How to Build a Computer How to Troubleshoot Computer Startup Problems How to

Schedule a Shutdown for Your PC or Mac Computer

Set Your Computer to Boot from a USB Flash Drive How to Boot a PC or Mac from a CD or DVD How to

Change Computer BIOS Settings on Windows: Easy Guide How to

Change the Computer Time and Date Using the Command Prompt How to

Boot from an External HDD or SSD: Step-by-Step Guide How to Turn Off a Personal Computer How to

Find out How Long Your Computer Has Been On How to

Access the BIOS on Any PC: Guide + Troubleshooting How to

Lock Your Computer With or Without a Password (PC & Mac) Advertisement References

↑https://www.asus.com/us/support/faq/1008829/

↑https://www.maketecheasier.com/schedule-windows10-shut-down-start-up/

[Automatically Turn on](https://automatically-turn-on.northlist.shop/automatically-turn-on/202608262746.html)

↑https://www.maketecheasier.com/schedule-windows10-shut-down-start-up/

↑https://support.apple.com/guide/mac-help/schedule-your-mac-to-turn-on-or-off-mchl40376151/mac

↑https://support.apple.com/guide/mac-help/schedule-your-mac-to-turn-on-or-off-mchl40376151/mac

↑https://support.apple.com/guide/mac-help/schedule-your-mac-to-turn-on-or-off-mchl40376151/mac About This Article Written by:  Megaera Lorenz, PhD wikiHow Staff Writer

This article was co-authored by wikiHow staff writer, Megaera Lorenz, PhD. Megaera Lorenz is an Egyptologist and Writer with over 20 years of experience in public education. In 2017, she graduated with her PhD in Egyptology from The University of Chicago, where she served for several years as a content advisor and program facilitator for the Oriental Institute Museum’s Public Education office. She has also developed and taught Egyptology courses at The University of Chicago and Loyola University Chicago. This article has been viewed 550,247 times.  How helpful is this? Co-authors: 37 Updated: August 19, 2026 Views: 550,247

Categories: System Maintenance and Repair Article SummaryX 1. Restart PC into the BIOS.

2. Go to the Power On Alarm or RTC Alarm section. 3. Set a schedule frequency. 4. Choose the startup time. 5. Save and exit. Did this summary help you?YesNo In other languages Spanish Italian Russian Portuguese French Indonesian Dutch Arabic Hindi Japanese Print Send fan mail to authors

Thanks to all authors for creating a page that has been read 550,247 times. Is this article up to date? YesNo Advertisement

Cookies make wikiHow better. By continuing to use our site, you agree to our cookie policy. Written by:  Megaera Lorenz, PhD wikiHow Staff Writer Click a star to vote Co-authors: 37 Updated: August 19, 2026 Views: 550,247 Quizzes & Games

What Does Your Morning Routine Say About You? Analyze Me

[Computer at](https://computer-at.northlist.shop/computer-at/20260826.html)

Chronotype Quiz: What's Your Natural Sleep Cycle? Take Quiz What Time Should I Go to Bed Quiz Take Quiz Why Can't I Sleep Quiz Take Quiz You Might Also Like How to Build a Computer How to Troubleshoot Computer Startup Problems How to

Schedule a Shutdown for Your PC or Mac Computer

Set Your Computer to Boot from a USB Flash Drive Trending Articles Am I Chopped Quiz Kiss, Marry, Kill Quiz What Type of Person Do I Attract Quiz Which World-Ending Catastrophe Are You? Trending Articles

Pick a Door and We'll Reveal What You're Missing What’s the Name of My Crush? Am I a Side Chick or a Main Chick Quiz What Kind of Doomed Am I? Take the Quiz. Face the Truth. 🔥 Am I Gay Quiz Do I Have a Type? Am I Hard to Love? Am I a Spoiled Brat? 🤔 Are You More... 🤔 How Tuff Am I? What Kind of Wolf Is My Personality?

[Automatically Turn on](https://automatically-turn-on.northlist.xyz/automatically-turn-on/20260826118.html)

Am I More Golden Retriever or Black Cat? Villain or Hero Quiz Featured Videos How to Create a Cone from Paper: 2 DIY Methods How to

Tell If Your Phone Is Tapped: Telltale Signs + Fixes

[Automatically Turn](https://automatically-turn.swapstreet.shop/automatically-turn/20260826.html)

7 Ways to Know if You’re Addicted to Wearing Diapers A Beginner's Guide to Bullet Journaling Hot Takes Only 🔥

Do You Agree with These Hygiene Hot Takes?

Weird Would You Rather: What Do You Choose?

Do You Agree With These Spicy Hot Takes? Overrated or Underrated Game Your Daily Dose of Fun 🎉 Can We Guess Your Hair Color?

Can You Pull Off The Perfect Heist? Prove Yourself

Do You Agree with These Popular Hot Takes?

Let Us Guess Your Age Based On Video Game Nostalgia Categories Computers and Electronics Maintenance and Repair System Maintenance and Repair

© 2026 wikiHow, Inc. All rights reserved. Use of site content is subject to our Terms of Use. wikiHow Newsletter You're all set! Helpful how-tos delivered to your inbox every week! Sign me up!

By signing up you are agreeing to receive emails according to our privacy policy. Home About wikiHow Experts Jobs Contact Us Site Map Terms of Use Privacy Policy Do Not Sell or Share My Info Not Selling Info Contribute Follow Us ×

Keep up with tech in just 5 minutes a week! Subscribe You're all set! X - - 1034
