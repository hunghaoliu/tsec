mkdir tsrtc
cd tsrtc/
git init
git config core.sparseCheckout true
git remote add origin https://github.com/hunghaoliu/tsrtc.git
vim .git/info/sparse-checkout
     /*
     !data
git pull origin master     
