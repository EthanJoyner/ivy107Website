# EthanJoyner.github.io
Jekyll + Sass + Boostrap Based Website
[Link to Site](https://ivy107.com)

### Dev Environment
- linux!!!
    - dual booting
        - balena etcher to flash linux iso
        - download `.iso` file from ubuntu website
    - virtual machine
        - vmware workstation player
        - or virtualbox
- jekyll
    - google install jekyll for ubuntu
    - follow instructions
    - https://jekyllrb.com/docs/installation/ubuntu/
- sass
    - `sudo apt install sass`

### Running the environment
- `jekyll serve` from root directory
    - runs webhost locally (usually port `4000`)
    - open this in your web browser (`localhost:4000`)
- `sass -w styles.sass:styles.css`
    - this will watch for updates to your `styles.sass` file and write the `styles.css` file for you
- `git add .` + `git commit -m "commit message"` + `git push` to push your changes up
    - or use vscode integrated git

### Design ideas
- https://html5up.net
- https://templated.co/
- Design notes can be found in DesignNotes.md

##### Thank you Tyler Lee for helping me set up the files architecture.
