# Git Configuration and Setup

## Setting up your Git configuration

To set up your Git username and email, run the following commands:

```bash
git config --global user.name "Favour Ehizojie-Philips"
git config --global user.email "favourphilips1705@gmail.com"

$ git  config -l
user.email=favourphilips1705@gmail.com
user.name=Favour Ehizojie-Philips

$ git remote -v
origin  https://github.com/FavourPhilips/altschool-cloud-exercises.git (fetch)
origin  https://github.com/FavourPhilips/altschool-cloud-exercises.git (push)

$ git log
commit d66d36faafb598fb550315322d08c11d8236ca06 (HEAD -> master)
Author: Favour Ehizojie-Philips <favourphilips1705@gmail.com>
Date:   Wed Nov 13 15:35:58 2024 +0000

    Initial commit