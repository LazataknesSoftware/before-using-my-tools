Here are questions that can be asked by future users of my programs to me.

**Legend:**
* **Q** - question
* **A** - answer

---

**Q**: I tried to open your tool by double-click and got Windows Script Host window with error `"console" is undefined`. Did you give me tool which does not work?

**A**: Of course, no! My tools are incompatible with Windows Script Host. You should install Node.js to use my tools.

---

**Q**: Why should I install Node.js on my computer? Where are installers of your programs?!

**A**: 
1. First read what is [programming language](https://en.wikipedia.org/wiki/Programming_language), [interpreter](https://en.wikipedia.org/wiki/Interpreter_(computing)), [JavaScript](https://en.wikipedia.org/wiki/JavaScript) and [Node.js](https://en.wikipedia.org/wiki/Node.js).
2. Let me tell a story from personal experience:
> **Once upon I converted js-code to executable file (.exe on Windows). The result was not encouraging: executable was heavy-weight (82 MB)! How many space of disk will be used if I develop 1000 projects? 82 GB?! What a nightmare! So I decided to ask users to install Node.js on their computers and tool (which user wants (DateNTimeChief, for example)). It is good: interpreter will use nearly 82 MB (may be) and 1000 scripts will use 4 MB of disk space.**

---

**Q**: I bought new laptop. And I should install Node.js to use your tools? I will litter my operating system!

**A**: There is portable Node.js-version called "Windows Binary" which does not require install. Just unpack downloaded zip-archive to folder which is convievent for you.

---

**Q**: How to use your tools on Android? I don't see APKs of them.

**A**: If you want to use my tools on Android, you should follow next steps:

1. Install Termux (Linux environment on your Android) from F-Droid.
2. Wait while Termux installs bootstrap packages.
3. Execute in Termux `apt update`
4. Execute in Termux `apt install coreutils`
5. Execute in Termux `pkg install nodejs`
6. Wait while nodejs is installing.
7. Done!

---

**Q**: I don't understand how to execute your tool.

**A**: To execute my tool, you must use command prompt (cmd.exe). Follow these steps:
* On Windows:
    1. Press Win+R
    2. Type `cmd.exe` and press Enter.
    3. Remember where did you unpack Node.js and where did you download my tool.
    4. Type `<path to Node.js>/node.exe <path to my tool>`
       
       where is:
       
         * \<path to Node.js\> - path where you unpacked Node.js
         * \<path to my tool\> - path where you downloaded my tool.
           
           **Paths with spaces must be put in quotation marks!**
       
       > **Useful tip!**
       > 
       > On Windows, you can just drag and drop a file from explorer into cmd.exe window to get its full path.

---

**Q**: Where is graphical interface?! Only white text on black background!

**A**: 
1. First read what is [command-line interface](https://en.wikipedia.org/wiki/Command-line_interface).
2. I couldn't find normal GUI library for Node.js.
3. If there are some GUI libraries, then they are heavy-weight for small projects like calculator.

---

**If you have questions or there are misexactings in my FAQ, then make an issue!**
