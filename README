# PitchDetector

基于苹果加速库的音高检测
Base on Apple Accelerate Lib, detect audio pitch

# Overview

![](https://github.com/WymanLyu/WYNullView/blob/master/Images/pitchTest.gif)

# 使用

```objc
 PitchDetector *pitchDetector = new PitchDetector(NUMBER_SAMPLES, SAMPLE_RATE);
 Pitch pit = pitchDetector->process(BUFFER_DATA, NUMBER_SAMPLES);
 // get information you need 从Pitch的结果中获取需要的信息【比如音高，频率...】
 printf("frequency:%f - amplitude:%f - octave:%ld - key:%ld - step:%ld - name :%s \n", pit.frequency, pit.amplitude, pit.octave, pit.key, pit.step, pit.stepString.c_str());
```

# 注意

如果是在.m文件使用此类，请修改成.mm

# Hope

If you think it's useful, star to me, Free to share with ideas, issue or pull requests
欢迎提出任何问题，

# License

MIT