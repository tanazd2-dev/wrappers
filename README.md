# wrappers
Fake termux wrappers for su and sudo


Dependencies:
1. bash
2. coreutils
3. moreutils
4. git


Installation:
```bash
git clone https://tanazd2-dev/wrappers.git
cd wrappers
mv su $PREFIX/bin/ || mv su /usr/bin/ || mv su /bin/
mv sudo $PREFIX/bin || mv sudo /usr/bin/ || mv sudo /bin/
chmod +x $PREFIX/bin/* || chmod +x /usr/bin/* || chmod +x /bin/
```
