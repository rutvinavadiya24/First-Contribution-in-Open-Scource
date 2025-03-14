# First-Contribution-in-Open-Scource Guide

## Steps to add yourself in the contributers list.

1) You will first need git which you can download from [here](https://git-scm.com/downloads).

2) Now head [here](https://github.com/CypherPunk-git/First-Contribution-in-Open-Scource) and click on the `fork` button.

3) On the next page you will see a `create fork` button, press it.

4) You will land on your forked repo page, here you will see a `<> Code` button marked in green, click on it and copy the url.

5) Open your terminal and type git clone <url you copied> and press enter.

6) Now you will see a folder named `First-Contribution-in-Open-Scource`, open it and edit the `README.md` file using any text editor, VScode for example.

7) Below is a code snippet for reference as to what has to ADDED in the file. Inside the `<b> </b>` tag you have to put your name, in the `<href >` tag, you have to place your github profile URL. And lastly you have to place your github profile photo url inside the `src` tag.

    ```
    
    <td align="center">
        <a href="https://github.com/akshitvadher">
            <img src="https://avatars.githubusercontent.com/u/122861906?v=4" width="100px;" alt="Akshit Vadher" />
            <br />
            <sub><b>Akshit Vadher</b></sub>
        </a>
    </td>
    
    ```

8) Now save your changes and exit the editor, type `git add .`, afterwards `git commit -m "<your name> 8"` and lastly `git push origin master`.

9) Go to your forked repo page, `sync` your fork and then there you will see a button in green which says `Open pull request`, press it and in the comments section type "Adding my name to contributer list" and press on `create pull request`.

10) You have created a pull request, wait for a member to review and merge it.
