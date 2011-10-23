This is an **Xcode Template** which Wraps a THEOS project to allow the usage of Xcode's autocompletion.

NOTE: Uses iPhoneOS**4.3**.sdk for PublicFrameworks by default.


* Add your THEOS Project directory to Xcode (Don't copy)
* Setup your PrivateFrameworks in /opt/theos/frameworks
 * mkdir -p /opt/theos/frameworks/SpringBoard.framework
 * ln -s /opt/theos/include/SpringBoard /opt/theos/frameworks/SpringBoard.framework/Headers
* Configure the Xcode Build script *if desired*