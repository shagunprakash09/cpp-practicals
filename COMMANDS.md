# Git commands (replace YOUR-USERNAME)

## Practical 1
1. On github.com create an empty repo `cpp-practicals`.
```bash
git config --global user.name "Shagun Prakash"
git config --global user.email "your-github-email"
git clone https://github.com/YOUR-USERNAME/cpp-practicals.git
cp cpp-practicals/* <cloned-folder>/     # or copy the files in manually
cd cpp-practicals
git add .
git commit -m "Add C++ fundamentals demo"
git push origin main
```

## Practical 12 (commit in steps, as the manual asks)
Create empty repo `library-management-cpp` on GitHub, then:
```bash
git clone https://github.com/YOUR-USERNAME/library-management-cpp.git
cd library-management-cpp
# copy the project files in, then commit one step at a time:
git add .gitignore && git commit -m "Add .gitignore"
git add include/exceptions.h && git commit -m "Add custom exception hierarchy"
git add include/items.h && git commit -m "Add abstract LibraryItem with Book and Magazine"
git add include/library.h && git commit -m "Add Library class with std::map storage and CSV save/load"
git add src/main.cpp && git commit -m "Add console menu and main loop"
git add sample && git commit -m "Add sample CSV and console output"
git add README.md && git commit -m "Add README with features, build steps and UML diagram"
git push origin main
git log --oneline
```
Finally paste both repo links into the manual.
