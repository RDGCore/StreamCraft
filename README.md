git clone https://github.com/nanox11/TikCraft-updates.git
cd TikCraft-updates
git checkout --orphan clean
git rm -rf .
echo "# TikCraft Releases" > README.md
git add README.md
git commit -m "init: releases-only repo"
git branch -M main
git push -f origin main
