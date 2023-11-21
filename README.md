const developer = {
  name: "Ajzal",
  twitter: "ajzaldonttweet",
  linkedin: "Ajzal Muhammed",
  portfolio: 404 Not found,
};

const techStack = {
  frontend: ["HTML", "CSS", "JavaScript", "NodeJS", "Express", "MongoDB"],
  backend: ["Node.js", "Express"],
  database: ["MongoDB"],
  tools: ["Git",
};


const currentLearning = [
  "Exploring concepts needed for an eCommerce",
  "Mastering advanced JavaScript concepts",
  "Improving Logic building for backend",
];


function generateREADME() {
  return `
# 👨‍💻 ${developer.name} - JavaScript Developer

Welcome to my GitHub profile! I'm ${developer.name}, a creative and detail-oriented JavaScript developer with a love for building web applications and exploring new technologies. Here, you'll find a collection of my projects and contributions. Feel free to explore, and don't hesitate to reach out if you have any questions or just want to connect.

## 🚀 Technologies & Tools

- **Frontend**: ${techStack.frontend.join(", ")}
- **Backend**: ${techStack.backend.join(", ")}
- **Database**: ${techStack.database.join(", ")}
- **Tools**: ${techStack.tools.join(", ")}

## 🌱 Currently Learning

I'm always eager to learn and stay up-to-date with the latest technologies. Here are some of the things I'm currently focusing on:

${currentLearning.map((topic, index) => `- ${index + 1}. ${topic}`).join("\n")}


## 📫 Let's Connect

- Twitter: [@${developer.twitter}](https://twitter.com/${developer.twitter})
- LinkedIn: [${developer.linkedin}](https://www.linkedin.com/in/${developer.linkedin}/)

Feel free to connect with me! Whether it's about programming, tech in general, or just to say hi, I'm always open to interesting conversations.

## 🌟 Fun Facts

- I believe that code can be both functional and a work of art.
- When not coding, you can find me [hobbies/interests].

Thanks for stopping by! Happy coding! 🚀
`;
}

// Log the generated README to the console
console.log(generateREADME());
