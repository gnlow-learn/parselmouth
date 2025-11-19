# parselmouth
```py
import parselmouth as pm

s = pm.Sound("mySound.flac")

# 0.5초 시점의 F1
print(s.to_formant_burg().get_value_at_time(1, 0.5))
```

##
```
uv init
uv add praat-parselmouth
```
- Windows에서 안돼서 WSL로 했음
