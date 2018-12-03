# Planing our application

  1. Answer the questions?
    - What am I building ?
    - Who am I building it for?
    - What features do I need to have?
  2. User stories
  3. Modeling Data
  4. Think through the pages I need in my app

## Questions
  1. What am I building?
    Iam building a personal website. A place I can blog, share my personal
    projects and add me more scores when I apply for a job.
  2. Who am I building it for ?
    Iam building it for myself.
  3. What features do I need to have?
    - Posts
      - Create/Edit/Destroy
      - Markdown format
      - Comments
    - Projects
      - Create/Edit/Destroy
    - Contact
      - Contact form
      - Sendgrid
    - User Authen (Devise gem)

## User stories
  - As a admin user, I want to be able to create posts so that I can share what
  I am learning on my blog.
  - As a admin user, I want to be able to edit & destroy posts so that I can
  manage my blog
  - As a admin user, I want to be able to write posts in markdown syntax so that
  it's easy for me to writes posts
  - As a admin user, I want to show the visitors and potential headhunt examples
  of my work or stuff that i've built.

## Modeling data
  **Post**

    - title:string
    - content:text

  **Project**

    - title:string
    - description:text
    - link: string

  **User**

    - role:string

## Think through the pages I need in my app
  - Home
  - Posts#index
  - Posts#show
  - Projects#index
  - Projects#show
  - Contact


------------------------------------------------------------
@Copyright TrungN
