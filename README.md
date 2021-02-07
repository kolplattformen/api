# $kolplattformen.org monorepo

This is a try to reverse engineer Skolplattformens backend to a more consistant and secure experience for developers to create apps that can help parents, kids and teachers to be more productive.

## Embedded API
We previously were testing having a proxy for the API. That was a bad idea, even if we werent saving any information on our side it still was an extra complexity so we encapsulated our API into its own npm package so the app still could be lightweight and not have to worry about the complex nature of the official API. 

Read about the embedded api here: https://github.com/kolplattformen/react-native-embedded-api

## App
The central part of the project is of course the app. It is written in React Native and is using a UI library called React Native Kitten. Our goal with the app is to make it as fast and easy to use as possible. We start small and will continue to add more features over time.
[packages/app](packages/app)

## Website
Our official site for the project is https://skolplattformen.org 
The source code for the site lives here [packages/site](packages/site)

## Contributions
We want this project to become a citizen movement. Every time you find something you want to fix, we encourage you to try to fix the problem yourself by providing a "pull request" - meaning you fix the problem yourself, test it out on your machine and then send the fix to us with documetnation about why we should incorporate your fix into our main branch. This way we can continue to improve the project together with our users which hopefully will render in a much better experience and fast moving project. 

If you don't know how to program and still want to contribute we encourage you to file an Issue or help us an any other way. Please find the Issues tab above to see other issues or file one yourselves. We are super duper happy for both issues and PR:s and will try to answer all of them as soon as humanly possible.

## Money
We are both an open source project and still charge money for our app. Isn't this contradicting? No. Open doesn't mean free. We want to be able to sustainably continue to work with maintaining this project which means someone needs to pay for the time spend on that. Our long term goal is to reach to a point when you are contributing in any substantially way you will be reinbursed for the work.

## Disclaimer
This initiative is started by frustrated parents and we have no affiliation with Stockholm Stad. We just want to find and read our newsletters a little bit easier and register sick-leave more convenient.

If you are offended by this initiative, please don't - we come in peas.

# Contributors
- Christian Landgren
- Johan Öbrink
- Erik Hellman
- Rickard Laurin
- You?


## License

MIT
