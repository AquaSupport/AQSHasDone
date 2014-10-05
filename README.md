AQSHasDone
==========

[iOS] "Has done brabra?" flag manager.

```objc
+ (BOOL)hasDone:(NSString *)key;
+ (void)markDone:(NSString *)key;
+ (BOOL)checkAndMarkDone:(NSString *)key;

+ (BOOL)performAndMarkDone:(SEL)selector ifHasNotDoneForKey:(NSString *)key;
+ (BOOL)performBlockAndMarkDone:(void(^)())block ifHasNotDoneForKey:(NSString *)key;
```
