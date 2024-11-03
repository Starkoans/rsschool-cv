# Anastasia Starkova

## Junior Frontend Developer

### Contacts

![Discord](https://api.iconify.design/simple-icons:telegram.svg) [@starkoans](https://t.me/starkoans)

![Discord](https://api.iconify.design/simple-icons:discord.svg) strknt

![Discord](https://api.iconify.design/simple-icons:github.svg) [Github](https://github.com/Starkoans)

![Mail](https://api.iconify.design/fa-solid:envelope.svg) starkoans@gmail.com

![LeetCode](https://api.iconify.design/simple-icons:leetcode.svg) [Leetcode](https://leetcode.com/u/starkoans/)

## About me

Hi, my name is Anastasia, I am a beginner frontend developer, I would be glad to be a part of a team where I will continue to grow in this direction.

In addition to interface development, I'm also interested in [designing](https://www.behance.net/acab7e75) them.

## Skills

HTML, CSS/SASS, Javascript, Typescript, React, Redux Toolkit, Bootstrap, Tailwind, Git.

## Code example

My solution to the [Leetcode task](https://leetcode.com/problems/promise-time-limit/description/?envType=study-plan-v2&envId=30-days-of-javascript):

```
/**
 * @param {Function} fn
 * @param {number} t
 * @return {Function}
 */
var timeLimit = function (fn, t) {

    return async function (...args) {
        return new Promise((resolve, reject) => {
            let timeoutId;
            fn(...args)
                .then(res => { resolve(res) })
                .catch(err => reject(err))
                .finally(() => { clearTimeout(timeoutId) })
            timeoutId = setTimeout(() => {
                clearTimeout(timeoutId)
                reject('Time Limit Exceeded');
            }, t)
        })

    }
};

/**
 * const limited = timeLimit((t) => new Promise(res => setTimeout(res, t)), 100);
 * limited(150).catch(console.log) // "Time Limit Exceeded" at t=100ms
 */
```

## Expiriense

### Cat business (Training pet project)

Demo of a quest game about a boss cat.
At the moment the basic mechanics are implemented - moving around the level and mini-games.

> Stack: React, Typescript, Tailwind.

- [Demo video](https://drive.google.com/file/d/1P1kRV4cWaxyePZEHqFKrJ7Zk3FaMZmKC/view?usp=drivesdk)
- [Deploy](https://cat-business-avw64rk0b-starkoans.vercel.app)
- [Repo](https://github.com/Starkoans/cat-business)

### FroggyChat (Training pet project)

Developed realtime chat with nickname search.

> Stak: React, Bootstrap и SCSS, Redux Toolkit, Firebase (Authentication, Realtime Database, Firestore), Vite.

- [Demo video](https://drive.google.com/file/d/1RVPCNAaZJWYGMiVQAFTVzPjTBIa4xSuG/view?usp=drivesdk)
- [Deploy](https://froggy-chat-8msqc6sqc-starkoans.vercel.app)
- [Repo](https://github.com/Starkoans/chatApp)

### SHIFT Delivery (Training pet project)

Developed a web application to calculate parcel delivery, place orders and view order history. Work within the framework of the Shift Intensive from [Financial Technologies Center](https://www.cft.ru/).

> Stack: React, Tailwind, React-hook-form, Redux Toolkit (Thunk), Vite, Git, Swagger.

- [Demo video](https://drive.google.com/file/d/1YV0IdBHDPNBXmiZQfqFpVJwf-9Vvs18R/view?usp=drivesdk)

- [Deploy](https://shift-delivery-summer-2023-30v1ubwxw-starkoans.vercel.app)

- [Repo](https://github.com/Starkoans/shift-summer-2023-task)

### P2Pizza (Training pet project)

Developed the client side of the website for ordering pizza.

> Stack: React, Redux Toolkit, React-hook-form, Vite.

- [Deploy](https://pizza-qj14hjkx5-starkoans.vercel.app)
- [Repo](https://github.com/Starkoans/pizza)

### School 21, Novosibirsk

**Manual QA Engineer**

I was involved in manual testing of Sber's School 21 educational platform and environment, worked with git, wrote bash scripts, small C programs, and bug reports.

## Education

- **Siberian State University of Telecommunications and Informatics**, Bachelor of Applied Informatics (2020-2024) Russia, Novosibirsk
- [Summer Intensive on "Frontend Development" at the School of Information and Financial Technologies](https://team.cft.ru/start/intensive), Financial Technologies Center (2023)

## Languages

- Russian (Native)
- English (B1, Intermediate)