# Environment Setup

This is an ansible configuration to setup my OS X machine.

## Installation

  1. Ensure Apple's command line tools are installed (`xcode-select --install` to launch the installer).
  2. Install pip
  3. Clone this repository to your local drive.
  4. Run `$ pip install -r requirements.txt`
  5. Run `$ ansible-galaxy install -r requirements.yml` inside this directory to install required Ansible roles.
  6. Run `ansible-playbook main.yml -i inventory -K` inside this directory. Enter your account password when prompted.

> Note: If some Homebrew commands fail, you might need to agree to
> Xcode's license or fix some other Brew issue. Run `brew doctor` to
> see if this is the case.
