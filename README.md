# Invitilo <!-- omit in toc -->
Like the name says in Esperanto, a command prompt. But with themes and more. For now only Bash is supported.

- [Getting started](#getting-started)
- [Why yet another themed command prompt?](#why-yet-another-themed-command-prompt)
- [Some things I learned along the way](#some-things-i-learned-along-the-way)
- [About the name](#about-the-name)


## Getting started

_It is assumed you have Bash installed and configured on your system._

1. **Find the latest release**: Visit the [Latest release page](https://github.com/leebehrens/invitilo/releases/latest) for Invitilo on GitHub.

2. **Download the installer**: Download the `install-invitilo` script from the assets section of the latest release.

3. **Run the installer**: Open a terminal and execute the following commands:
    ```bash
    # cd to the directory where you downloaded `install`
    chmod u+x install-invitilo
    ./install-invitilo
    ```

## Why yet another themed command prompt?
Look! A shiny programming challenge to solve.

It started with a few simple formatting changes to `PS1` in my `.bashrc`. Then it was ensuring the prompt always started on a new line. Up next was how to format the Python virtual environment indicator when it appeared in the prompt. And then Git branch info.

By then, I (again) ran across a few screen shots with [Powerline](https://github.com/powerline/powerline)-like command prompts of varying themes. Themes, hmm...

Look! Another shiny programming challenge to solve.

## Some things I learned along the way
- Available prompt features
- A lot of nifty features in Bash
- Locating the cursor position in the terminal
- Curious quirks Linux environments
- Python virtual environment state
- Determine the active Git branch and related info
- GitHub release automation

## About the name
invitilo: 💻 Signo aŭ mesaĝo, montrata surekrane por indiki, ke la programo atendas enigaĵon de la uzanto. (fonto: [PIV2020](https://vortaro.net/#invitilo_kdc))

Command prompt: A sign or message shown on screen to indicate that the program is waiting for input from the user.
