# macOS-misc
Misc problems and solutions

- brew commnads throws error "/usr/local/Library/Homebrew/version.rb:186:in `initialize': Version value must be a string; got a NilClass () (TypeError)"

  Try reinstall using
  /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install.sh)"

- Install commandline tools for Xcode
  
  xcode-select --install
