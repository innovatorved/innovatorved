- 👋 Hi, I’m @innovatorved
- 👀 I’m interested in learning
- 🌱 I’m currently learning Deep learning
- 📫 How to reach me vedgupta@protonmail.com

```python
#!/usr/bin/env python3

__author__ = "Ved Prakash Gupta"
__copyright__ = f"Copyright (c) 2002 {__author__}"
__license__ = "Private Domain"
__version__ = "19.0"

import subprocess
res = subprocess.run(["python3" , "-c" , "print('Never take me lightly\nI am Coming')"],
		capture_output=True, text=True
		)
        
print("stdout:", res.stdout)	# Output
if res.stderr != "" : print("stderr:", res.stderr)	# Error

```

<!---
innovatorved/innovatorved is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
