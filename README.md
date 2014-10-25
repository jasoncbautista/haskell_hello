# Simple haskell


Download tar.gz

http://www.haskell.org/cabal/download.html

tar xyzf C[tab]

sudo apt-get install cabal-install


cd C[tab]
cabal install



/// or even better

Install from source

then make sure to add 


~/.cabal/bin 
to beginning of path in bashrc


make sure you have a cabal executable inside that bin folder


export PATH="$HOME/.cabal/bin:$PATH:$HOME/.rvm/bin" 




Yesod:
http://www.yesodweb.com/page/quickstart
cabal install alex happy yesod-bin



http://www.yesodweb.com/page/quickstart


sudo cabal install alex happy yesod-bin


yesod init


// hello
// s

cd hello
sudo cabal install --enable-tests --reorder-goals --max-backjumps=-1 -j
