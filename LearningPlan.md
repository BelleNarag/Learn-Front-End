# Learning Plan — React Frontend for FinTrack

**Technology:** React (with Vite)  
**Goal:** By the end of Week 5, build a working frontend that connects to my FinTrack REST API, supports user authentication (login/signup), and allows users to manage savings goals and contributions.  
**Time available:** 6 hours per week  

---

## Week 1 — React Fundamentals
**Assignment:** Learn Front End 1  
**Goal:** Understand how React works and get comfortable with the basics before touching the real project.

### Topics to learn
- What is a component and how to write one
- JSX syntax (HTML inside JavaScript)
- Props — passing data into components
- useState — making components interactive
- Rendering lists with `.map()`

### Resources
- [React Official Tutorial](https://react.dev/learn) — work through "Quick Start" and "Thinking in React"
- [freeCodeCamp React Course](https://www.freecodecamp.org/learn/front-end-development-libraries/#react) — free, beginner-friendly
- [Scrimba Learn React](https://scrimba.com/learn-react-c0e) — interactive, highly recommended for beginners

### Milestone checklist
- [ ] I can create a functional component from scratch
- [ ] I can pass props between a parent and child component
- [ ] I can use useState to make a button or input interactive
- [ ] I can render a list of items from an array using `.map()`
- [ ] My Hello World app is pushed to GitHub

---

## Week 2 — React Router + Forms
**Assignment:** Learn Front End 2  
**Goal:** Build multiple pages and handle user input — the foundation for login and signup.

### Topics to learn
- React Router — navigating between pages without reloading
- Controlled inputs — connecting form fields to state
- Handling form submission with `onSubmit`
- Conditional rendering — show/hide things based on state
- useEffect — running code when a component loads

### Resources
- [React Router Official Docs](https://reactrouter.com/en/main/start/tutorial) — follow the tutorial
- [Web Dev Simplified — React Router in 20 min](https://www.youtube.com/watch?v=Ul3y1LXxzdU) — YouTube, very clear
- [React Forms Guide](https://react.dev/learn/sharing-state-between-components) — official docs

### Milestone checklist
- [ ] I have at least 3 pages: Home, Login, Signup
- [ ] Navigating between pages works with React Router
- [ ] My login form captures email and password with useState
- [ ] My signup form captures name, email, and password
- [ ] Code is committed and pushed to GitHub

---

## Week 3 — API Calls + Authentication
**Assignment:** Learn Front End 3  
**Goal:** Connect the frontend to the FinTrack backend — log in for real, store the JWT token, and protect pages that require login.

### Topics to learn
- `fetch()` — making GET and POST requests to an API
- Sending JSON data in a POST request body
- Storing the JWT token in localStorage
- Sending the token in request headers (`Authorization: Bearer ...`)
- Redirecting users after login
- Protected routes — blocking pages if not logged in

### Resources
- [JavaScript Fetch API Guide — MDN](https://developer.mozilla.org/en-US/docs/Web/API/Fetch_API/Using_Fetch)
- [Web Dev Simplified — JWT Auth in React](https://www.youtube.com/watch?v=X3qyxo_UTR4) — YouTube
- [React Router Protected Routes](https://www.youtube.com/watch?v=2k8NleFjG7I) — YouTube

### Milestone checklist
- [ ] Signup form sends a POST request to my API and creates a real user
- [ ] Login form sends credentials and receives a JWT token back
- [ ] JWT token is saved to localStorage after login
- [ ] All API requests after login include the Authorization header
- [ ] Logged-out users are redirected away from protected pages
- [ ] Code is committed and pushed to GitHub

---

## Week 4 — Goals + Contributions Features
**Assignment:** Learn Front End 4  
**Goal:** Build the core FinTrack features — users can create savings goals, log contributions, and see their progress.

### Topics to learn
- Fetching and displaying data from the API on page load (useEffect + fetch)
- Rendering real data from the database in the UI
- Posting new goals and contributions through forms
- Deleting items and updating the UI instantly
- Basic progress bar UI for savings goals

### Resources
- [useEffect + fetch pattern — React Docs](https://react.dev/reference/react/useEffect)
- [Traversy Media — React Crash Course](https://www.youtube.com/watch?v=w7ejDZ8SWv8) — YouTube, covers full CRUD with an API
- [CSS Progress Bar Tutorial](https://www.w3schools.com/howto/howto_js_progressbar.asp)

### Milestone checklist
- [ ] Dashboard page loads and shows all goals for the logged-in user
- [ ] Create Goal form sends a POST request and adds it to the list
- [ ] Each goal shows current amount vs target amount as a progress bar
- [ ] Users can log a contribution to a goal
- [ ] Users can delete a goal
- [ ] Code is committed and pushed to GitHub

---

## Week 5 — Polish + Final Frontend
**Assignment:** Create a Frontend  
**Goal:** Connect everything together into a complete, working app. Clean up the UI, fix bugs, and deploy publicly.

### Topics to learn
- Basic CSS styling and layout (Flexbox)
- Handling loading states and error messages
- Deploying a React app to Vercel (free)
- Writing a clear README for the repository

### Resources
- [Vercel Deployment Guide](https://vercel.com/docs/frameworks/vite) — deploy in under 5 minutes
- [CSS Flexbox — CSS Tricks](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)
- [How to write a good README — makeareadme.com](https://www.makeareadme.com/)

### Milestone checklist
- [ ] All pages are connected and working end to end
- [ ] Login, signup, goals, and contributions all work with the real API
- [ ] The app is deployed on Vercel with a live public URL
- [ ] README explains what the project is and how to run it
- [ ] Final code is pushed to GitHub and submitted

---

## Weekly schedule (5 hours/week)

| Day | Time | Activity |
|-----|------|----------|
| Monday | 1.5 hours | Watch tutorial / read docs for the week |
| Wednesday | 2 hours | Code the main feature for the week |
| Friday | 1.5 hours | Finish feature, fix bugs, commit to GitHub |
| Sunday | 1 hour | Review what you built, prep for next week |

---

*Generated with AI assistance (Claude by Anthropic) as part of Learn Front End 1 assignment.*
