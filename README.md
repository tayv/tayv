### Hello 👋

I'm a Product/UX Designer that spends my days making enterprise security software easier to use. This is the place to view some of my personal coding projects that I complete in my free time. Professional design portfolio available upon request.

#### 🔧 Things I'm working on:

- [Project Bubblegum](https://github.com/tayv/Project-Bubblegum). An adventure in learning to use Nextjs, Typescript, and Tailwind CSS to develop reusable form components and UI patterns.


#### 🌱 Things I'm learning:

- Typescript, MySQL databases (through PlanetScale), and React + Nextjs.

### Past projects:

<details>
  <summary>🚗 <strong>Parkadoo</strong> </summary>
  <br>
  
  > See it in action at [parkadoo.com](https://parkadoo.com) or [parkadoo.netlify.app](parkadoo.netlify.app/)


## What is parkadoo?
This was an experimental project to help people understand Edmonton parking laws better and create a letter that can help with the appeal process. There are three letter types plus the ability to proactively avoid parking tickets:

1. Public parking ticket appeal
2. Private parking lot appeal
3. Neighbour complaint/warning
4. Quickly check list of city bylaws to see if you're likely to get a ticket

## Philosophy

### Design
- Many form-based wizards are inflexible and frustrating to use, particularly on mobile devices. This project sought to explore a more fluid user experience by mimicking native messaging apps. 
- Key experimental design pattern: 
  + Allowing the step-by-step wizard to update active section via buttons but also on scroll. See example section below for video.
  + For context this project began in 2019 when scroll based interaction patterns were more unusual, especially for forms. Nowadays it's fairly common to see form/survey products utilizing some variation of scroll-based interactions.

### Code
- Goal was to reduce external dependencies as much as possible. Uses vanilla JS, CSS, HTML
- Use es6 modules instead of Node.js require
- Privacy and offline first. User data is not collected and user answers are saved to user's device and clears after their browsing session ends

## UI examples

### Light and dark mode 
<img src="https://user-images.githubusercontent.com/48400779/139737501-d5032be4-02a0-415a-9a5a-770632559fc4.PNG" width="250"> <img src="https://user-images.githubusercontent.com/48400779/139737519-eb9f4108-f2e5-4116-a316-af44f4c28127.PNG" width="250"> <img src="https://user-images.githubusercontent.com/48400779/139737508-933df7ff-3327-41fb-8301-008abd763c5a.PNG" width="250"> <img src="https://user-images.githubusercontent.com/48400779/139737515-ccf8a153-72a3-4eb9-9073-9d271f285253.PNG" width="250">


### Checking bylaws

- Make it easier to check bylaws by using providing a list, summarizing in plain language, and linking to official bylaw.

<img src="https://user-images.githubusercontent.com/48400779/139737561-b5f570e9-f53c-468a-aeac-cca2b233e59d.PNG" width="250"> <img src="https://user-images.githubusercontent.com/48400779/139736957-fdc9a339-0a80-4f8b-9d1e-a176bf558bc7.PNG" width="250">


### Creating an appeal letter

https://user-images.githubusercontent.com/48400779/139738865-407aece7-31fe-4b14-b829-dc2eee35aff1.mov 

https://user-images.githubusercontent.com/48400779/139738868-ba373c40-262f-49b2-9f2a-c87e194875de.mov


### Appeal letter (city)

- Appeal letter page gives links to next steps, common letter actions, and a letter preview

https://user-images.githubusercontent.com/48400779/139736044-146ffdba-6d1a-46a8-a081-5d81d243a57e.mov


### Scrolling

- Goal was to mimic the fluidity of a native messaging by having current step update as user scrolls up/down

https://user-images.githubusercontent.com/48400779/139736229-f5e7fa38-093d-45a0-8f6f-cc918f96b216.mov



## How to set up

1. [Clone repo](https://github.com/tayv/parkadoo)
2. Navigate to project folder and run ```npm run install``` to install dependencies 
3. Open terminal and run ```npm run start``` to start a local server 
4. View on localhost address shown in terminal


## Other notes

- 3D UFO graphic designed by me using [Spline](https://spline.design/)

<br>

</details>

<details>
  <summary>🏁 <strong>MK1 Leaderboard</strong></summary>
  <br>  

  > _View the [public repo](https://github.com/tayv/mk1) or see it in action at [https://mk1racing.netlify.app/](https://mk1racing.netlify.app/)_

## What is MK1?
MK1 is a Mario Kart race league started during the Covid-19 pandemic. This project was a way for me to learn React by creating a visual leaderboard that could be used by the league to better track race results. 


## Philosophy

### Design

- Design is not polished. This was primarily a coding project with minimal time spent refining visual design or interaction patterns.
- Goal: Follow standard race league leaderboards while also allowing users the ability to quickly see rankings by season as well as all-time results.
- Logo designed by Steve A.
- If I ever have time the Avatars will be updated to pixel art.
- Pixel art background created by me using Figma

### Code

- Uses React for the UI and Google Sheets API to host/update data. 
- There's a known async rendering issue with season results on initial page load. Can be fixed by triggering a re-render using the season dropdown. 
    
### Examples

https://user-images.githubusercontent.com/48400779/174938723-ad73c9c8-f893-4e85-81ac-c16b88e2bc91.mov
  
#### Desktop
  
<img width="400" alt="Desktop - MK1 Final Season Standings" src="https://user-images.githubusercontent.com/48400779/174938863-5b683f06-7dcd-484b-8c20-eed5b8720fe0.png">

<img width="400" alt="Desktop - MK1 All-Time Championship Rank" src="https://user-images.githubusercontent.com/48400779/174938869-84048e83-7582-4cb2-bfa1-c59e094d3497.png">

#### Mobile

<img width="250" alt="MK1 Mobile View" src="https://user-images.githubusercontent.com/48400779/174939203-4db54aaa-62e0-4d3b-acf6-d2991edf1d74.jpeg">

<br>
  
</details>
