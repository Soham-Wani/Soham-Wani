```javascript
const soham = {
    name: "Soham Wani",
    pronouns: "he" | "him",
    birthDate: new Date(2004, 11, 18),
    mood: `${"Confused"} ${"Enthusiastic"}`,
    education: [
        {
            institute: "Gati Shakti Vishwavidyalaya",
            yearEnrolled: 2022,
            degree: "BTech",
            course: "Electronics and Communication Engineering (Specialisation: Rail Engineering)"
        },
        {
            institute: "Indian Institute of Technology, Madras",
            yearEnrolled: 2023,
            degree: "BS",
            course: "Data Science and Applications"
        }
    ],
    interests: {
        hobbies: new Set(["reading", "writing", "travelling"]),
        talkWithMeAbout: ["poetry", "astronomy", "programming", "anything you like"]
    },
    connect: new Map([
        ["GitHub", "https://github.com/Soham-Wani"],
        ["LinkedIn", "https://www.linkedin.com/in/soham-wani-b0726a262"],
        ["Discord", "https://discordapp.com/users/912297357339660309"],
        ["Blogger", "https://www.blogger.com/profile/14703622455073552485"]
    ]),
    isAvailableForCollaboration: true,
    randomQuote: "Hate is a choice. Love is not."
}

console.log(soham);