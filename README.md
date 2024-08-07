# Promptopia is a Next.js 13 Full Stack App Using the Official React Framework

![Deployed site](public/assets/images/screenshot.jpg)


## Welcome to Promptopia 🌍✨

Promptopia is an open-source AI prompting tool designed for the modern creator. Dive into a world where your imagination fuels AI, crafting prompts that inspire and excite!

## Features

- **Discover Prompts**: Explore a rich database of creative AI-generated prompts across various categories.
- **Create Prompts**: Submit your own prompts and see them come to life with AI.
- **Share with Community**: Engage with other creators, share your prompts, and get feedback.
- **Responsive Design**: Whether you're on desktop or mobile, Promptopia provides a seamless experience.

## Technology Stack

- **Frontend**: Built with Next.js, leveraging the power of React for dynamic user interfaces.
- **Authentication**: Integrated with NextAuth for secure Google logins.
- **Database**: MongoDB is used for storing user and prompt data, ensuring fast access and scalability.
- **Styling**: Tailored UI with TailwindCSS for sleek, responsive designs.

## Getting Started

### Prerequisites

- Google Cloud Registration:
  - Create a Google Cloud project to obtain OAuth 2.0 credentials (`CLIENT_ID` and `CLIENT_SECRET`) for the Google authentication via NextAuth.
  - Configure OAuth consent screen and add the necessary scopes.
- MongoDB Registration:
  - Sign up for MongoDB and create a new cluster.
  - Obtain your connection string to use in your application (`MONGODB_URI`).

### Local Setup

Here's how to get Promptopia running on your local machine:

1. **Clone the repository:**

   ```bash
   git clone https://your-repository-link
   cd promptopia
   ```

2. **Install dependencies:**

    ```bash
    npm install
    ```

3. **Set up environment variables: Copy the .env.example file to a new file named .env, and update the values accordingly including GOOGLE_ID, GOOGLE_CLIENT_SECRET, and MONGODB_URI.**

4. **Run development server:**

```bash
npm run dev
```

Visit <http://localhost:3000> to see your application in action!

### Contributing

We love your input! We want to make contributing to this project as easy and transparent as possible, whether it's:

Reporting a bug:

- Discussing the current state of the code
- Submitting a fix
- Proposing new features
- Becoming a maintainer

This was crafted with ❤ and bringing your ideas to life, one prompt at a time!
