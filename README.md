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
        stack: [
            "Rust 🦀",
            "Solana ⚡",
            "TS 🟦",
            "JS 🟨",
            "Next ▲",
            "React ⚛️",
            "Django 🐍",
        ],
    };

    println!("{} | {}", me.name, me.role);
    println!("Mode: {} | Caffeine: {}%", me.mode, me.caffeine);
    println!("Stack: {}", me.stack.join(" • "));
}
```
