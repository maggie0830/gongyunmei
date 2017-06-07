# gongyunmei
Audio Feature Extractor &amp; audio classification
(sudo) git clone --recursive https://github.com/Yaafe/Yaafe.git
brew install cmake
brew search libsndfile
brew install libsndfile
brew install mpg123
brew install homebrew/science/hdf5
brew install homebrew/science/scalapack
brew install argtable 

mkdir build
cd build
ccmake -DCMAKE_PREFIX_PATH=/usr/local/Cellar -DCMAKE_INSTALL_PREFIX=/Users/gongyunmei/anaconda/lib/python3.6/site-packages ..
make
make install

________install done

env:
vim ~/.bash_profile 
export PYTHONPATH=/usr/local/lib/python3.6/site-packages:$PYTHONPATH
