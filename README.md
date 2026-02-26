enum Mode {
    Learning,
    Building,
    Shipping,
}

struct Developer {
    name: &'static str,
    role: &'static str,
    mode: &'static str,
    caffeine_level: u8,
    tech_stack: Vec<&'static str>,
}

fn main() {
    let diya = Developer {
        name: "Diya Mehra",
        role: "Full Stack & Blockchain Developer",
        mode: "Building 🛠️",
        caffeine_level: 82,
        tech_stack: vec![
            "Rust 🦀",
            "Solana ⚡",
            "TypeScript 🟦",
            "JavaScript 🟨",
            "Next.js ▲",
            "React ⚛️",
            "Django 🐍",
        ],
    };

    println!("Name → {}", diya.name);
    println!("Role → {}", diya.role);
    println!("Mode → {}", diya.mode);
    println!("Caffeine Level → {}%", diya.caffeine_level);
    println!("Tech Stack → {}", diya.tech_stack.join(" | "));
}
