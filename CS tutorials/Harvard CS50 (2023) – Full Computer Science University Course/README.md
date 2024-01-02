# Harvard CS50 (2023) – Full Computer Science University Course

- [Official CS50 site][1]
- [Youtube Video from FreeCodeCamp][2]
- [VS code cloud based version][3]
- [Manual pages for the C standard library, the C POSIX library, and the CS50 Library for those less comfortable][4]
- [cs50.h file repository][5]
- [cs50 repository][6]

Learn the basics of computer science from Harvard University. This is CS50, an introduction to the intellectual enterprises of computer science and the art of programming. The course is taught live every year and this is the 2023 version.

💻 Slides, source code, and more at https://cs50.harvard.edu/x. 

⭐️ Course Contents ⭐️
⌨️ ([00:00:00](https://www.youtube.com/watch?v=LfaMVlDaQ24&t=0s)) Lecture 0 - Scratch

⌨️ ([02:05:47](https://www.youtube.com/watch?v=LfaMVlDaQ24&t=7547s)) Lecture 1 - C
- how to install cs50.h

  ```bash
  curl -s https://packagecloud.io/install/repositories/cs50/repo/script.deb.sh | sudo bash
  sudo apt-get install libcs50
  ```
  or
  ```bash
  # Install from source
  git clone https://github.com/cs50/libcs50.git
  cd libcs50
  sudo make install
  ```

- how to run C code

  ```bash
  gcc hello.c -o hello
  ./hello
  ```
  or
  ```bash
  clang hello.c -o hello
  ./hello
  ```
  or
  ```bash
  make hello
  ./hello
  ```

- if you will have problem with compiling your code with cs50.h file you can try to compile it another way.
1. first download libcs50
2. copy from libcs50 folder src folder with files cs50.h and cs50.c
3. paste it to your project folder
4. compile your file with cs50.c file
```bash
gcc -o hello hello.c src/cs50.c
./hello
```


⌨️ ([04:35:19](https://www.youtube.com/watch?v=LfaMVlDaQ24&t=16519s)) Lecture 2 - Arrays

⌨️ ([06:59:38](https://www.youtube.com/watch?v=LfaMVlDaQ24&t=25178s)) Lecture 3 - Algorithms

⌨️ ([09:01:13](https://www.youtube.com/watch?v=LfaMVlDaQ24&t=32473s)) Lecture 4 - Memory

⌨️ ([11:26:33](https://www.youtube.com/watch?v=LfaMVlDaQ24&t=41193s)) Lecture 5 - Data Structures

⌨️ ([13:42:44](https://www.youtube.com/watch?v=LfaMVlDaQ24&t=49364s)) Lecture 6 - Python

⌨️ ([15:58:02](https://www.youtube.com/watch?v=LfaMVlDaQ24&t=57482s)) Lecture 7 - SQL

⌨️ ([18:18:30](https://www.youtube.com/watch?v=LfaMVlDaQ24&t=65910s)) Lecture 8 - HTML, CSS, JavaScript

⌨️ ([20:58:14](https://www.youtube.com/watch?v=LfaMVlDaQ24&t=75494s)) Lecture 9 - Flask

⌨️ ([23:19:07](https://www.youtube.com/watch?v=LfaMVlDaQ24&t=83947s)) Lecture 10 - Emoji

⌨️ ([25:05:28](https://www.youtube.com/watch?v=LfaMVlDaQ24&t=90328s)) Cybersecurity


---

Learn to code for free and get a developer job: https://www.freecodecamp.org

Read hundreds of articles on programming: https://freecodecamp.org/news


[1]:https://cs50.harvard.edu/x/2023/
[2]:https://www.youtube.com/watch?v=LfaMVlDaQ24
[3]:https://cs50.dev/
[3]:https://code.cs50.io/
[4]:https://manual.cs50.io/
[5]:https://github.com/cs50/libcs50
[6]:https://github.com/cs50
