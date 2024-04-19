Install
=======
#Install Go\
`winget install GoLang.Go` \

#Install Git\
`winget install Git.Git` \

#Install Cheat package \
`go install github.com/cheat/cheat/cmd/cheat@latest` \

#Clone cheatsheets and config
`cd $env:APPDATA; git clone https://github.com/p-jach/cheat.git`

Usage
-----
#List all cheatsheets
`cheat -l` \

#View "net" cheatsheet
`cheat net` \

#List all cheatsheets containing "net"
`cheat -s net`

Links
-----
https://go.dev/doc/install \
https://github.com/cheat/cheat \
https://github.com/p-jach/cheat