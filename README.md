AQSHasDone
==========

[iOS] "Has done brabra?" flag manager.

```objc
+ (BOOL)hasDone:(NSString *)key;
+ (void)markDone:(NSString *)key;
+ (BOOL)checkAndMarkDone:(NSString *)key;

+ (BOOL)perform:(SEL)selector ifHasNotDoneForKey:(NSString *)key;
+ (BOOL)performBlock:(void(^)())block ifHasNotDoneForKey:(NSString *)key;
```
