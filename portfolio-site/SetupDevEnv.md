# Building My Portfolio Website

## Introduction

This is the journey of building my portfolio website. I decided to use Next.js, a popular React framework, and Tailwind CSS for styling. I'm documenting each step of the process to serve as a guide for others and a reference for future projects.

## Setting Up the Project

I started by installing nvm and setting up a new Next.js project. I used `pnpm` as my package manager. Here are the commands I used:
```
nvm install v20.13.0
nvm use v20.13.0
npm install -g pnpm
npx create-next-app@latest
```
# First Error
Parsing error : Cannot find module 'next/babel'

Solved by adding 
```
{
  "extends": ["next/babel","next/core-web-vitals"]
}
```
in .eslintrc.json file
[Reference](https://stackoverflow.com/questions/68163385/parsing-error-cannot-find-module-next-babel)
