Reverse for 'sign_up' not found. 'sign_up' is not a valid view function or pattern name.

在找 LibreOffice Python 巨集資料的時候找到這個網站，頗好玩：
https://thebiasplanet.blogspot.com/2017/01/wehavecometothebiasplanet.html
https://thebiasplanet.blogspot.com/2018/04/basicelementsofuno.html
https://thebiasplanet.blogspot.com/2018/03/whatwecandobyexploitinglibreofficeorapacheopenoffice.html

```
import contextlib

with contextlib.suppress(FileNotFoundError): os.remove('somefile.tmp')
```
equivalent to:
```
try:
    os.remove('somefile.tmp')
except FileNotFoundError:
    pass
```
