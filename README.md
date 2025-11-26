# UE4 C++ Git Workflow Test

A minimal test project to validate the **Unreal Engine 4.24 + C++ + Git** workflow for our final assignment.


## ✅ Goals
- Confirm C++ classes work with Blueprints  
- Verify Git collaboration setup (3 members)  
- Test build & packaging on Windows  

## 🛠️ What to do
0. Install UE4.24 and VS 2019  

1. Fork this repo to your github account and then clone to local position
2. Right-click `TopDownCpptest.uproject` → **Generate Visual Studio project files**  
3. Open `.sln` in Visual Studio 2019 (Win64, Development Editor)  
4. Press **Ctrl+F5** to compile and launch  
5. Open `TopDownCpptest.uproject` with **Unreal Engine 4.24**
6. Add anything you want in UE(changes may take place in the folder `source`)
7. Go back to VS 2019, use git to commit and pull
8. Go to github, create a pull request to this very repo(not the one you forked)

> — this is a technical prototype only.

## ❗Important: 
- Make sure you have the file `.gitignore` to exclude files we don't need to upload, because they could be generated automatically by UE or VS.


## 📁 Key Folders
- `/Source/` – C++ code (e.g., `ATestActor`)  
- `/Content/` – Test blueprints and map  
- `.gitignore` – Excludes Binaries, Saved, etc.



© 2025 657220