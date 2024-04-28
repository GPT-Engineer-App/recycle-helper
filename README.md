# recycle-helper

 want to build an Android app to help me count refundable bottles and cans while I'm sorting through recycling bins at night. I'll be wearing gloves, so I need to control the app using only my voice through a Bluetooth headset. The environment is noisy, and there might be long pauses in my speech while I'm digging through the bins.
I want to develop this as an Android app. I'd like to use Android's built-in speech recognition to keep things simple. Since I might not be able to look at the screen, audio feedback will be important—maybe a sound to indicate the app is listening and different tones to confirm when it counts a bottle.
I want to expand the app to track 5 keywords: pet, hdp, can, glass, carton. The app should also recognize multiples, like "3 bottles" and update counts correctly. Could we include a separate count for words the app doesn't recognize?
I'd like the app to keep running totals for each keyword and the unrecognized word count. It would be great to save this data for later review. Ideally, I could see the most common item and totals for each day.
or the display, let's have a simple on-screen breakdown of the individual keyword counts, the total count, and the number of unrecognized words. We can skip audio announcements for now.
Could we outline the main modules of the code? We'll likely need components for speech recognition, counting logic, data storage, and the display.



## Collaborate with GPT Engineer

This is a [gptengineer.app](https://gptengineer.app)-synced repository 🌟🤖

Changes made via gptengineer.app will be committed to this repo.

If you clone this repo and push changes, you will have them reflected in the GPT Engineer UI.

## Tech stack

This project is built with React and Chakra UI.

- Vite
- React
- Chakra UI

## Setup

```sh
git clone https://github.com/GPT-Engineer-App/recycle-helper.git
cd recycle-helper
npm i
```

```sh
npm run dev
```

This will run a dev server with auto reloading and an instant preview.

## Requirements

- Node.js & npm - [install with nvm](https://github.com/nvm-sh/nvm#installing-and-updating)
