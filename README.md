# JHGestureBlock
Use gesture with block，手势，Block

---

# Usage
```
    [self.view addGestureRecognizer:JHGestureType_Tap block:^(UIView *view, UITapGestureRecognizer *gesture) {
        // do your stuff!
        // 是时候露一手了！
        
        // example
        [view removeGestureRecognizer:gesture];
    }];
    
    
    [yourView addGestureRecognizer:JHGestureType_Swipe block:^(YourView *view, UISwipeGestureRecognizer *gesture) {
        // do your stuff!
        // 是时候露一手了！
        
        // example
        [view hide];
    }];
```

---

# Logs
### 2019-06-13
1.fix a warning.
- 找到一个警告.

### 2019-04-10
1.upload.
- 上传.

---
