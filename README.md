## Hi, I''m Shirshxk.
This is just a test.
# Hello
Just testing out some stuff.
# Shirshxk AdBlocker
#### Video Demo:  https://www.youtube.com/watch?v=F8JTWcNC5p4
#### Description:

## Shirshxk AdBlocker Extension - CS50 Final Project

> Welcome to the Shirshxk AdBlocker extension, a culmination of knowledge and skills developed throughout the CS50 course. This project is designed to address the pervasive issue of online advertisements disrupting user experience by providing a seamless and efficient ad-blocking solution.

## Project Overview:
> The Shirshxk AdBlocker is implemented as a browser extension, compatible with popular web browsers such as Chrome, Firefox, and Safari. The extension is built using web technologies like HTML, CSS, and JavaScript, offering a lightweight and user-friendly solution to enhance web browsing experiences.

## File Structure:

> manifest.json: This file serves as the manifest file required for browser extensions. It contains metadata about the extension, such as its name, version, permissions, and the background script.

> background.js: This JavaScript file operates in the background, managing the extension's functionality. It handles event listeners, filters requests, and communicates with the content script to dynamically block ads.

> content.js: The content script injects JavaScript code into web pages, allowing for dynamic manipulation of the page's content. This file is responsible for identifying and blocking ad elements on the page, ensuring a smooth and uninterrupted browsing experience for the user.

> popup.html and popup.js: These files create the user interface for the extension's popup. Users can control the ad-blocking functionality through the popup, allowing them to toggle the extension on or off and view basic information about blocked ads.

## Design Choices:

> Dynamic Ad Blocking: The decision to implement dynamic ad blocking through the content script allows the extension to adapt to changes in web page structures and new ad elements, ensuring a robust and up-to-date ad-blocking solution.

> User-Friendly Interface: The popup and options pages are designed with simplicity in mind. Users can easily toggle the extension on or off, access basic information about blocked ads, and customize settings without any hassle.

> Efficiency: The extension prioritizes efficiency by minimizing resource usage and ensuring that the ad-blocking process has minimal impact on page load times. This approach enhances the overall browsing experience for the user.

......
