# Hack-the-school
This game has been done in 4 days by 3 students and myself. You may find some bugs, and the characters have no textures.
The game is still playable, don't worry.

## Important to read
This repo uses LFS, so make sure you have git with LFS installed : 
```
  #1 (git install)
curl -LO https://github.com/git-for-windows/git/releases/download/v2.42.0.windows.1/Git-2.42.0-64-bit.exe
  #2 (git install)
Git-2.42.0-64-bit.exe /VERYSILENT /NORESTART
  #3 (LFS install)
curl -LO https://github.com/git-lfs/git-lfs/releases/download/v3.4.0/git-lfs-windows-amd64-v3.4.0.zip
  #4 (LFS install)
powershell -Command "Expand-Archive -Path git-lfs-windows-amd64-v3.4.0.zip -DestinationPath ."
  #5 (LFS install)
git-lfs-windows-amd64-v3.4.0.exe
  #6 (LFS install)
git lfs install
```
Then, go in the directory in which you want the game to be and clone the repo : 
```
  #1 (go to the directory)
cd "/your/directory/path"
  #2 (git clone)
git clone https://github.com/ImRitchy/Hack-the-school.git
  #3 (use LFS)
git lfs pull
```
Now you can run the .exe using your mouse or : 
```
"Hack-the-school\game\game.exe"
```

## More informations
__-> objective :__ Hack the school by stealing teachers' stuff without getting caught

__-> controls :__ Z,Q,S,D to move, space to jump, C to crouch, A to interract, Left click to throw paper. Control can be changed before starting the game (main menu)

__-> tips :__ There is 1 object to take per room. You'll get a checkpoint after finishing each room. Crouching make you less visible to teachers. Throwing things could disturb them and help you win.
