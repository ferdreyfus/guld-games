Manual to set up VM Ware Ubuntu for Guld Games.

1. Download VM Ware

2. Download Ubuntu Install

3. Set up machine on VMWare with Enough HDD space(50GB+), and ram (2GB+)

4. Load the Ubuntu Install into the Storeage Settings of VMWare Ubuntu Machine.

5. launch and Select language to install ubuntu

6. Choose Keyboard Layout

7. Set up Name and Login Info

8. wait on installation and updates.

9. Restart machine after Installation when prompted

10. Upon restart launch Terminal

11. type in `sudo apt install Git`, `sudo apt get GPA`, `sudo apt-get updates`

12. Restart

13. Git config Data, add the following data with your own

git config --global user.email email@emailprovider.com
git config --global user.name John Doe
git config --global user.username Jondoe
git config --global user.signingkey ASDF213413O872436IJHQWEF987243HASD82389H
git config --global commit.gpgsign true

14. Download GULD, GG, and Price Ledgers into folders named respectively in a folder named Ledger under you home folder ~/home/ledger

15. Use Terminal Git, or a github client to pull and update ledger repos you copied

16. Repos to put into ledger

  git clone https://github.com/TigoCTM/ledger-guld.git
  git clone https://github.com/guld-games/ledger-gg.git
  git clone https://github.com/TigoCTM/token-prices.git

17. Rename Ledgers to `GULD`, `GG`, and `prices` Respectively

18. Download Latest version of Bash GG

19. Run Bash GG for instructions

20. Play!


