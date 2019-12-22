How to submit software/solution to EasiestSoft.com
===========

Basically, humans may not have much free will

You thoughts and behaviors are not so different from those of other people in the world. Your environment and your past experience determine how your think and behave

We can increase our free will by doing something special

King Eca treats people with special personalities as **free-willed people** and software with special personalities as **free-willed software**

What makes EasiestSoft.com different
--------

There are many software download sites in the world, other than EasiestSoft.com, nothing special

- Anyone can submit software/solution to EasiestSoft, not just the author of the software, [example](https://easiestsoft.com/web/best-software-find-replace-text-in-multiple-files/)

- EasiestSoft.com is not an ordinary software download site, but a software-related solution provider for beginners

  In most cases, people search for solutions to help them get their work done quickly, and once we realize this, we focus on providing **very detailed tutorials/solutions for beginners**, not just list many software names on site

- Submit your software/solution in **markdown** file format, no need to prepare PAD file, no need to fill in the online form. Say goodbye to the old software download sites. Let's fly now

- [Submit software/solution on github](https://github.com/EasiestSoft/submit-software-to-easiestsoft.com). This is the 21st century, why do you still need to sign up again and again on the software download sites? waste time

We are prefer special software (Free-willed software)
-----------

[EasistSoft.com](https://easiestsoft.com) is a special website, of course we are prefer special solutions/software

- A software may not be the best to do one thing, but it is so special to accomplish such a thing, just submit it to us with detailed guide
- You know a solution that can easily accomplish a specific task, and there are no very detailed tutorials on the web, and you don't want to maintain a personal blog yourself, you can submit it to EasiestSoft
- From a certain point of view, one software may not be the best, but it does the work in a special way, you can write a detailed tutorial for it and share it with the world through us
- A software with special User Interface, not everyone likes it, but you really love it, you can write a beginner-friendly guide for it and send it to EasiestSoft
- Other special reasons that you think are worth pushing the solution to the world

Main steps to submit software/solution to EasiestSoft
----------

- [Fork us](https://github.com/EasiestSoft/submit-software-to-easiestsoft.com) on github
- Create your feature branch (`git checkout -b how-to-do-something`)
- Commit your changes (`git commit -am 'Submit how-to-do-something'`)
- Push to the branch (`git push origin how-to-do-something`)
- Create a new Pull Request on [Github.com](https://github.com/EasiestSoft/submit-software-to-easiestsoft.com)

How to write a solution on a local PC:
---------------

- Determine the parent directory
  - `web` directory: for cross-platform solutions (Windows, Mac and Linux), or server side/web related solutions
  - `win` directory: Windows-specific solutions
  - `mac` directory: Mac-specific solutions, currently unavailable
- Create a solution directory under `web` or `win` folder
  - For example [web/best-software-find-replace-text-in-multiple-files](https://github.com/EasiestSoft/submit-software-to-easiestsoft.com/tree/master/web/best-software-find-replace-text-in-multiple-files)

    `best-software-find-replace-text-in-multiple-files` is the solution directory, it should be relevant to the search keywords, and contains at least 5 English words separated by `-`. The directory name should not begin with number(0-9) or `a-`

    Be careful not to insert the software brand or name in the file name
- Create sub-directories and `index.md`
  - [best-software-find-replace-text-in-multiple-files/index.md](https://raw.githubusercontent.com/EasiestSoft/submit-software-to-easiestsoft.com/master/web/best-software-find-replace-text-in-multiple-files/index.md) you write your solution in `index.md`
  - [best-software-find-replace-text-in-multiple-files/img](https://github.com/EasiestSoft/submit-software-to-easiestsoft.com/tree/master/web/best-software-find-replace-text-in-multiple-files/img) images directory for your solution

    Static images can only be in `.png` format, image maximum width is 600px, image size up to 60KB

    Animated GIF has a maximum width of 800px and image size of 300KB
  - `best-software-find-replace-text-in-multiple-files/dl` downloads directory for your solution

    As we do not host binaries currently, please don't put binaries in it

- [index.md](https://raw.githubusercontent.com/EasiestSoft/submit-software-to-easiestsoft.com/master/web/best-software-find-replace-text-in-multiple-files/index.md) consists of 5 parts
   - Title

          This is the document title relevant to the search keywords (usually there is no software brand or name here)
          ===========

      Don't use the following syntax, this is a bad syntax design:

          # This is the article title relevant to the search keywords

  - Description

    For example:

        Find all files in a directory, replace text, preview results, optional regular expression mode - freeware _VS Code_

  - Download

          [Free Download(Windows, Mac and Linux)](https://easiestsoft.com)
          -----------

      Don't use the following syntax, it is ugly:

          ## [Free Download(Windows, Mac and Linux)](https://easiestsoft.com)

  - Main document
  - footer, the last line of the document, for example:

     `2019-12-22 by King Eca`

      - Date format: `YYYY-MM-DD`, should be on the far left of the last line
      - Author: your name

- [stars](https://github.com/EasiestSoft/submit-software-to-easiestsoft.com/tree/master/stars): introduce yourself to the reader (optional)

  Create a folder under `stars` directory, name it with your name, for example:

  `stars/donald-trump/index.md`

  The `index.md` file is only relevant to you, such as your contribution, where you live, things you are interested in...

  You can link to the `index.md` in your contribution like this:

      2019-12-22 by [Donald Trump](../../stars/donald-trump/index.md)

Host binaries on EasiestSoft.com
--------

Currently we do not host binaries, but we can do it if one of the following conditions is met:

- Portable freeware with binary file size less than 5MB, and set the EasiestSoft solution URL as the software homepage
- A really special and small size freeware, the author does not have a personal website, or the author may abandon the homepage in the near future
- Other special cases

Notes
-----

- All directory names and file names should be lowercase
- We do not accept commercial software, Adware, Malware, video converter/editor
- Solutions that link to unsafe page or to non-https pages will be rejected
- Usually we only accept English interface software, unless people can use it by following your very detailed tutorial
- You can zip compress and send your solution to email address: `submit at easiestsoft.com` with the subject `submit the-solution-folder-name` If you don't want to use github

2019-12-22 by King Eca