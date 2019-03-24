# Regex
### Tổng hợp các biểu thức chính quy <br/>
***1.Để lấy date từ một chuỗi:***
```
import re
date=re.findall("\d+/\d+/\d+", "03/25/93 Total time of visit (in minutes):\n")
print(date)
```
Kết quả:
```
[‘03/25/93’]
```
