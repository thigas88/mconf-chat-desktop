This is a branch of the Psi project (http://psi-im.org/) to implement the multiplatform Mconf.org Chat client.


Setting up enviroment
==========
To start work with this project, there are two simple steps: installing the dependencies and getting the source.


Dependencies
----------

The psi projects depends on QT, as it is explained on their documentation. To install this dependency on a Ubuntu 12.04 OS, it as simple as run the fallowing command:
 	`sudo apt-get install build-essential qt4-dev-tools libqt4-dev libqt4-dev libqt4-core libqca2 libqca2-dev libqca2-plugin-ossl libqca2-plugin-gnupg qtcreator zlib1g-dev zlib-bin`

And then you download and install QCA, according to INSTALL file on the root folder of QCA source. You can obtain this source on the fallowing link:
    `http://delta.affinix.com/qca/`

Getting the source
----------

First you need to clone this repository:
	`git clone https://github.com/mconf/mconf-chat-desktop.git`

Then you must initialize the submodules of the project with the commands:
	`git submodule init`
	`git submodule update`

Now you should execute the fallowing command on the root folder of the downloaded source:
    `./configure`

Then you simply open the psi.pro file on your QT Creator IDE and hit the run button.
