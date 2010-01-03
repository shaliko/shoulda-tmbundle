# Shoulda TextMate bundle

To install with Git:

    mkdir -p ~/Library/Application\ Support/TextMate/Bundles
    cd ~/Library/Application\ Support/TextMate/Bundles
    git clone git@github.com:shaliko/shoulda-tmbundle.git "Shoulda.tmbundle"

To install without Git:

    mkdir -p ~/Library/Application\ Support/TextMate/Bundles
    cd ~/Library/Application\ Support/TextMate/Bundles
    wget http://github.com/shaliko/shoulda-tmbundle/tarball/master
    tar zxf shaliko-shoulda-tmbundle*.tar.gz
    rm shaliko-shoulda-tmbundle*.tar.gz
    mv shaliko-shoulda-tmbundle* "Shoulda.tmbundle"