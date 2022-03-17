# gym-check-in

An app that manages reserving and checking in to a gym.

This app has members, owners, and coaches. The core of the application is functionality that enables members to reserve a class time and check in when they they show up.

## Tech stack

This is a full stack application. My favorite stack right now is Next.js + Tailwind + Prisma with Supabase on the backend to store data.

Next.js handles all the application needs that I want. Easy file-based routing and the ability to implement serverless functions with their API routes.

Tailwind is my defacto CSS Framework because I don't want to worry about CSS file architecture or class names.

Prisma gives me great type safety and a way to manage my data models.

Supabase is a hosted postgres database and gives you a lot out of the box. They have a nice auth solution that I will look at but I'm also considering [NextAuth](https://next-auth.js.org/)


## About the Project 

I will be documenting user stories in [issues](https://github.com/zacjones93/gym-check-in/issues) so check those out if your interested in the development of the application.

## App Structure

### routes

```md

/

// member
/[class]
/reservations

// owner
/admin
```
