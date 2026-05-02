
/* Portfolio of Abdullah Al Shaikh */

import emoji from "react-easy-emoji";
import splashAnimation from "./assets/lottie/splashAnimation";

// Splash Screen
const splashScreen = {
  enabled: true,
  animation: splashAnimation,
  duration: 2000
};

// Summary And Greeting Section
const illustration = {
  animated: true
};

const greeting = {
  username: "Abdullah Al Shaikh",
  title: "Hi all, I'm Abdullah",
  subTitle: emoji(
    "A passionate Full Stack Developer 🚀 with 10 years of experience building visually appealing and effective web applications. Expertise in logo design, print design, and web design — delivering projects on time with the highest standards of quality."
  ),
  resumeLink:
    "https://drive.google.com/file/d/1J78AuDdQrZHHrTw2AkvZ_1qj-stckeXA/view?usp=sharing",
  displayGreeting: true
};

// Social Media Links
const socialMediaLinks = {
  github: "http://github.com/abdullahalsahikh",
  linkedin: "https://www.linkedin.com/in/abdullah-al-sahikh-249580407",
  gmail: "abdullahalsahikh1469.csenub@gmail.com",
  facebook: "https://www.facebook.com/share/1DpcdjnZ5r/",
  // gitlab, medium, stackoverflow, twitter -- add if needed
  display: true
};

// Skills Section
const skillsSection = {
  title: "What I do",
  subTitle: "FULL STACK DEVELOPER WITH A PASSION FOR DESIGN AND TECHNOLOGY",
  skills: [
    emoji(
      "⚡ Design and develop highly interactive Front end / User Interfaces for web and mobile applications"
    ),
    emoji(
      "⚡ Build scalable backend systems and RESTful APIs for real-world applications"
    ),
    emoji(
      "⚡ Work with IoT and embedded systems — smart automation projects using sensors and solar technology"
    )
  ],

  softwareSkills: [
    {
      skillName: "html-5",
      fontAwesomeClassname: "fab fa-html5"
    },
    {
      skillName: "css3",
      fontAwesomeClassname: "fab fa-css3-alt"
    },
    {
      skillName: "JavaScript",
      fontAwesomeClassname: "fab fa-js"
    },
    {
      skillName: "reactjs",
      fontAwesomeClassname: "fab fa-react"
    },
    {
      skillName: "nodejs",
      fontAwesomeClassname: "fab fa-node"
    },
    {
      skillName: "python",
      fontAwesomeClassname: "fab fa-python"
    },
    {
      skillName: "sql-database",
      fontAwesomeClassname: "fas fa-database"
    },
    {
      skillName: "git",
      fontAwesomeClassname: "fab fa-git-alt"
    },
    {
      skillName: "npm",
      fontAwesomeClassname: "fab fa-npm"
    }
  ],
  display: true
};

// Education Section
const educationInfo = {
  display: true,
  schools: [
    {
      schoolName: "Northern University Bangladesh",
      logo: require("./assets/images/harvardLogo.png"), // Replace with NUB logo
      subHeader: "B.Sc. in Computer Science & Engineering",
      duration: "2023 - 2027",
      desc: "CGPA: 3.25. Actively involved in various academic and extracurricular activities.",
      descBullets: [
        "Studying core subjects: Data Structures, Algorithms, Web Engineering, and Software Development",
        "Working on IoT and smart system projects as part of coursework"
      ]
    }
  ]
};

// Tech Stack Proficiency
const techStack = {
  viewSkillBars: true,
  experience: [
    {
      Stack: "Frontend / Design",
      progressPercentage: "85%"
    },
    {
      Stack: "Backend",
      progressPercentage: "65%"
    },
    {
      Stack: "Programming",
      progressPercentage: "70%"
    }
  ],
  displayCodersrank: false
};

