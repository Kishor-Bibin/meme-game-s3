
# Memory Matching Game 🎮

## Description

This repository contains a **Memory Matching Game** built using HTML, CSS, and JavaScript. The game is a simple and fun challenge where users try to match pairs of meme cards. It features:

- A grid of face-down cards
- Users can click on two cards at a time to reveal them
- If the two revealed cards match, they disappear from the board
- If the cards don't match, they flip back, and the user can try again!

The game is deployed and hosted on AWS using **S3** for static website hosting, with automatic deployment via **AWS CodePipeline** from GitHub.


## Tech Stack 🛠️
HTML, CSS, JavaScript: The core technologies used to build the game.
AWS S3: Used for hosting the static website.
AWS CodePipeline: For continuous deployment of the code whenever changes are made in this GitHub repository.

## Deployment Pipeline 🚀
This project uses AWS CodePipeline to automate the deployment process:

Source: The game code is hosted in this GitHub repository.
Build/Deploy: When changes are detected in the repository, AWS CodePipeline automatically pulls the latest code and deploys it to an S3 bucket configured for static website hosting.
Hosting: The game is accessible via the S3 bucket's public URL.
Steps to Set Up the Deployment Pipeline
Create an S3 Bucket:

Go to the AWS Console and create a new S3 bucket.
Enable static website hosting for the bucket.
Set Up AWS CodePipeline:

Create a new pipeline in AWS CodePipeline.
Choose GitHub as the source provider and link your repository.
Set up the pipeline to automatically deploy the game to your S3 bucket when changes are pushed to the main branch.

## How to Play 🎮
Open the game URL hosted on AWS S3.
Click on two cards to reveal them.
If the cards match, they will disappear from the board.
If the cards don’t match, they will flip back, and you can try again.
Keep going until all cards are matched!
## Screenshot📸
![https://github.com/Kishor-Bibin/meme-game-s3/tree/main/screenshot](https://via.placeholder.com/468x300?text=App+Screenshot+Here)



## Continuous Deployment Workflow ⚙️
1. Code is pushed to the GitHub repository.
2. AWS CodePipeline detects the changes and automatically pulls the latest code.
3. The updated code is deployed to the S3 bucket configured for hosting.
4. The game is now live with the latest changes!

## Contributing 🤝
Contributions are welcome! Please feel free to submit a pull request or open an issue if you have any suggestions or improvements.


## License 📄
