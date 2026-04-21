# wrappers
Fake termux wrappers for su and sudo


Dependencies:
1. bash
2. coreutils
3. moreutils
4. git


Installation:
```bash
git clone https://https://github.com/tanazd2-dev/wrappers.git
cd wrappers
cp su $PREFIX/bin/ || cp su /usr/bin/ || cp su /bin/
cp sudo $PREFIX/bin || cp sudo /usr/bin/ || cp sudo /bin/
cp tsu $PREFIX/bin/ || cp tsu /usr/bin/ || cp tsu /bin/
chmod +x $PREFIX/bin/* || chmod +x /usr/bin/* || chmod +x /bin/
```
