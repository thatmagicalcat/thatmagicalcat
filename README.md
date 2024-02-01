```rs
struct Programmer {
    name: String,
    age: u32,
    loves_rust: bool,
    known_languages: Vec<String>,
    discord: String,
}

fn main() {
    let wizard = Programmer {
        name: String::from("Pranjal Patel"),
        age: 16,
        loves_rust: true,
        discord: String::from("thatmagicalcat"),
        known_languages: vec![
            "Rust".into(),
            "C/C++".into(),
            "Assembly".into(),
            "Python".into(),
        ],
    };
}
```
