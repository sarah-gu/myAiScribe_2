

# myAIScribe

## Table of Contents
1. [Overview](#Overview)
1. [Product Spec](#Product-Spec)
1. [Wireframes](#Wireframes)
2. [Schema](#Schema)

## Overview
### Description
Mobile app to keep track of your coursework history, grades, and plan for upcoming semesters

### App Evaluation
[Evaluation of your app across the following attributes]
- **Category:** Lifestyle / Social / Utility
- **Mobile:** Easy to access notes-viewing on your phone, more accessible than a webpage that you need to navigate to
- **Story:** Creates a seamlined and all-in-one-place view of notes, with ML automatically highlighting the phrases and keywords. 
- **Market:** Any student can use this app. 
- **Habit:** Students use the app to keep track of their notes, and have a faster note-taking system altogether. Additionally, students can use the app to create goals for their note-taking and study habits. 
- **Scope:** V1 could be the basic scanning / storing notes setup without any ML function. V2 would expand to incorporate CoreML auto-highlighting capability. V3 would add in ability to track graphs set goals. 

## Product Spec

### 1. User Stories (Required and Optional)

**Required Must-have Stories**

* User can log in / create account
* User can take pictures of notes 
* User can view the stored notes and filter by subject or by recent date of addition
* Settings page for basic profile information display



**Optional Nice-to-have Stories**

* Goals page with pie charts showing the status of the goal 
* Reminders tab to set reminders about completing goals/ studying
* General graphs page showing trends of learning over the history of using the app 

### 2. Screen Archetypes

* Login Screen
   * user logs in
* Register Screen
   * user registers for an account
* Scanner Screen
   * user can take picture of notes
* Notes Display 
   * User can view the stored notes and filter by subject or by recent date of addition
* Settings Screen
   * Settings page for basic profile information display

### 3. Navigation

**Tab Navigation** (Tab to Screen)

* Scanner
* Note Display
* Settings

**Flow Navigation** (Screen to Screen)

* Login Page
   * Notes Display
* Notes Display
   * Scanner
   * Settings
* Settings
   * Goals
   * Reminders
   * Notes Display
   * Login Page
   * Scanner

## Wireframes

![figma wireframes](https://github.com/sarah-gu/myAIScribe/blob/main/figma.png)


### Models
- Notes model, has info about the subject and image to be uploaded. 
### Networking
- Send requests to the CoreML API 
- Parse Network uploads a new Note 


