# 💻 Code & Content Tabs Showcase

Welcome to my **Code & Content Tabs Showcase** — a demonstration of how I structure and present multi-language, developer-focused documentation using **[Material for MkDocs](https://squidfunk.github.io/mkdocs-material/)**.

This page reflects my ability to combine **clarity**, **technical accuracy**, and **modern design**, creating documentation that developers actually enjoy reading.

---

## 🚀 Why This Matters

In developer documentation, clarity is everything.

Great documentation doesn’t just explain, it **teaches**, **guides**, and **inspires**.  
That’s why I use clean formatting, interactive tabs, and callouts to help readers absorb information faster.

!!! note "Developer Experience First"
    Every decision here (layout, tone, formatting, or visuals), is made with the **developer experience** in mind.  
    When documentation feels effortless, adoption naturally follows.

---

## 🧱 Content Tabs in Action

Below are some examples of how I present different types of content (text, lists, and code) in a modular and modern way.

### Generic Content

=== "Plain text"

    This is some plain text.

=== "Unordered list"

    * First item
    * Second item
    * Third item

=== "Ordered list"

    1. First item
    2. Second item
    3. Third item

!!! tip "Why Use Content Tabs?"
    Content tabs help developers **find examples in their preferred format** without scrolling endlessly.  
    This approach works beautifully for SDK documentation, API endpoints, or setup instructions across multiple platforms.

---

## 🧠 Code Examples in Multiple Languages

As a **technical writer and AI engineer**, I understand that documentation often needs to support developers working in different stacks.  
That’s why I organize code examples with clean tabs and consistent formatting.

=== "Python"

    ```py
    def main():
        print("Hello world!")

    if __name__ == "__main__":
        main()
    ```

=== "JavaScript"

    ```js
    function main() {
        console.log("Hello world!");
    }

    main();
    ```

=== "C++"

    ```cpp
    #include <iostream>
    using namespace std;

    int main() {
        cout << "Hello world!" << endl;
        return 0;
    }
    ```

=== "Bash"

    ```bash
    echo "Hello world!"
    ```

??? info "Multi-Language Code Examples"
    Supporting multiple programming languages in a single documentation flow makes your product **accessible to a broader audience**.  
    Developers can instantly switch to the example that fits their environment — no searching required.

---

## ⚙️ Advanced Callouts for Context

I also use **admonitions and collapsible info blocks** to guide users through complex technical information while keeping the interface clean.

!!! example "Quick Setup Example"
    Here's how you can start a live MkDocs server to preview documentation in real-time.

    ```bash
    mkdocs serve
    ```

    Then open your browser at `http://127.0.0.1:8000` to view your docs.

??? success "Pro Tip: Automate with GitHub Actions"
    You can automatically build and deploy your MkDocs site to **GitHub Pages** using **CI/CD workflows**.

    ```yaml
    name: Deploy Docs
    on:
      push:
        branches: [ main ]
    jobs:
      deploy:
        runs-on: ubuntu-latest
        steps:
          - uses: actions/checkout@v3
          - uses: actions/setup-python@v4
            with:
              python-version: "3.x"
          - run: pip install mkdocs-material
          - run: mkdocs gh-deploy --force
    ```

---

## 🧩 Why I Build Docs Like This

Every documentation system I build is guided by three core principles:

1. **Clarity:** Technical information should be easy to follow and free from unnecessary complexity.  
2. **Consistency:** Readers shouldn’t have to “learn” how to read your docs, structure should feel familiar across pages.  
3. **Scalability:** From a single API reference to a 100-page developer portal, I build docs that scale with your product.

---

!!! quote "My Philosophy"
    *“Good documentation turns confusion into confidence.”*  
    — Victory Nnaji

---

## 📚 Built With

- **MkDocs** – Static site generator for elegant documentation  
- **Material for MkDocs** – Modern, responsive, developer-focused theme  
- **Markdown & YAML** – Simple, lightweight authoring  
- **GitHub Pages + GitHub Actions** – Continuous deployment and version control  

---

## 🏁 Summary

This page demonstrates:
- My ability to design **interactive, developer-first documentation**
- Use of **advanced Markdown features** in Material for MkDocs
- Technical and stylistic consistency across **multi-language examples**
- My approach to building documentation that **educates and delights developers**

> 💬 *If you want documentation that feels like a product, not an afterthought, I can help you design it.*

---

## A Little Personality

Outside of code and documentation, I to play piano, saxophone or watch documentaries on Youtube