// Work Experience Section
const workExperiences = {
  display: true,
  experience: [
    {
      role: "Voice Director",
      company: "GENX",
      companylogo: require("./assets/images/facebookLogo.png"), // Replace with GENX logo
      date: "2023 – 2024",
      desc: "Directed voice productions and managed audio content pipelines at GENX, ensuring high-quality output across all deliverables."
    },
    {
      role: "Manager",
      company: "Abul Hotel",
      companylogo: require("./assets/images/quoraLogo.png"), // Replace with Abul Hotel logo
      date: "2024 – 2025",
      desc: "Managed day-to-day operations, staff coordination, and customer service at Abul Hotel, improving overall operational efficiency."
    },
    {
      role: "Intern",
      company: "Grameenphone (GP)",
      companylogo: require("./assets/images/airbnbLogo.png"), // Replace with GP logo
      date: "2025 – Present",
      desc: "Currently completing an internship at Grameenphone, gaining hands-on experience in telecom technology and corporate operations."
    }
  ]
};

// Open Source
const openSource = {
  showGithubProfile: "true",
  display: true
};

// Big Projects
const bigProjects = {
  title: "Projects",
  subtitle: "SMART SYSTEMS AND TECH PROJECTS I HAVE BUILT",
  projects: [
    {
      image: require("./assets/images/saayaHealthLogo.webp"), // Replace with project image
      projectName: "Smart Watering System Using Solar",
      projectDesc:
        "An IoT-based automated plant watering system powered by solar energy — monitors soil moisture and irrigates plants intelligently without manual intervention.",
      footerLink: [
        {
          name: "View Project",
          url: "#"
        }
      ]
    },
    {
      image: require("./assets/images/nextuLogo.webp"), // Replace with project image
      projectName: "Smart Lighting System",
      projectDesc:
        "An automated smart lighting system that adjusts brightness based on ambient light levels and motion detection, improving energy efficiency.",
      footerLink: [
        {
          name: "View Project",
          url: "#"
        }
      ]
    }
  ],
  display: true
};

// Achievement Section
const achievementSection = {
  title: emoji("Achievements And Certifications 🏆"),
  subtitle:
    "Achievements, Certifications, and Cool Stuff I have accomplished!",

  achievementsCards: [
    {
      title: "Best Achievement",
      subtitle:
        "Recognized for outstanding performance and contribution in my field.",
      image: require("./assets/images/codeInLogo.webp"), // Replace with relevant image
      imageAlt: "Achievement Logo",
      footerLink: [
        {
          name: "View Details",
          url: "#"
        }
      ]
    },
    {
      title: "Best Recognition",
      subtitle:
        "Awarded for excellence and dedication in a competitive environment.",
      image: require("./assets/images/googleAssistantLogo.webp"), // Replace with relevant image
      imageAlt: "Award Logo",
      footerLink: [
        {
          name: "View Details",
          url: "#"
        }
      ]
    }
  ],
  display: true
};

// Blogs Section
const blogSection = {
  title: "Blogs",
  subtitle:
    "I love sharing knowledge and writing about technology and design.",
  displayMediumBlogs: "false",
  blogs: [],
  display: false // Set true and add blogs when available
};

// Talks Section
const talkSection = {
  title: "TALKS",
  subtitle: emoji("I LOVE TO SHARE MY KNOWLEDGE AND EXPERIENCE 😄"),
  talks: [],
  display: false
};

// Podcast Section
const podcastSection = {
  title: emoji("Podcast 🎙️"),
  subtitle: "I LOVE TO TALK ABOUT TECHNOLOGY AND DEVELOPMENT",
  podcast: [],
  display: false
};

// Resume Section
const resumeSection = {
  title: "Resume",
  subtitle: "Feel free to download my resume",
  display: true
};

// Contact Info
const contactInfo = {
  title: emoji("Contact Me ☎️"),
  subtitle:
    "Discuss a project or just want to say hi? My inbox is open for all.",
  number: "+8801948129016",
  email_address: "abdullahalsahikh1469.csenub@gmail.com"
};

// Twitter Section
const twitterDetails = {
  userName: "twitter",
  display: false // Set true and add your Twitter/X username if you have one
};

const isHireable = true;

export {
  illustration,
  greeting,
  socialMediaLinks,
  splashScreen,
  skillsSection,
  educationInfo,
  techStack,
  workExperiences,
  openSource,
  bigProjects,
  achievementSection,
  blogSection,
  talkSection,
  podcastSection,
  contactInfo,
  twitterDetails,
  isHireable,
  resumeSection
};