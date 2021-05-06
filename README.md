# Curtsy Android Coding Challenge

## Challenge Description

Here at Curtsy we love content feeds! Your task is to transform a simple JSON HTTP endpoint and into a scrollable feed of item postings. The feed should be searchable by the item's `title` property, and there should be a toggle that filters items based on the item's `new` property. Each item should have an image, title, size, number of loves, indicate whether or not the item is new. Please use the mock-up (below) as a suggestion, and introduce any and all platform-specific bells-and-whistles, libraries, or design patterns.

### Mock-up:

![IMG_3875](https://user-images.githubusercontent.com/906671/117348747-6be18500-ae5f-11eb-8ee0-febc90272d5c.png)

### Item list HTTP Endpoint
-  `GET (Content-Type: application/json)` https://mod.curtsyapp.com/sample-items
```
[
  {
    "title": "ZARA  Sweatpants",
    "thumbnailImage": "https://curtsy-parse-files.s3-us-west-2.amazonaws.com/5d1dbec0375a6a84135d21986184d74e_photo.jpeg",
    "loves": 471,
    "price": 20,
    "new": true,
    "size": "M"
  },
  {
    "title": "SheIn Leaf Print Knot Bandeau Bikini Swimsuit",
    "thumbnailImage": "https://curtsy-parse-files.s3-us-west-2.amazonaws.com/23a13df19f0fe1d8b64c2f57d6344c34_photo.jpeg",
    "loves": 2,
    "price": 15,
    "new": false,
    "size": "S"
  },
  ...
]
```

## Instructions

- Clone this repository 
- Create a new Android project from scratch
- Treat this as a new production app: documentation/comments, architecture, commit hygiene, testability are all great things!

## Deliverables

- Please spend a maximum of two hours on the project. Completing it is not necessary as you will be assessed on many factors.
- Email us back a zip file containing your project, its `.git` history, along with a SOLUTION.md describing your approach.
