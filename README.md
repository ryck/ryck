```ts
type Engineer = {
  role: string;
  location: `${string}, ${string}`;
  focus: readonly string[];
  currently: string;
};

const ryck = {
  role: "Senior Software Engineer",
  location: "London, UK",
  focus: ["React", "TypeScript", "CSS & animation", "Accessibility", "DX"],
  currently: "Working at Engine by Starling",
} as const satisfies Engineer;

export default ryck;
```

---

<p align="center">
  <sub>
    <code>ryck</code> on
    <a href="https://ryck.dev">Website</a> ·
    <a href="https://github.com/ryck">GitHub</a> ·
    <a href="https://www.linkedin.com/in/ryck/">LinkedIn</a> ·
    <a href="https://bsky.app/profile/ryck.dev">Bluesky</a> ·
    <a href="https://twitter.com/ryck">X</a> ·
    <a href="https://www.instagram.com/ryck">Instagram</a>
    &nbsp;—&nbsp; say hi: <a href="mailto:info@ryck.dev">info@ryck.dev</a>
  </sub>
</p>
