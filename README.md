```c++
#include <vector>
#include <string_view>

struct Programmer {
  std::string_view name;
  unsigned int age;
  bool loves_cpp;
  std::vector<std::string_view> known_languages;
};

int main() {
  Programmer wizard {
    .name = "Pranjal Patel",
    .age = 15,
    .loves_cpp = true,
    .known_languages = { "C++", "C", "Rust", "Python", "Javascript", "x86 Assembly" }
  };
}
```

Discord: wizard#2219
