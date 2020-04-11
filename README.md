# openssl10
Brew formula to install openssl 1.0.2u (for PowerShell Core 7 on macOS)

# Related Issues
- [Cannot Connect to Office 365 Exchange 2016 via terminal in 10.15.1 (Catalina) · Issue #11188 · PowerShell/PowerShell](https://github.com/PowerShell/PowerShell/issues/11188)
- [macOS can't use New-PSSession to Connect to O365 from PowerShell Host - WSMAN client library not found · Issue #10600 · PowerShell/PowerShell](https://github.com/PowerShell/PowerShell/issues/10600)

# Installation Steps
```
brew install https://github.com/luckman212/openssl10/releases/download/1.0.2u/openssl@1.0.rb
rm /usr/local/opt/openssl
ln -s /usr/local/Cellar/openssl@1.0/1.0.2u /usr/local/opt/openssl
```
