# home-office-setup
These are scripts to set up my local environment

### Steps
1. Begin by running ./prereqs.sh to install homebrew and ansible
2. Open playbook.yml and uncomment the lines to install brew cask [TODO make this idempotent, Alexandra]
3. Run the ansible playbook.yml by executing ./runansible.sh. 

**Note:** Which came first, the chicken or the egg? The one manual step might be to install git, or you can copy these files locally and install git using homebrew after step 1.




