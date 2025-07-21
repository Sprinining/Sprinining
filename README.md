## Hi there 👋

<!--
**Sprinining/Sprinining** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->

```cpp
#include <iostream>
#include <string>

class Learner {
public:
    void learn(const std::string& concept) {
        std::cout << "[Starting to explore new concept] — " << concept << std::endl;
        askWhat(concept);
        askWhyImportant(concept);
        askWhyLearn(concept);
        askWhenToUse(concept);
        askHowItWorks(concept);
        std::cout << "[Exploration complete]\n" << std::endl;
    }

private:
    void askWhat(const std::string& concept) {
        std::cout << "1. What is " << concept << "?" << std::endl;
    }

    void askWhyImportant(const std::string& concept) {
        std::cout << "2. Why is " << concept << " important?" << std::endl;
    }

    void askWhyLearn(const std::string& concept) {
        std::cout << "3. Why should I learn " << concept << "?" << std::endl;
    }

    void askWhenToUse(const std::string& concept) {
        std::cout << "4. When will I use " << concept << "?" << std::endl;
    }

    void askHowItWorks(const std::string& concept) {
        std::cout << "5. How does " << concept << " work?" << std::endl;
    }
};
```

![Snake animation](https://raw.githubusercontent.com/Sprinining/Sprinining/output/github-contribution-grid-snake.svg)

