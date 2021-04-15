# Curtis Bridges Developer Landing Page

This homepage needs to specialize in landing me a developer job at a company of my choice. Here are the features it will leverage to do this...

## Sections

1. Who am I?
   1. List my: GitHub & LinkedIn profiles
2. What skills do I have?
3. What is my work experience?
4. What projects have I done to showcase?
5. What have I done for ongoing education?
   1. Show Udemy certificates
   2. Show LinkedIn verified skills
6. How to contact me.
   1. email
   2. email form
   3. twitter

## Techs Used

- HTML (avoid static site generators -- we are demo'ing our ability to create, not engine themes)
- CSS (avoid bootstrap, tailwind, etc.)
- JS? (avoid frameworks)
- Docker
- AWS hosting

## Deployment

- AWS
- curtisbridges.dev DNS setup
- Docker image
- CI/CD (GitHub Actions)

## TODO
- [x] Create README
- [ ] Create GitHub repo
- [ ] Research good __developer__ landing pages
  - [ ] Choose color palette
  - [ ] Choose layout
- [ ] Design landing page (Figma)
- [ ] Create base html, css, javascript files
- [ ] Show GitHub link (note consistent daily usage, number of repos)
- [ ] Show LinkedIn link (note verified skills, recommendations)
- [ ] Show past work experience. Focus on Riverbed/Aternity products worked on.
- [ ] Show work sample projects
- [ ] Show education (UMaine, BU)
- [ ] Show ongoing education (Udemy, LinkedIn, Books)
- [ ] Setup email form, email link
- [ ] Setup Amazon DNS (for curtisbridges.dev)
- [ ] Setup Dockerfile
  - [ ] Can/should we leverage for local development?
- [ ] Setup GitHub Action to deploy site on main branch pushes


## Design Ideas

<Header />
<Menu>
  <Home>Curtis Bridges - Developer</Home>
  <GitHub />
  <LinkedIn />
  <Twitter />
</Menu>

<Introduction>
  I can help build your next product.

  I'm a full stack javascript developer with a rich background in application development.
  I've helped design, develop, and deliver over a dozen products. Most of them from the ground up. These products drove millions of dollars in revenue in a variety of industries.

  I can do it again, for you.
</Introduction>

<Skills>
  Web Applications
    - HTML, CSS, and JavaScript/TypeScript
    - React & Hooks
    - Node.js & Express.js
    - Amazon Web Services
      - Cognito, Lambda, SES, SQS, ECS, DynamoDB, CloudWatch,
    - Docker
  Mobile Apps
    - iOS, Swift, SwiftUI
</Skills>

<Work>
  <Riverbed & Aternity>
    <AppInternals SaaS />
    <AppInternals />
    <Panorama />
  </Riverbed & Aternity>
  <LogMatrix />
  <efi & VUTEk />
</Work>

<Education>
  <Ongoing>
    <Udemy />
    <LinkedIn />
  </Ongoing>
  <Formal>
    <Boston University />
    <UMaine />
  </Formal>
</Education>

<Contact Form />

<Footer />
