```ts
// 🚀 Welcome to My Digital Universe! I'm Aziz Rajabov 👋

const azizRajabov = {
  name: "Aziz Rajabov",
  role: "💻 Full-Stack Developer | 🛠 Web Enthusiast",
  motto: "Code Smart. Build Bold. Secure Everything.",
  passion: [
    "🚀 Developing high-performance full stack web applications",
    "🎨 Creating immersive 3D experiences with Three.js",
    "📈 Discovering Web3 & AI"
  ],
  techStack: {
    frontend: ["⚛️ React", "⚡ Next.js", "🅰️ Angular", "🟦 TypeScript", "🎨 Tailwind CSS"],
    backend: ["🟩 Node.js", "⚡ Express.js", "🟦 TypeScript", "🍃 PostgreSQL"],
    devOps: ["🐳 Docker", "🚀 CI/CD", "⚙️ GitHub Actions", "GIT"],
    currentlyLearning: ["🗄️ Advanced SQL", "⚡ Scalable Backend Architecture", "⚡ Next.js", "React Native", "ThreeJS"]
  },
  currentStatus: {
    location: "📍 Montreal, Canada",
    lookingForJob: true,
    previousExperience: ["🏦 KMS Vertrieb und Services AG - Software Developer", "🏦 Alif Bank - Full-Stack Developer"],
    workingOn: "🚀 Developing web applications & mastering AI integration",
    interests: ["Programming", "🌍 Web3", "🤖 AI", "🔒 Cybersecurity"],
  },
  socialLinks: {
    LinkedIn: "🔗 https://www.linkedin.com/in/yourprofile/",
    GitHub: "🐙 https://github.com/AzizR/",
    Portfolio: "🌐 https://rajabov.net/"
  },
  introduce() {
    console.log("🌟 Welcome to my digital space! 🌟");
    console.log(`👨‍💻 I'm ${this.name}, a ${this.role}`);
    console.log("\n🔥 Passion Areas:");
    this.passion.forEach(p => console.log(` - ${p}`));
    console.log("\n🛠 Tech Stack:");
    Object.entries(this.techStack).forEach(([key, value]) => console.log(` - ${key.toUpperCase()}: ${value.join(", ")}`));
    console.log("\n🚀 Featured Projects:");
    this.projects.forEach(p => console.log(` - ${p.name}: ${p.link} → ${p.description}`));
    console.log("\n📫 Connect With Me:");
    Object.entries(this.socialLinks).forEach(([key, value]) => console.log(` - ${key}: ${value}`));
    console.log("\n✨ Let's build the future together! 🚀");
  }
};

azizRajabov.introduce();
```
