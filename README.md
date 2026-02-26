```rust
struct Developer {
    name: &'static str,
    role: &'static str,
    mode: &'static str,
    caffeine: u8,
    stack: [&'static str; 7],
}

fn main() {
    let me = Developer {
        name: "Diya Mehra",
        role: "Backend Dev & Blockchain Dev",
        mode: "Building 🛠️",
        caffeine: 82,
        stack: ["Rust 🦀","TS 🟦","JS 🟨", "Python 🐍"],
    };

    println!("{} | {}", me.name, me.role);
    println!("Mode: {} | Caffeine: {}%", me.mode, me.caffeine);
    println!("Stack: {}", me.stack.join(" • "));
}
```
## 📊 GitHub Stats

![GitHub Stats](https://github-readme-stats-sigma-five.vercel.app/api?username=Diya28-mehra&show_icons=true&theme=tokyonight)

![Top Languages](https://github-readme-stats-sigma-five.vercel.app/api/top-langs/?username=Diya28-mehra&layout=compact&theme=tokyonight)

