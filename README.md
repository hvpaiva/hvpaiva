```rust
// 👋 Hey there, I'm Highlander Paiva! 🇧🇷

struct Developer {
    name: &'static str,
    role: &'static str,
    country: &'static str,
    current_job: &'static str,
    goal: &'static str,
    linkedin: &'static str,
    fun_fact: &'static str,
}

impl Developer {
    fn new() -> Self {
        Developer {
            name: "Highlander Paiva",
            role: "Backend Developer",
            country: "Brazil",
            current_job: "Software Engineer SSr at Mercado Livre",
            goal: "Become a versatile and impactful Software Architect",
            fun_fact: "My name is based on the movie 'Highlander (1986)'. There can be only one! ⚔️",
        }
    }

    fn introduce(&self) {
        println!("👋 Hey there, I'm {}! 🇧🇷", self.name);
        println!("🚀 {} from {}, currently working as {}.", self.role, self.country, self.current_job);
        println!("🎯 Goal: {}", self.goal);
        println!("🎬 Fun fact: {}", self.fun_fact);
    }

    fn advise(&self) {
        println!("🌟 Keep exploring, learning, and having fun! 🌟");
    }
}

fn main() {
    let highlander = Developer::new();

    highlander.introduce();
    highlander.advise();
}

```

- 🔗 LinkedIn: [Highlander Paiva](https://www.linkedin.com/in/hvpaiva)


<br/>

<div align="center">
  <a href="https://github.com/hvpaiva">
  <img height="180em" src="https://github-readme-stats.vercel.app/api?username=hvpaiva&show_icons=true&theme=dark&include_all_commits=true&count_private=true"/>
  <img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=hvpaiva&layout=compact&langs_count=5&theme=dark&&hide=javascript,typescript,vue,html,java,c%23"/>
</div>

<br/>
